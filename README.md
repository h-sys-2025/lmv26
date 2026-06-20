# lmv26
- Forked from: `https://github.com/hmZa-Sfyn/lmv-suite` 

- A lightweight, Baby Metasploit modular framework written in Go.  
Supports modules written in **Python 3** and **Bash**. (and Ruby too, but not stable)

### This is old, but worth it.
[official website](http://lmv-ng.vercel.app/)

## Features

- `Std(in/out) support`: Interactive command-line interface.
- `Easy boilerplate syntax`: Simple module creation (Python 3 / Bash).
- `Flexible argument passing`: Easy to use arguments. `(Named + W_Defaut_Value)`
- `No json`: YAML-based module metadata.
- `Variables declare/call`: Built-in environment variable support for arguments.
- `Live output`: Real-time execution with clear output.

## Setup

```sh
gh repo clone h-sys-2025/lmv26
cd ./lmv26

# Please read the: ./setup.sh file first to spot any issues. (I assure there are none)
chmod +x ./setup.sh

# JUst run it then.
./setup.sh

#
# - The script does these things:
#
# 1. go mod tidy
# 2. go build .
# 
# - downloads default 81 modules from archive repo.
#
# - sets up alises in ~/.zshrc OR/AND ~/.bashrc
#
```

## Getting started:

```sh
lmv -banner  # to show banner
```
[welcome](./media/intro.png)

### Or

```sh
./lanmanvan
```

or with custom modules path:

```sh
./lanmanvan -modules ./custom_modules
```

---

## Help
[help](./media/help1.png)
[search](./media/search1.png)

## Using Modules

### List Available Modules

[list modules](./media/list1.png)

### Get Module Information

[list modules](./media/info1.png)
[!](./media/!.png)

### Run a Module

[run a module](./media/run1.png)

Or use shorthand:

[run a module using var](./media/run2.png)

---
