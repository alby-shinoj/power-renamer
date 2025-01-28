# power-renamer
rename both files and directories in the given directory
------------------------------------------------------------------------------------------------------
How the Program Works:
Input Directory: The user provides the directory path.

Input Old Word: The user specifies the word to be replaced.

Input New Word: The user specifies the new word to replace the old word.

Recursive Traversal: The program uses os.walk() to traverse the directory and its subdirectories.

Renaming Files and Directories:

Files are renamed first.

Directories are renamed afterward (to avoid conflicts with subdirectory paths).

Validation: The program checks if the directory exists before proceeding.

------------------------------------------------------------------------------------------------------

C:/my_documents/
├── report_2021.docx
├── report_2022.docx
├── summary_2021.txt
├── old_data/
│   ├── data_2021.csv
│   └── backup_2021.zip
└── archive_2021/
    └── notes_2021.txt
