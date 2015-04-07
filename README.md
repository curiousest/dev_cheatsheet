# dev_cheatsheet
## Table of Contents
- [Bash](#bash)
- [Git](#git)
- [Python](#python)


Bash
====

## My custom .env_setup

| command  | description                    |
|----------|--------------------------------|
| copy     | copies anything piped to it to the clipboard |

## Normal

| command  | description                    |
|----------|--------------------------------|
| ctrl + u          | Clear all BEFORE cursor |
| ctrl + k          | Clear all AFTER cursor |
| alt + <           | Move to the first line in the history |
| alt + >           | Move to the end of the input history, i.e., the line currently being entered |
| ~[TAB][TAB]       | List all users |
| $[TAB][TAB]       | List all system variables |
| @[TAB][TAB]       | List all entries in your /etc/hosts file |
    
# Kill a job

n = job number, to list jobs, run `jobs`

```bash
kill %n
```

Example:

```bash
kill %1
```

Git
====

## Reset hard to origin master
```bash
git fetch
git reset --hard origin/master
```

Python
====

## My custom .env_setup
