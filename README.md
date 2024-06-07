# Umbra Data Downloader

## Overview

This project provides a Python script to download `.tif` images and their corresponding `.json` metadata files from the public AWS S3 bucket `umbra-open-data-catalog`. This script leverages the AWS SDK for Python, `boto3`, to access and download files without requiring AWS credentials.

## Prerequisites

Before you begin, ensure you have the following:

1. **Python**: This script requires Python 3.6 or later. You can download and install Python from [python.org](https://www.python.org/downloads/).
2. **pip**: Python's package installer. It comes bundled with Python, but you can upgrade it by running:
    ```bash
    python -m pip install --upgrade pip
    ```
3. **AWS CLI**: Although not strictly necessary for running this script, it is useful for verifying access to the S3 bucket. You can install the AWS CLI from [here](https://aws.amazon.com/cli/).

## Installation

### Step 1: Install the AWS CLI (Optional but Recommended)

### Step 2: Install Python and pip

### Step 3: Install the boto3 Library

boto3 is the AWS SDK for Python, which allows Python developers to write software that makes use of Amazon services like S3 and EC2.

Install boto3 using pip:

```bash
pip install boto3
```

## Script Usage

### Step 1: Download the Script

### Step 2: Update the Script

Before running the script, update the local_download_path in the script to the desired local directory where you want the files to be downloaded.

### Step 3: Run the Script

This will start downloading all `.tif` and `.json` files from the S3 bucket to the specified local directory.

After running the script, navigate to the local directory you specified (e.g., C:\Users\misha\OneDrive\Desktop\umbra_data). You should see the downloaded `.tif` and `.json` files, organized in the same structure as they are in the S3 bucket.

## Support

If you encounter any issues or have questions, feel free to open an issue on the project repository or reach out for support.
