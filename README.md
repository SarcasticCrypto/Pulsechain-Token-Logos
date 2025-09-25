# Pulsechain Token Logos

A comprehensive collection of token logos for assets on the Pulsechain network.

## Overview

This repository serves as a centralized resource for Pulsechain token logos, aggregated from various platforms including DexScreener and other DeFi platforms. It provides developers and users with easy access to high-quality token images for use in their applications, tools, and projects.

## Purpose

- **Centralized Asset Library**: One-stop source for Pulsechain token logos
- **Developer Resource**: Easy integration for dApps, wallets, and other tools
- **Community Driven**: Aggregated from multiple trusted sources
- **Standardized Format**: Consistent PNG format for all token logos

## Usage

Token logos are stored in the `logos/` folder and named using the token's contract address:
```
logos/0x1234567890abcdef1234567890abcdef12345678.png
```

Simply reference the token by its contract address to retrieve the corresponding logo.

## How to Submit Missing Logos (No Coding Required!)

### Method 1: GitHub Web Interface (Easiest)

1. **Find Your Token's Contract Address**
   - Go to [PulseScan](https://pulsechain.com) or your preferred explorer
   - Search for your token
   - Copy your token's full contract address (starts with 0x, should be 42 characters total)
   - Example: `0x1234567890abcdef1234567890abcdef12345678`

2. **Prepare Your Logo**
   - **Resize your logo** (if needed):
     - Use this free tool: [Simple Image Resizer](https://www.simpleimageresizer.com/)
     - Upload your logo
     - Set dimensions to 256x256 pixels
     - Keep "Maintain Aspect Ratio" checked
     - Download the resized image

   - **Convert to PNG** (if needed):
     - If your logo is JPG/JPEG/SVG, use: [CloudConvert](https://cloudconvert.com/png-converter)
     - Upload your file and convert to PNG

   - **Remove background** (optional but recommended):
     - Use [Remove.bg](https://www.remove.bg/) for automatic background removal
     - Works great for logos with solid backgrounds

   - **Rename your file**:
     - Right-click your PNG file
     - Select "Rename"
     - Paste your contract address as the filename
     - Keep the .png extension
     - Final name example: `0x1234567890abcdef1234567890abcdef12345678.png`

3. **Upload via GitHub**
   - Go to this repository's main page
   - Navigate to the `logos` folder
   - Click the "Add file" button (near the green "Code" button)
   - Select "Upload files"
   - Drag and drop your properly named PNG file
   - In the "Commit changes" section:
     - Add a title like: "Add [Your Token Name] logo"
     - Optionally add a description
   - Select "Create a new branch" (should be default)
   - Click "Propose changes"
   - Click "Create pull request"
   - Done! We'll review and merge it soon

### Method 2: Submit via Issues

1. Go to the "Issues" tab above
2. Click "New Issue"
3. Title: "Add [Your Token Name] Logo"
4. Include:
   - Token contract address
   - Link to your logo file (Google Drive, Imgur, etc.)
   - Token name and symbol
5. Submit the issue

### Logo Requirements

- **Format**: PNG only
- **Size**: Minimum 256x256 pixels
- **Quality**: Clear, high-resolution
- **Background**: Transparent preferred
- **File Name**: Must be the full contract address (e.g., `0x1234567890abcdef1234567890abcdef12345678.png`)

## Contributing

If you have token logos that are missing from this collection, feel free to submit them using the methods above or create a pull request if you're familiar with Git.

## License

These logos are aggregated from public sources for community use. Individual token logos remain the property of their respective projects.