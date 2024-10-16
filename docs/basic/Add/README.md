# Git Adding

## - Add all file into repo
```bash
git add .
```


## Adds content from all *.txt files under **docs** directory and its subdirectories:
```bash
git add docs/\*.txt
```

## Add All Files of Multiple Extensions
```bash
git add *.js *.css *.html
```


## Add Files Recursively in All Subdirectories
```bash
git add '**'/*.js '**'/*.css '**'/*.html
```

## Add All Files of Certain Extensions Using Regex Patterns
```bash
git add '*.{js,css,html}'
git add '**/*.{js,css,html}'

```
## Add All Files with a Common Prefix or Extension
```bash
git add index.*
git add '**/*.{js,html}'

```

## Summary of Wildcards:
- `*.ext`: _Add all files with the .ext extension in the current directory._
- `**/*.ext`: _Add all files with the .ext extension recursively from all subdirectories._
- `'*.{ext1,ext2,ext3}`': _Add files with multiple extensions in the current directory._
- `'**/*.{ext1,ext2,ext3}`': _Add files with multiple extensions recursively from all subdirectories._