## Code Radio Songs

Song List:

[Online Table](songs.md)

[Json](songs.json)

## Description

An incomplete list of the music played on https://coderadio.freecodecamp.org/.

## Notice

There might be duplicated IDs if Code Radio updated a song's info.

For example, if Code Radio updated a song's album info, then you will see this in `songs.json`:

```
[
    ...
    {
        "id": "48f039d5fdb546aca3a341223cf923e1",
        "title": "Song Name",
        "album": "Foo Album"
    },
    ...
    {
        "id": "48f039d5fdb546aca3a341223cf923e1",
        "title": "Song Name",
        "album": "Bar Album"    // Updated value
    }
    ...
]
```