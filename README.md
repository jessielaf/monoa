# Monoa
Monoa is an assembler for modular monoliths. This can be done by creating a yaml that looks like this:

> This module is not usable in production!

```yaml
dest: modules
modules:
  - name: employees
    repo: git@github.com:jessielaf/effe
    version: master
  - name: shifts
    repo: git@github.com:jessielaf/effe
    version: master
```
