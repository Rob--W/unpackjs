## unpackjs

`browserify` takes a project and generates a single file.  
This tool, `unpackjs` does the opposite: It takes a list of files, and creates
a directory with separate modules for each file.

This has only been tested with browserify, but other bundlers such as RequireJS
or Webpack may be supported in the future if I need such a tool.

## Usage

```
$ npm install -g unpackjs
$ unpackjs path/to/file.js path/to/file2.js

# Now there are directories "path-to-file" and "path-to-file2" that contain
# the modules.
```

## Authors
Rob Wu <rob@robwu.nl> (https://robwu.nl)
