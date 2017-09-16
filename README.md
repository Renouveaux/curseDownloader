# curseDownloader
download all mods for minecraft via Docker

Download and extract your favorite modpack from curse and extract contents.
Then, juste run the following
`docker run --rm -ti -v <path/to/manifest>:/pack renouveaux/cursedownloader`

eg : `docker run --rm -ti -v /tmp/wasterland:/pack renouveaux/cursedownloader`

This will automatically download all mods on a minecraft folder beside your manifest.json.
