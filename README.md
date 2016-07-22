# Tag And Warp

Easily tag locations in deep space (directories) and easily warp (like the space drive) to them with a few keystrokes.

## Installation

Installation is quite straightforward. Depending on the shell you are using (bash or zsh), add the following line to .bashrc or .zsh respectively.

`source [path-to-repo]/.warpdrive`

## Usage

### tag

Tags the current directory with an optional tagname. If no tagname is specified it will take the name of the current directory.

```bash
warp [tagname]
```

### untag

Removes a tag from the taglisting.

```bash
untag [tagname]
```

This tagname is optional. If you are in a tagged directory it will automatically remove the directory from the list of tags.

### warp

```bash
warp [tagname]
```

### tags

Lists all tags.
