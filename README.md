# osu-collection-exporter

Exports osu! collections into a list of maps and links to beatmaps. All operations are performed locally within your browser and is never uploaded anywhere. It avoids making calls to the osu! API by using the osu!.db beatmap cache as its source of beatmap data.

NOTE: The FileReader API has a file size limit that varies between browsers (For instance: 231 MB on Chrome) so be wary of large osu!.db files

[Try it here!](https://jaasonw.github.io/osu-collection-exporter/)

# Dependencies

None! This uses vanilla javascript with the FileReader API and Dataview. However, a lot of the code is ported from [osu-db-tools](https://github.com/jaasonw/osu-db-tools) to javascript.

# Issues/Contributing

This project is a heavilly work in progress but if you ever find any issues, feel free to shoot me an issue, pull request, or a message on Discord: jasonw#2463 or on osu: jasonw
