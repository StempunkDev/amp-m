# amp-m

> Advanced Music Playlist Manager

@todo: add pipeline/package status tags

## Features

- manage your playlists across different proviers
- @todo: expand

## Demo

@todo: insert preview cmd-replay (/ui video once implemented)

## Getting started

### Installation and invocation

| package manager | how to use                                       |
| --------------- | ------------------------------------------------ |
| nix             | `nix run github:StempunkDev/amp-m -- --args...`  |
| apt             | @todo: provide infrastructure? `amp-m --args...` |
| windows?        | @todo: @StempunkDev        `amp-m.exe --args...` |

### Usage

#### Common usecases

```bash
# referencing a playlist
amp-m --playlist ...

# sorting a playlist
amp-m --sort ...

echo @todo: write out actual usage here
```

#### Less common usecases

- @todo: document

#### automation

- @todo: describe how to automate (eg. keep in sync from a->b)

### Building from source

```bash

git clone git@github.com:StempunkDev/amp-m.git
cd amp-m

# if you have nix installed
nix build . # to build into ./result
nix run . -- --args... # to execute a build in place

# non-nix:
npm run init # installs all dependencies 
npm run build # runs the full build pipeline
# this will build into ./dist

# run the build with:
./dist/app/amp-m --args...

# you can copy the executable anywhere, it's dependency-free
```

### Contributors

- @kittencoder
- @StempunkDev

