# Steganography
A Python tool that decodes secret messages hidden in Google Docs using Unicode character grids. Inspired by coordinate-based steganography techniques

This decoder reads specially formatted text documnets containing Unicode characters and their 2D coordinates, then reconstructs them into a visual grid that reveals hidden messages. When displayed in a fixed-width font, the characters form readable text or symbols.

# ✨ Features

- Document Parsing: Automatically fetches and parses Google Docs via public URLs
- Flexible Grid System: Supports arbitrary grid sizes with (0,0) at bottom-left
- Unicode Support: Handles any Unicode characters including special symbols

# 📋 Document Format
Your Google Doc should contain a table with three columns:

- x-coordinate: Horizontal position (0 = leftmost)
- Character: Any Unicode character
- y-coordinate: Vertical position (0 = bottom)

![image](https://github.com/user-attachments/assets/86042ef3-0e64-4ff1-b158-96b32bd83d17)

# Hidden Message

![image](https://github.com/user-attachments/assets/ab8c9fa0-222f-485e-bc84-1bbf69ba0d2f)
