Maximize - Deobfuscate and beautify JavaScript code with source maps
=====================================================================

Maximize will deobfuscate and beautify minified code using
[source maps](http://www.html5rocks.com/en/tutorials/developertools/sourcemaps/).
Source
maps map compiled code back to the original code, including mangled to original
function and variable names. [JS Beautifier](http://jsbeautifier.org/) is used
under the hood for beautifying.

This program will fail if source maps are not provided and available. Use JS
Beautifier directly for beautifying code without transforming variable and
function names.

As an example, see the
[minified script](https://gist.github.com/txase/6043155#file-minified-script)
and the generated
[maximized script](https://gist.github.com/txase/6043177#file-maximized-script)
from http://dev.fontdragr.com.

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
