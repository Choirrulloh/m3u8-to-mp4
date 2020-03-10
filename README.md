# m3u8-to-mp4

Download

## Example usage

### Normal mode

```sh
sh ./m3u8-to-mp4 "https://mnmedias.api.telequebec.tv/m3u8/29880.m3u8" ./some-random-vid.mp4
```

### Batch mode (NOT YET IMPLEMENTED)

Say you have a file like this (`./batch-input`)

```
vid1.mp4 < https://mnmedias.api.telequebec.tv/m3u8/29880.m3u8
vid2.mp4 < https://mnmedias.api.telequebec.tv/m3u8/29880.m3u8
```

And you wanted all those files to be downloaded, you'd use the script like this

```sh
sh ./m3u8-to-mp4 -b ./batch-input -o ./ouput
```

When the script is finished, the files `vid1.mp4` and `vid2.mp4` will be in the `output` directory