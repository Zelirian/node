```bash
./configure --without-inspector # don't build the inspector 'cause it relies on newer APIs
./make -j4 # use 4 threads to build the node executable (on macOS it will be located under out/Release/node)
```
