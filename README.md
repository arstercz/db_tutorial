# Let's Build a Simple Database

[View rendered tutorial](https://cstack.github.io/db_tutorial/) (with more details on what this is.)

## Notes to myself

Run site locally:
```
bundle exec jekyll serve
```

### Centos version

we can compile `db_centos.c` in centos system with the following command:
```
gcc -o db -std=gnu99 db_centos.c
```

_note_: only test in the following system 
```
centos 6.5 - gcc 4.4.7
centos 7.2 - gcc 4.8.5
```
