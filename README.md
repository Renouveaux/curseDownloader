# curseDownloader
download all mods for minecraft via Docker

Download and extract your favorite modpack from curse and extract contents.
Then, juste run the following
`docker run --rm -v <path/to/manifest>:/pack renouveaux/cursedownloader`

This will automatically download all mods on a minecraft folder beside your manifest.json.
