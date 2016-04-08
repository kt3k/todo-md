# view-todo v1.1.0

> TODO.md viewer app.

# Install

    npm install -g view-todo

The above installs `view-todo` command globally.

## todo.conf.yml

Set up the config file `$HOME/.todo.conf.yml` like the following:

```yml
title: view-todo
path: /Users/kt3k/tmp/view-todo
note: todo management service
tags: todo, javascript
---
title: ledgerman
path: /Users/kt3k/tmp/ledgerman
note: A Cli tool for creating a general ledger from the journal.
tags: ledger, accounting, javascript
---
title: bulbo
path: /Users/kt3k/tmp/bulbo
note: Streaming static site generator, based on gulp
tags: javascript, statis site generator
```

Then you can run todo viewer server with the command:

    view-todo

The above starts the server at http://localhost:3000/site/

# Commands

## Starts the server

    view-todo

Example

    $ view-todo
    Using the config file: /Users/kt3k/.todo.conf.yml
    Server running at: http://localhost:3000/site

You can access http://localhost:3000/site and will see something like:

![ss](http://kt3k.github.io/view-todo/media/todo-ss.png)

## Init config (not yet implemented)

    view-todo init

## Edit config (not yet implemented)

    view-todo edit

# License

MIT
