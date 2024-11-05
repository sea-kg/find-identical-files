# find-identical-files

Windows:
```
python3 -m pip install tk
```

## Pack to one exe

Required:
```
python3 -m pip install pyinstaller openpyxl
```

Make FindIdenticalFiles.exe
```
pyinstaller --onefile find_identical_files.py --name "FindIdenticalFiles" --clean --noconfirm
```

More info:

https://www.codeforests.com/2020/07/17/pack-python-program-into-exe-file/