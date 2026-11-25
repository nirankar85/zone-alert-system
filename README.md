GitHub's browser uploader accepts only about 100 files at a time, and this project has 173 files.
So the files are split into three folders:

  UPLOAD_1_of_3   (47 files)
  UPLOAD_2_of_3   (69 files)
  UPLOAD_3_of_3   (57 files)

For EACH folder, one at a time, in this order:
 1. Open the folder. Select everything INSIDE it (Ctrl+A on Windows, Cmd+A on Mac).
    Do not drag the UPLOAD folder itself, only the things inside it.
 2. On your GitHub repository page click: Add file -> Upload files.
 3. Drag the selected items onto the page. Wait until all files show up in the list.
 4. Click Commit changes. Then do the next folder.

After all three folders, add the build file by hand (GitHub cannot upload folders whose name starts with a dot):
 - Add file -> Create new file
 - In the name box type exactly:  .github/workflows/android.yml
 - Open SETUP/android.yml from UPLOAD_1_of_3, copy all of it, paste it in the editor, click Commit changes.
