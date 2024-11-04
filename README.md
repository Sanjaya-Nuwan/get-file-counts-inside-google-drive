# File Count by Extension in Google Drive

This Python script counts the number of folders and files in a specified directory on Google Drive, categorized by file extensions. It is designed to run in a Google Colab environment and uses the `os` and `collections` libraries to traverse the directory structure.

## Features

- Counts the total number of folders and files.
- Reports the number of files for each file extension.
- Provides a breakdown of file counts by folder.

## Prerequisites

- A Google account with access to Google Drive.
- Basic understanding of Python and Jupyter notebooks (Google Colab).

## Setup

1. **Open Google Colab:**
   - Go to [Google Colab](https://colab.research.google.com/).

2. **Mount Google Drive:**
   - The script includes a command to mount your Google Drive, allowing the script to access files within it.

3. **Upload the Script:**
   - Copy the script into a new cell in a Google Colab notebook.

4. **Run the Script:**
   - Adjust the `base_directory` variable to point to the specific directory you want to analyze within your Google Drive.
   - Execute the cell to run the script.

## Usage

1. **Open Google Colab:**
   - Go to [Google Colab](https://colab.research.google.com/).

2. **Mount Google Drive:**
   - The script includes a command to mount your Google Drive, allowing the script to access files within it.

3. **Set Base Directory:**
   - Change the `base_directory` variable to specify the directory you want to analyze.
   ```python
   base_directory = '/content/drive/MyDrive'
   
4. **Call the count_files_by_extension function with the base directory**
   - The script will print the total number of folders, total files, file count by extension, and a detailed count by folder.
