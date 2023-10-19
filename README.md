# hello-aaingyunii_pr `0.3.2`

- The Python program I'm distributing for the first time

View at:

- https://pypi.org/project/hello-aaingyunii_pr

### INSTALL
`$ pip install hello-aaingyunii_pr`

### USE

```bash
$ hello-aaingyunii-pic



            ░░░░░░░░░░░░░░░░░░░░░░░░░░
            ░░░█▀▀▀░█▀▀█░░█▀▀░▀▀█░░█░░
            ░░░▀▀▀█░█░░█░░█▀▀░▄▀░░░▀░░
            ░░░▀▀▀▀░▀▀▀▀░░▀▀▀░▀▀▀░░▀░░
            ░░░░░░░░░░░░░░░░░░░░░░░░░░
            ⎛⎝(•‿•)⎠⎞⎛⎝(•‿•)⎠⎞⎛⎝(•‿•)⎠⎞⎛⎝(•‿•)⎠⎞

```

```bash
$ hello-aaingyunii-who

My name is aik

```

### DEV

```bash
$ git clone ...
$ cd hello-aaingyunii_pr
$ pdm venv create
$ source .venv/bin/activate
(hello-aaingyunii_pr-3.8) $ pdm install
```

### TEST

```bash
$ pdm add -dG test pytest pytest-cov
$ pytest
$ pytest -s
$ pytest --cov
```

### `pytest` 

- who.py
```python
def my_name():
    print("My name is aik")
```

- test_who.py
```python
from hello_aaingyunii_pr.who import my_name

def test_my_name():
    my_name()
```

### DEPLOY

```bash
$ pdm publish
```

### REF
- image to text : https://www.text-image.com/convert/ascii.html




