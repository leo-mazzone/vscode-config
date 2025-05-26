# README
A list of opinionated settings and configurations for VSCode.


## Extensions
Generate:

```bash
code --list-extensions > extensions.txt
```

Install:

``` bash
cat extensions.txt | xargs -n 1 code --install-extension
```

## Keybindings and settings
Generate:

```bash
cp "/Users/leo-mazzone/Library/Application Support/Code/User/keybindings.json" keybindings.json 
cp "/Users/leo-mazzone/Library/Application Support/Code/User/settings.json" settings.json 
```

Apply:

```bash
cp keybindings.json "/Users/leo-mazzone/Library/Application Support/Code/User/keybindings.json" 
cp settings.json "/Users/leo-mazzone/Library/Application Support/Code/User/settings.json" 
```