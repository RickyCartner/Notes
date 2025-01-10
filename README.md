# General notes I've collected

## GitHub Actions Status

[![Test Loop](https://github.com/RickyCartner/Notes/actions/workflows/test-loop2.yml/badge.svg?branch=development)](https://github.com/RickyCartner/Notes/actions/workflows/test-loop2.yml)

## Default **_READ ME_** file

```
install -v cicada.tct temp.txt
```

``` console
$ install -v cicada.tct temp.txt
```

```terminal
install -v cicada.tct temp.txt
[...]
hello
```

```sh
- name: Hello
  ansible.builtin.debug:
    msg: "Hello World"
```

``` py
def bubble_sort(items):
    for i in range(len(items)):
        for j in range(len(items) - 1 - i):
            if items[j] > items[j + 1]:
                items[j], items[j + 1] = items[j + 1], items[j]
```
