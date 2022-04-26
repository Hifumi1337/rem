# Rem (Really Epic & Makeable) 

Rem is a terminal code editor I created as an alternative to Vim or Nano (or the many other terminal editors). I will eventually add more features and improve the codebase, but for now, it works pretty well.

## Usage

How to create an executable:
```bash
make
```

Available Commands:
```
Ctrl-X (^X) | Exits the Rem editor
Ctrl-Q (^Q) | Search (Query) for specific characters or strings
Ctrl-S (^S) | Save file contents
```

If you don't want to get your hands dirty with a bunch of commands, there's an installation script called `install.sh`:
```bash
# Only required if the file doesn't have executable permissions
chmod +x install.sh

./install.sh
```

Once the project is compiled, run the following command to set an alias on your local system:
```bash
# Example if using the build script
alias rem="/opt/rem/rem"
```
or you can just run `rem.sh` to run the editor, if you don't want to go through the trouble of setting up a new alias or variable.
```bash
# Only required if the file doesn't have executable permissions
chmod +x rem.sh

./rem.sh
```

## Example
```bash
# Creates a file called file.py. You can also open existing files the same way!
./rem file.py
```

### Mini FAQ
> Q. Will there be any actual releases for this project or a project website?
>> A. Yes! I have a domain ready for the website, but need to build it. As for the release, a "real" release will be created once I am happy with the project.