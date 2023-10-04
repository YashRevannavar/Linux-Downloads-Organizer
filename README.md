# Linux-Downloads-Organizer

This is a simple but useful Bash script that organizes files in the Downloads directory into subdirectories based on their file types.

## Usage

1. Clone the repository or download the [downloads.sh](/Linix-downloads-organizer/downloads.sh) file.
2. Open a terminal and navigate to the directory containing the [downloads.sh](/Linix-downloads-organizer/downloads.sh) file.
3. Run the script using the command.

```bash
bash ./downloads.sh
```

The script will run continuously, checking for new files in the Downloads directory every 5 seconds. It will create subdirectories for different file types and move files to the appropriate subdirectory.

## Supported File Types

The script currently supports the following file types:

- Music files (.mp3, .wav)
- Image files (.jpg, .png, .jpeg, .gif)
- Video files (.mp4, .mov)
- PDF files (.pdf)
- Archive files (.zip, .tar, .tar.gz, .deb)
- Document files (.csv, .ods, .xlsx, .txt, .docx, .doc)
- Python files (.py, .ipynb, .db)
- Other files (any file that doesn't match the above file types)

## Customization

You can customize the script to add support for additional file types or change the subdirectory names. Simply edit the [downloads.sh](/Linix-downloads-organizer/downloads.sh) file and modify the if statements accordingly.

## License

This project is licensed under the MIT License. See the [LICENSE](/Linix-downloads-organizer/LICENSE.md) file for details.
