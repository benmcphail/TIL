# Simple/handy bash stuff

```
if [ $uptime -lt 0 -o $questions -lt 1 -o $slow -gt 10 ] ; then
    some code
fi

PWD="$(pwd)"
SOURCE="${BASH_SOURCE[0]}"
```
