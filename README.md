# template-cli

An [`mj`][mj] template to add a command line interface to a module. Depends
on the [khaos-node][khaos-node] template (wich will automatically be
installed when using `mj`).

## Usage

To create a new module based on this template, run:

```
mj create cli ./my-new-module
```

and answer the prompted questions.

This will

1. Clone the base template and this template mixin from github into the specified directory
2. Fill in the prompted answers
3. Initialize a git repository and make an initial commit
4. Run `npm install`


## License

Apache 2


[mj]: https://github.com/mongodb-js/mj
[template-node]: https://github.com/mongodb-js/khaos-node
