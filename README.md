# ITMO_ScientificPython_2026
Scientific Python course ITMO 2026

# HW1: Decoding Base64 Image from Text File

Instructions on how to decode a Base64-encoded image string stored in a text file back into an image file.

## Prerequisites

- **Linux/Unix/macOS**: Base64 utility is pre-installed
- **Windows**: 
  - Option 1: Use Windows Subsystem for Linux (WSL)
  - Option 2: Use Git Bash
  - Option 3: Install Base64 for Windows manually

## Instructions

Example content of `input_image.txt`:

### Step 1: Decode the image

Open your terminal/command prompt and navigate to the directory containing your text file:

```bash
cd /path/to/your/file

Run the following command to decode the image:

```bash
base64 -d input_image.txt > output_image.png

**### Step 2: Verify the result**
Check that the image was created successfully:

```bash
ls -la
