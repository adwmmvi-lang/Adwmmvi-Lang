## Lab 01

- Name:Andrew Wooddell
- Email:wooddell.19@wright.edu

## Part 1 - GitHub Profile

1. [Adwmmvi-Lang's GitHub Profile](https://github.com/adwmmvi-lang/Adwmmvi-Lang)

## Part 2 - Research

| Windows | Linux / Mac | Action |
| ---     | ---         | ---    |
| help    | man         |    describes the different ways that powershell works and shows other types of help options     |
| Get-Location | pwd    |     Shows the current path to the file that you are using     |
| Get-ChildItem | ls    |     Shows all the files in that directory   |
| mkdir   | mkdir       |     Makes a directory   |
| Set-Location | cd     |     Sets location of the current directory  |
| New-Item | touch      |     creates a new file   |
| Move-Item | mv        |     moves a file    |
| Copy-Item | cp        |     makes a copy of the file    |
| Remove-Item | rm      |     delets the chosen file   |
| notepad.exe | vim     |     Opens the notebook application stored in the computer   |

## Part 3 - Command Line Navigation

My OS is:
- [x] Windows
- [] Linux
- [] Mac

My Command Line Shell is: Windows PowerShell

### Navigating My OS on the Command Line

1. Full / absolute path to your user's home directory: **C:\Users\Awood>**

2. Create a directory named `DirA`:  **PS C:\Users\Awood> mkdir**

**cmdlet mkdir at command pipeline position 1**

**Supply values for the following parameters:**

**Path[0]: DirA**

**Path[1]: Dir B**

3. Create a directory named `Dir B`: **Mentioned in question 2**

4. Go into `DirA`:PS C:\Users\Awood> **set-location '.\DirA\'**

5. Go into `Dir B` from `DirA`: **PS C:\Users\Awood\DirA> set-location '..\Dir B\'**

6. Return to your user's home directory: **PS C:\Users\Awood\Dir B> cd ..**
7. Create a file named `test.txt`: **PS C:\Users\Awood> new-item**

**cmdlet New-Item at command pipeline position 1**

**Supply values for the following parameters:**

**Path[0]: test.txt**

**Path[1]:**

8. Move the file named `test.txt` into `DirA`: **PS C:\Users\Awood> move-item test.txt DirA**
9. Contents of `test.txt`:
```
CEG 2350L Lab #1
```
10. Make a copy of `test.txt` named `copy.txt` in `DirA`: **PS C:\Users\Awood\DirA> copy-item test.txt copy.txt**
11. View the contents of `DirA`: **PS C:\Users\Awood\DirA> get-childitem**


    **Directory: C:\Users\Awood\DirA**


**Mode                 LastWriteTime         Length Name**

**----                 -------------         ------ ----**

**-a----         8/28/2025   7:42 PM              0 copy.txt**

**-a----         8/28/2025   7:42 PM              0 test.txt**

12. Make a copy of `test.txt` in `Dir B` named `fodder.txt`: **PS C:\Users\Awood\Dir B> copy-item test.txt 'fodder.txt'**
13. Delete / remove both `fodder.txt` AND `Dir B`: **PS C:\Users\Awood\Dir B> remove-item fodder.txt**

**PS C:\Users\Awood> remove-item '.\Dir B\'**

## Citations

To add citations, provide the site and a summary of what it assisted you with.  If generative AI was used, include which generative AI system was used and what prompt(s) you fed it. 
