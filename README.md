# Plagarism-Checker

This Python script provides a simple plagiarism checker based on the Levenshtein distance algorithm. It offers three options for plagiarism checking:

1. Compare Folder with Masterfile:
   - Enter a folder path containing text files.
   - Specify the masterfile (reference) path.
   - Set the percentage of allowed plagiarism.
   - The script compares each file in the folder with the masterfile and identifies plagiarized files.

2. Check Plagiarism in Two Files:
   - Enter paths for two text files.
   - Set the percentage of allowed plagiarism.
   - The script compares the content of the two files and determines the similarity.

3. Check Plagiarism in All Files in a Folder:
   - Enter a folder path containing text files.
   - Set the percentage of allowed plagiarism.
   - The script compares all pairs of files within the folder and identifies plagiarized documents.

## Usage

1. Run the script in a Python environment.
2. Choose the desired option (1, 2, or 3) for plagiarism checking.
3. Follow the prompts to input necessary information such as file paths and plagiarism threshold.

## Requirements
- Python 3.x
- NumPy library

## Example Usage:

### Folder Comparison
Enter 1 for comparing folder with masterfile

Enter the percentage of plagiarism allowed

Enter the path of the folder to scan:
/path/to/folder

Enter the masterfile path (not in the same folder):
/path/to/masterfile.txt

### Two Files Comparison
Enter 2 to check for plagiarism in two files

Enter the percentage of plagiarism allowed

Enter the path of the first file to scan:
/path/to/file1.txt

Enter the path of the second file to scan:
/path/to/file2.txt

### Folder-wise Comparison
Enter 3 to check for plagiarism in all files in folder

Enter the percentage of plagiarism allowed

Enter the path of the folder to scan:
/path/to/folder
