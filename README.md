# Missing libraries and a new start script to run Baldur's Gate: Enhanced Edition on linux

When you try to run Baldur's Gate EE from gog you might get an error like this `./BaldursGate: error while loading shared libraries: libssl.so.1.0.0: cannot open shared object file: No such file or directory`.

This repo contains needed libs in the proper version (1.0.0) and a start script `s.sh`.

You need to copy the content of this repo to the directory with the game like `~/Games/gog/baldurs-gate-enhanced-edition` and start the game with `./s.sh`.
