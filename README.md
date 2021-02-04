# osu!/McOsu Beatmap Importer
This is a bash script created primarily for McOsu for the purpose of importing beatmaps. This allows easy usage of McOsu without having or using osu!.

# Usage
`osz` may be placed anywhere in your PATH where you can place user-created scripts.

`OSUDIR` must be set, for example, by putting the following in `~/.bashrc`:

```bash
export OSUDIR=$HOME/osudir
```

`osz <filename(s)>` will unpack one or more zip archives and move them into your `OSUDIR`'s `Song` directory, removing the original file. This can accept multiple files as input, so the following may be a common use case after downloading several beatmaps:

```bash
cd ~/Downloads
osz *.osz
```

After beatmaps have been unpacked, McOsu's song selection may be reloaded with F5.

