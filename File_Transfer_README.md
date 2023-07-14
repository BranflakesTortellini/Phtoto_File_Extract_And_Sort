# File Transfer Script (File_Transfer_v_2.ipynb)

This script allows you to transfer files from a source directory to an output directory while providing various functionalities like removing duplicate files, verifying transferred files, moving remaining files to a "Possible Duplicates" directory, and removing empty directories.

## Prerequisites
- Python 3.x installed on your system
- Required Python packages: `os`, `shutil`, `tkinter`, `tqdm`, `datetime`, `logging`

## Setup
1. Ensure that you have Python 3.x installed on your system.
2. Save the script to a Jupyter Notebook file with the name `File_Transfer_v_2.ipynb`.

## Usage
1. Launch Jupyter Notebook.
2. Navigate to the directory where you saved the `File_Transfer_v_2.ipynb` file.
3. Open the notebook file.
4. Follow the instructions within the notebook to run the script.
5. The script will prompt you to select a search directory and an output directory using a file dialog.
6. After selecting the directories, the script will perform the following actions:
   - Transfer files from the search directory to the output directory.
   - Check for duplicate files in the output directory and remove them.
   - Save information about removed duplicate files to a text file named "removed_duplicates.txt" in the output directory.
   - Verify the transferred files in the output directory.
   - Move remaining files in the search directory to a subdirectory named "Possible Duplicates".
   - Remove empty directories in the search directory.
   - Display progress information, including the total files found, files transferred, duplicate files removed, and the runtime.
7. Once the process is complete, you can review the progress information in the notebook output or the `application.log` file.

## Note
- The script uses the Tkinter library to provide a file dialog for selecting directories.
- The `tqdm` library is used to display progress bars for the transfer and verification processes.
- Duplicate files are identified based on matching file names, sizes, and extensions.
- The script preserves the original directory structure while transferring files to the output directory.
- The script removes duplicate files from the output directory and saves information about the removed duplicates to a text file.
- Verification is performed on the transferred files to ensure their integrity.
- The script moves remaining files in the search directory to a subdirectory named "Possible Duplicates" and removes empty directories within the search directory.
- Detailed progress information, including the number of files found, transferred, and duplicate files removed, as well as the runtime, is logged to the `application.log` file.

## Example
1. Launch Jupyter Notebook and navigate to the directory where you saved the `File_Transfer_v_2.ipynb` file.
2. Open the notebook file.
3. Follow the instructions within the notebook to run the script.
4. The script will prompt you to select a search directory and an output directory using a file dialog.
5. The script will transfer files from the search directory to the output directory, remove duplicate files, verify the transferred files, move remaining files to the "Possible Duplicates" directory, and remove empty directories.
6. Progress information will be displayed in the notebook output or the `application.log` file.
7. Once the process is complete, review the progress information to ensure files were transferred, duplicates were removed, and empty directories were handled appropriately.

If you have any questions or need further assistance, please let me know!
