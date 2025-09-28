<div align="center">
  <img src="https://pulsechain.com/images/wordmark.png" alt="PulseChain" width="400" />

  # PulseChain Token Logos

  [![PulseChain](https://img.shields.io/badge/Network-PulseChain-FF0099?style=for-the-badge)](https://pulsechain.com)
  [![Token Count](https://img.shields.io/badge/Tokens-600%2B-brightgreen?style=for-the-badge)](./logos)
  [![License](https://img.shields.io/badge/License-Community-blue?style=for-the-badge)](LICENSE)

  **The Official Community Repository for PulseChain Token Logos**

  <img src="./logos/0xA1077a294dDE1B09bB078844df40758a5D0f9a27.png" alt="wPLS" width="80" />
</div>

---

## 🌟 Overview

This repository serves as the centralized resource for **PulseChain** token logos, providing the PulseChain community with high-quality token images aggregated from DexScreener, PulseScan, and other DeFi platforms. Perfect for developers building on PulseChain, dApp creators, and community projects.

## 🎯 Purpose

- **🏛️ Centralized Asset Library**: One-stop source for all PulseChain token logos
- **💻 Developer Resource**: Easy integration for dApps, wallets, and DeFi tools
- **🤝 Community Driven**: Aggregated from multiple trusted sources across PulseChain
- **📏 Standardized Format**: Consistent PNG format for seamless integration

## 💎 Featured Tokens

<div align="center">
  <table>
    <tr>
      <td align="center">
        <img src="./logos/0xA1077a294dDE1B09bB078844df40758a5D0f9a27.png" width="60" /><br/>
        <b>wPLS</b>
      </td>
      <td align="center">
        <img src="./logos/0x2b591e99afE9f32eAA6214f7B7629768c40Eeb39.png" width="60" /><br/>
        <b>HEX</b>
      </td>
      <td align="center">
        <img src="./logos/0xA0b86991c6218b36c1d19D4a2e9Eb0cE3606eB48.png" width="60" /><br/>
        <b>USDC</b>
      </td>
      <td align="center">
        <img src="./logos/0xdAC17F958D2ee523a2206206994597C13D831ec7.png" width="60" /><br/>
        <b>USDT</b>
      </td>
    </tr>
  </table>
</div>

## 🚀 Usage

Token logos are stored in the `logos/` folder and named using the token's contract address:
```
logos/0xA1077a294dDE1B09bB078844df40758a5D0f9a27.png  # wPLS
```

Simply reference the token by its contract address to retrieve the corresponding logo.

### Integration Example

```javascript
// For web applications
const getTokenLogo = (contractAddress) => {
  return `https://github.com/proestever/Pulsechain-Token-Logos/raw/master/logos/${contractAddress}.png`;
};

// Example usage
const wPLSLogo = getTokenLogo('0xA1077a294dDE1B09bB078844df40758a5D0f9a27');
```

## 📤 How to Submit Missing Logos (No Coding Required!)

### Method 1: GitHub Web Interface (Easiest)

1. **🔍 Find Your Token's Contract Address**
   - Go to [PulseScan](https://scan.pulsechain.com)
   - Search for your token
   - Copy your token's full contract address (starts with 0x, should be 42 characters total)
   - Example: `0xA1077a294dDE1B09bB078844df40758a5D0f9a27`

2. **🎨 Prepare Your Logo**
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
     - Final name example: `0xA1077a294dDE1B09bB078844df40758a5D0f9a27.png`

3. **📁 Upload via GitHub**
   - **Fork the repository first**:
     - Click the "Fork" button at the top right of this repository
     - This creates your own copy of the repository
   - In YOUR forked repository:
     - Navigate to the `logos` folder
     - Click the "Add file" button → "Upload files"
     - Drag and drop your properly named PNG file
     - Scroll down to "Commit changes"
     - Add a commit message like: "Add [Your Token Name] logo"
     - Click "Commit changes"
   - **Create a Pull Request**:
     - Click "Contribute" → "Open pull request"
     - Or go to the original repository and click "New pull request"
     - Click "compare across forks"
     - Select your fork and branch
     - Click "Create pull request"
     - Add a title: "Add [Your Token Name] logo"
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

## 📋 Logo Requirements

- **Format**: PNG only
- **Size**: Minimum 256x256 pixels (512x512 preferred)
- **Quality**: Clear, high-resolution
- **Background**: Transparent preferred
- **File Name**: Must be the full contract address (e.g., `0xA1077a294dDE1B09bB078844df40758a5D0f9a27.png`)

## 🤝 Contributing

We welcome contributions from the PulseChain community! If you have token logos that are missing from this collection, please submit them using the methods above or create a pull request if you're familiar with Git.

## 🔗 Useful Links

- [PulseChain Official Website](https://pulsechain.com)
- [PulseScan Explorer](https://scan.pulsechain.com)
- [PulseX DEX](https://pulsex.com)
- [DexScreener PulseChain](https://dexscreener.com/pulsechain)

## 📜 License

These logos are aggregated from public sources for community use. Individual token logos remain the property of their respective projects.

---

<div align="center">
  <b>Built with 💜 for the PulseChain Community</b><br/>
  <img src="https://pulsechain.com/images/wordmark.png" alt="PulseChain" width="200" />
</div>