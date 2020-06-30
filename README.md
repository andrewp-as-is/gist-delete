<!--
https://readme42.com
-->



[![](https://img.shields.io/badge/OS-Unix-blue.svg?longCache=True)]()
[![](https://img.shields.io/pypi/v/gist-delete.svg?maxAge=3600)](https://pypi.org/project/gist-delete/)
[![](https://img.shields.io/npm/v/gist-delete.svg?maxAge=3600)](https://www.npmjs.com/package/gist-delete)[![](https://img.shields.io/badge/License-Unlicense-blue.svg?longCache=True)](https://unlicense.org/)
[![](https://github.com/andrewp-as-is/gist-delete/workflows/tests42/badge.svg)](https://github.com/andrewp-as-is/gist-delete/actions)

### Installation
```bash
$ [sudo] pip install gist-delete
```

```bash
$ [sudo] npm i -g gist-delete
```

#### Config
```bash
$ export GITHUB_TOKEN="<GITHUB_TOKEN>"
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
    <a href="https://readme42.com/">readme42.com</a>
</p>