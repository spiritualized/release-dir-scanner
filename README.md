# release-dir-scanner
Python module for detecting audio releases in a directory structure

## Installation
`pip install release-dir-scanner`

## Usage
```
from release_dir_scanner import get_release_dirs

for path in get_release_dirs("C:\\Music"):
    print(path)

```
