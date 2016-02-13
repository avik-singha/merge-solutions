
```
merge-solutions.exe [/nonstop] [/fix] [/config solutionlist.txt] [/out merged.sln] [solution1.sln solution2.sln ...]

        /fix: Regenerates duplicate project guids and replaces them in corresponding project/solution files
              requires write-access to project and solution files

        /config solutionlist.txt: Takes list of new-line separated solution paths from solutionlist.txt file

        /out merged.sln: path to output solution file. Default is 'merged.sln'

        /nonstop: do not prompt for keypress if there were errors/warnings

        solution?.sln - list of solutions to be merged
```