<!--
https://pypi.org/project/readme-generator/
https://pypi.org/project/python-readme-generator/
-->

[![](https://img.shields.io/badge/OS-Unix-blue.svg?longCache=True)]()
[![](https://img.shields.io/pypi/v/gist-delete.svg?maxAge=3600)](https://pypi.org/project/gist-delete/)
[![](https://img.shields.io/npm/v/gist-delete.svg?maxAge=3600)](https://www.npmjs.com/package/gist-delete)
[![Travis](https://api.travis-ci.org/looking-for-a-job/gist-delete.svg?branch=master)](https://travis-ci.org/looking-for-a-job/gist-delete/)

#### Installation
```bash
$ [sudo] npm i -g gist-delete
```
```bash
$ [sudo] pip install gist-delete
```

#### Config
```bash
$ export GITHUB_TOKEN="<GITHUB_TOKEN>"
```

#### Scripts usage
```bash
usage: gist-delete id ...
```

#### Examples
```bash
$ gist-id <id1> <id2>
```

delete orphaned gists
```bash
$ pip install gist-id gists-id
$ python -m gists_id | grep -v "$(find ~/git/gists -maxdepth 1 -exec gist-id {} \; 2> /dev/null)" | xargs gist-delete;:
```

<p align="center">
    <a href="https://pypi.org/project/python-readme-generator/">python-readme-generator</a>
</p>