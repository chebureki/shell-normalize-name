# shell-normalize-name
## usage
```console
# if you are careful:
$ norm-name "Ugly File Name-1" "Another ugly file name2" ... "last ugly file name"

# if you are lazy, aka me:
$ norm-name *
```

## motivation
if you primarily use cli for file management, you probably have had to consult a psychiatrist.
All because of cli-unfriendly naming-conventions, made up by GUI users with their also precious text-box interfaces.
Jokes aside, you often want to have standardized naming-conventions for a more smooth experience.

A typical scenario:
```
cli-friendly-folder/
├─ some-script.sh
├─ my-cool-document.pdf
├─ cool-subfolder/
Messy Folder(terrible in Bash**) /
├─ new_file(1)
├─ new_file
Lässige Filme /
├─ My totally legally acquired Movie (2003 23 1) Hans Hürensohn.MP4
```
Different conventions, made by different people. A PIA for cli usage.

