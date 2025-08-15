# testdata

This repository contains test files in various formats for testing file converters, compressors, combiners, and other file processing tools.

## Available Test Files

The following test files are available, each named `test.{extension}`:

### Image Formats
- **test.arw** - Sony RAW image format
- **test.avif** - AV1 Image File Format
- **test.bmp** - Windows Bitmap image format
- **test.cr2** - Canon RAW version 2 image format
- **test.cr3** - Canon RAW version 3 image format
- **test.dng** - Adobe Digital Negative RAW format
- **test.gif** - Graphics Interchange Format
- **test.heic** - High Efficiency Image Container format
- **test.heif** - High Efficiency Image Format 
- **test.ico** - Windows Icon format
- **test.jfif** - JPEG File Interchange Format
- **test.jpeg** - JPEG image format
- **test.jpg** - JPEG image format (alternative extension)
- **test.png** - Portable Network Graphics format

### Document Formats
- **test.pdf** - Portable Document Format

### Data Formats
- **test.csv** - Comma-Separated Values format
- **test.json** - JavaScript Object Notation format

### Video/Media Formats
- **test.mkv** - Matroska Video format

Most image files contain a simple 100x100 pixel test pattern with basic shapes for validation purposes. RAW formats contain minimal valid headers. Data formats contain sample structured data. The PDF contains sample text and graphics suitable for testing PDF processing tools.

## Usage

These files can be used for:
- Testing file format detection
- Validating file converters
- Testing compression algorithms
- Verifying file combiners and splitters
- Format compatibility testing