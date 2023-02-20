# BeautyFiler
This mass-rename tool will make your filenames readable by renaming them according to the following rules:

1. Replace all dots (.) with space (file extension separator will not be affected): ugly.file.name.txt --> Ugly File Name.txt

2. If filename contains only one dash (-) and the dash has no spaces around, insert one space before and after ( - ). This is welcome when working with music tracks: artist-track title.mp3 --> Artist - Track Title.mp3

3. If filename has more then one dash, all dashes will be changed to spaces (ugly-looking-file.exe --> Ugly Looking File.exe)

4. Change all underscores (_) to spaces: ugly_file_title.doc --> Ugly File title.doc

5. When there is more than one space between words, delete one space until only one remains (can process max 3 spaces between words): ugly   file  name.txt --> Ugly File Name.txt

6. Capitalize every word: ugly file name.txt --> Ugly File Name.txt


Version 1.9 (headless mode) is for automation.
It runs only in the folder you put it in.
Its purpose is to be run periodically in the same folder (for example: Downloads folder).