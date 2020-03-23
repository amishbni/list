# list - simple tool to list stuff

## How to install?

* Clone the repository into `~/.list`

```bash
git clone https://github.com/amirashabani/list ~/.list
```

* Make it executable

```bash
chmod +x ~/.list/list
```

* Copy it to `/usr/local/bin`, so that the command is recognized by your terminal. Make sure to run it with `sudo`.
```bash
sudo cp ~/.list/list /usr/local/bin
```

## How to use?

* To list everything
```bash
list
```

* To only list directories
```bash
list dirs
```

* To only list files
```bash
list files
```

* To list hidden files and directories
```bash
list hidden
```

* To only list hidden directories
```bash
list hidden dirs
```

* To only list hidden files
``bash

list hidden files
```

Note that you can replace the words "hidden, files, and dirs" with their first letter.
