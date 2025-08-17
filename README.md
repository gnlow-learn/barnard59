# barnard59

## failed to run
```sh
deno run -A npm:barnard59/bin/barnard59.js run main.ttl --pipeline http://example.org/pipeline/utc
```
```
Error: The argument 'filename' must be a file URL object, file URL string, or absolute path string. Received undefined/
at Module.createRequire (node:module:862:13)
at desugar (file:///C:/Users/User/AppData/Local/deno/npm/registry.npmjs.org/barnard59/5.1.1/lib/pipeline.js:50:26)
at eventLoopTick (ext:core/01_core.js:179:7)
at async parse (file:///C:/Users/User/AppData/Local/deno/npm/registry.npmjs.org/barnard59/5.1.1/lib/pipeline.js:116:28)
at async Command.<anonymous> (file:///C:/Users/User/AppData/Local/deno/npm/registry.npmjs.org/barnard59/5.1.1/lib/cli.js:46:31)     
at async Command.parseAsync (file:///C:/Users/User/AppData/Local/deno/npm/registry.npmjs.org/commander/11.1.0/lib/command.js:936:5) 
at async run (file:///C:/Users/User/AppData/Local/deno/npm/registry.npmjs.org/barnard59/5.1.1/lib/cli.js:70:9)
at async file:///C:/Users/User/AppData/Local/deno/npm/registry.npmjs.org/barnard59/5.1.1/bin/barnard59.js:100:3
```
