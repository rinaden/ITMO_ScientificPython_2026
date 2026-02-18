# ITMO_ScientificPython_2026
Scientific Python course ITMO 2026

# HW1: Decoding Base64 Image from Text File

Instructions on how to decode a Base64-encoded image string stored in a text file back into an image file.

## Prerequisites

- **Linux/Unix/macOS**: Base64 utility is pre-installed
- **Python 3.x** (for encoding)

## Instructions

Example content of `input_image.txt`.

Open any preferable IDE and create a Python script:

```python
import base64 # Decoding

f = open('input_image.txt', 'rb')  # Open encoded file
byte = f.read()  # Read data
f.close()

decode = open('image_name.png', 'wb')  # Open image file to save
decode.write(base64.b64decode(byte))  # Decode and write data
decode.close()
```
