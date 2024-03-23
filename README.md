# safedav-tool

This tool is designed to provide a secure way to encrypt and decrypt files using the command line.

## Features

- **Encryption & Decryption**: safedav-tool allows you to encrypt files to keep them secure and decrypt them when needed.
- **Custom Prefix & Suffix**: Customize the naming of your encrypted and decrypted files with prefixes and suffixes.
- **Cross-Platform**: Works on Windows, Mac, and Linux.

## Getting Started

Before you begin, ensure you have downloaded the latest version of safedav-tool from the releases page.

### Installation

To install safedav-tool, download the appropriate version for your operating system and follow the installation instructions.

### Usage

To use safedav-tool, open your command line interface and navigate to the directory where safedav-tool is installed.

#### Parameters

- `--mode`: Set the operation mode (`encrypt` or `decrypt`). Default is `encrypt`.
- `--input`: Specify the path to the input folder.
- `--output`: Specify the path to the output folder.
- `--key`: Provide the encryption key.
- `--prefix`: Set the prefix for the filenames (used in both encryption and decryption modes).
- `--suffix`: Set the suffix for the filenames (used in both encryption and decryption modes).

#### Examples

Encrypting files:

```shell
safedav-tool --mode encrypt --input /path/to/input --output /path/to/output --key your-encryption-key --prefix secure_ --suffix _safe
```

Decrypting files:
```shell
safedav-tool --mode decrypt --input /path/to/input --output /path/to/output --key your-encryption-key --prefix secure_ --suffix _safe
```
