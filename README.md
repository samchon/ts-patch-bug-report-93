Bug report for [nonara/ts-patch#93](https://github.com/nonara/ts-patch/issues/93).

No problem when running `tspc` command, but running through `ts-node` with `-C ts-patch` is not possible.

Of course, if I run `ts-patch install` command and just run `ts-node` without the `-C ts-patch` option, it works fine.