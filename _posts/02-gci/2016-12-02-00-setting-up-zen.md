---
layout: post-page
title: Setting up Zen Environment and Run CoderDojo
category: gci
image: coderdojo.jpeg
meta: Successfully did the task of setting up Zen Environment and run coderdojo locally
head_image: coderdojo_env.png
---

<div style="text-align: center;">
<img src="{{site.baseurl}}/img/{{page.head_image}}" width="400px" height="220px" />
</div>

My task was to set up the zen environment and run CodeDojo platform locally.
The task was simple and had clear instructions in the README.md file in their <a href="https://github.com/coderdojo/cp-local-development">github repository</a>.

Before setting up the environment it is required for you to have:
1. NodeJS
2. PostgreSQL
3. Grunt

Links on those are also provided on the README file.

Once you are done setting up you should be able to visit `localhost:8000` and have
CoderDojo running, just like the above picture. 

# Troubleshooting

After initializing, when I tried running `./localdev.js run zen`
I encountered an error:

```

events.js:160
     throw er; // Unhandled 'error' event
     ^

Error: spawn gulp ENOENT
   at exports._errnoException (util.js:1026:11)
   at Process.ChildProcess._handle.onexit (internal/child_process.js:193:32)
   at onErrorNT (internal/child_process.js:359:16)
   at _combinedTickCallback (internal/process/next_tick.js:74:11)
   at process._tickCallback (internal/process/next_tick.js:98:9)
   at Module.runMain (module.js:606:11)
   at run (bootstrap_node.js:394:7)
   at startup (bootstrap_node.js:149:9)
   at bootstrap_node.js:509:3

```

However through a few google search I found <a href="">this</a>, and trying some of its solution and managed to remove the error.

```
npm cache clean gulp-imagemin
rm -rf node_modules/gulp-imagemin
npm install gulp-imagemin

npm install -g gulp bower && npm install && bower install
```
