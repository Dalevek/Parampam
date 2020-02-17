# Paperscript syntax
Setting paperscript syntax

## Instruction
1) Open 
```bash
...\Microsoft VS Code\resources\app\extensions\html\syntaxes
```
2) Edit 
```bash
html.tmLanguage.json
```
3) Replace:
```
x-javascript\n\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t  |
```
to:
```
paperscript\n\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t  | x-javascript\n\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t  |
```
4) Close file and relaunch VSCode