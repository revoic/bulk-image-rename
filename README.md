# REVOIC Amazon Image Bulk Upload Rename Tool

This jupyter notebook renames all images within a folder based on a catalog file and a unqiue identifier within the filename.

Goal is to create image names which can be upload with Amazon's **bulk image upload** tool.

![Amazon bulk image upload tool](./amazon-bulk-image-upload.png?raw=true "Amazon bulk image upload tool")

## How to use it

1. Put all files in a separate folder below this script. The folder may contain subfolders.
2. Make sure the images contain a unique identifier (e.g. an SKU) which can be used to find the product identifier in an Excel file (e.g. the ASIN or EAN or GTIN)
3. Set the script's variables accordingly and define the **regex** how to find the pattern within the filename

The script bundles 1,000 images within one output folder and creates a ZIP file for each bundle of 1,000 images.

If you need help with your Amazon account contact us: https://www.revoic.com

## MIT License

Copyright 2022 Trutz Fries

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.