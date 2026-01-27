<img src="./assets/logo.png" style="width:700px">

This is just a bunch of scripts that range from daily usage (and fundamental 
part of my workflow) to scripts I use once everytime I config a new system.

**Current scripts:**

- `vpn_init`: script that identifies all of the vpn files with the following
    regex: `~/Downloads/*.protonvpn.tcp.ovpn`. And help me configure them all
    for at the same time **with the same password and user**, for easy use of
    `nmcli`.
- `ni`: "Name It" - converts a string into a clean title by lowercasing,
    replacing spaces with underscores, and removing special characters.
    Useful for generating file/project names.
- `ncur`: "Note Current" - sets the current directory as the default folder
    for new notes in Obsidian. Run it from any folder inside the vault and
    new Quick Capture notes will go there.
- `ytrss`: "YouTube RSS" - takes a YouTube channel ID and spits out the RSS
    feed URL. That's it. Useful for adding channels to your RSS reader.
