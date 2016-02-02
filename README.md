# nwjs-demos
to demo https://github.com/nwjs/nw.js/issues/4338
goto node_modules/hello_world , npm install, then execute nwjs at root
Here are the errors:
/ws/0.13.0-beta5/nwjs.app/Contents/MacOS/nwjs
[0202/211929:INFO:nw_package.cc(175)] /ws/0.13.0-beta5/nwjs.app/Contents/MacOS/nwjs .
dyld: lazy symbol binding failed: Symbol not found: __ZN2v87Isolate10GetCurrentEv
  Referenced from: /ws/node-addon-examples/1_hello_world/nwjs/node_modules/hello_world/build/Release/hello.node
  Expected in: dynamic lookup

dyld: Symbol not found: __ZN2v87Isolate10GetCurrentEv
  Referenced from: /ws/node-addon-examples/1_hello_world/nwjs/node_modules/hello_world/build/Release/hello.node
  Expected in: dynamic lookup
