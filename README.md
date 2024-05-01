CastleDB
========
<img src="./img/icon_hd.png" align=right>

_A structured database and level editor with a local web app to edit it._

### What's CastleDB?
CastleDB is used to input structured static data. Everything that is usually stored in XML or JSON files can be stored and modified with CastleDB instead. For instance, when you are making a game, you can have all of your items and monsters including their names, description, logic effects, etc. stored in CastleDB.

### Why the fork?
While the [original CastleDB repository](https://github.com/ncannasse/castle) is still maintained as a library, the editor is now legacy, as it has been merged with [HIDE](https://github.com/heapsio/hide).

The goal of this fork is to provide a stable standalone version of the CastleDB editor.

It is based on [Motion Twin's `multifile` branch](https://github.com/motion-twin/castle/tree/multifile), which saves data in multiple files instead of only one, making collaborative work easier.

### Download and use

1. Go to the **[Releases](https://github.com/Orso2p2n/castle-multifile/releases)** page and download the latest release.
2. Unzip in any folder.
3. Launch `cdb-multifile.exe`.

### Run and Debug using VSCode

1. Clone this repo.
2. Install [Haxe](https://haxe.org).
3. Run the command `haxelib install castle.hxml` at the root of the repository.
4. Install the [Debugger for NWjs](https://marketplace.visualstudio.com/items?itemName=ruakr.vsc-nwjs) extension.
5. Open the command palette (`Ctrl + Shift + P` by default) and run `NWjs Install`.
6. Debug using the `Launch NWjs` configuration.

### Build EXE

At the root of the repository, run:
- `cd bin`
- `npm run dist`

### More info
Original Website / documentation (might not be up to date): http://castledb.org
