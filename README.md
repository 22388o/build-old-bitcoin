# Building Old Bitcoin Core Releases

Some docs for building old Bitcoin Core releases and using them on your modern computer.

Current as of March 2022

## Method

As shared libraries update, older releases won't run on modern OSes.
So we need to use the static binaries.
The easiest way to build the static binaries is to use the deterministic build system used to produce the releases in the first place.
For releases 0.21 and earlier, this is Gitian.
