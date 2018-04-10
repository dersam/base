Why so minimal?

This is for quick hacking around - it's the bare minimum. The less moving parts, the less things can go wrong.

Only has the following build processes, all via scripts defined in package.json.
* Copy static libraries into a public directory (because referring directly to node_modules in index.html feels wrong)
* Compile LESS (because writing CSS without a preprocessor is annoying, could be replaced with sass)
* Watch files and run commands on change (because waiting is the worst.)

Anything else should be thrown on as appropriate. Use yarn.
