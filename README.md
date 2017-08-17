## chanFilter

Command line interface and python module for filtering 4chan posts.


### Installation

```
pip install chanFilter
```

Or install from source by cloning the repository and running as root

```
python setup.py install
```

### Command Line

```
Usage: chanFilter [OPTIONS]

  Tool to search BOARD for TEXT in the title or OP's post.

Options:
  -l, --list         List all boards (overrides other options)
  -b, --board TEXT   Board to search
  -t, --text TEXT    Text to search
  -i, --intelligent  Searches via keywords and not just the string you entered
  --help             Show this message and exit.
```
