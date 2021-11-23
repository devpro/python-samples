# Python samples

Sample of Python code.

## Local setup

### Virtual environment

* Connect to a Linux machine (WSL on Windows)
* Make sure `python3`, `python3-pip`, `python3-venv` are installed

```bash
# change to a Linux directory (not /mnt)
cd ~

# creates a virtual environment
python3 -m venv whatever

# switches to the environment
source whatever/bin/activate
```

## Usage

```bash
python3 src/helloworld/hello.py
```

## Conventions

* [Structuring Your Project](https://docs.python-guide.org/writing/structure/)
* [How to Write Beautiful Python Code With PEP 8](https://realpython.com/python-pep8/)
