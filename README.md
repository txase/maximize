Maximize - Deobfuscate and beautify JavaScript code with source maps
=====================================================================

Maximize will deobfuscate and beautify minified code using source maps. Source
maps map compiled code back to the original code, including mangled to original
function and variable names. JS Beautifier is used under the hood for
beautifying.

This program will fail if source maps are not provided and available. Use JS
Beautifier directly for beautifying code without transforming variable and
function names.

```
usage: maximize.js [-h] [-b BEAUTIFY_OPTS] url

Deobfuscate and beautify JavaScript code with source maps

Positional arguments:
  url                   URL of javascript to maximize

Optional arguments:
  -h, --help            Show this help message and exit.
  -b BEAUTIFY_OPTS, --beautify-opts BEAUTIFY_OPTS
                        JS Beautifier options in JSON format
```
