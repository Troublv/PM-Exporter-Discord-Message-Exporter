# Project status: active[?]

PM Exporter can be used to export message history from a Discord channel to a file. It works with direct messages, group messages, and server channels, and supports Discord's dialect of markdown as well as all other rich media features.

❔ If you have questions or issues, please refer to the wiki.

💬 If you want to chat, join my Discord server.

Terms of use[?]
By using this project or its source code, for any purpose and in any shape or form, you grant your implicit agreement to all the following statements:

You condemn Russia and its military aggression against Ukraine
You recognize that Russia is an occupant that unlawfully invaded a sovereign state
You support Ukraine's territorial integrity, including its claims over temporarily occupied territories of Crimea and Donbas
You reject false narratives perpetuated by Russian state propaganda
To learn more about the war and how you can help, click here. Glory to Ukraine! 🇺🇦

Download
This application comes in two flavors: graphical user interface (GUI) and command line interface (CLI). The following table lists all available download options:

Downloads	Supported OS
GUI	
🟢 Stable release (PM Exporter.zip)
🟠 CI build (PM Exporter.zip)
Windows 7 or higher
CLI	
🟢 Stable release (PM Exporter.CLI.zip
🟠 CI build (PM Exporter.CLI.zip)
🐋 Docker (tyrrrz/discordchatexporter)
📦 AUR (discord-chat-exporter-cli)
Windows 7 or higher
macOS 10.13 (High Sierra) or higher
Linux (multiple distros)
Note: PM Exporter AUR package is maintained by the community.

Warning: To run PM Exporter on macOS or Linux, you will need to additionally install .NET Runtime v6:

.NET Runtime v6 for macOS x64
.NET Runtime v6 for macOS Arm64
.NET Runtime v6 for Linux (find the correct download for your distro)
This is not required if you installed PM Exporter using a package manager, or if you plan to run PM Exporter via Docker.

Features
Graphical user interface (Windows)
Command line interface (Windows, Linux, macOS)
Authentication via both user and bot tokens
Multiple output formats: HTML (dark/light), TXT, CSV, JSON
Support for markdown, attachments, embeds, emoji, and other rich media features
File partitioning, date ranges, message filtering, and other export options
Self-contained exports that don't require internet
Screenshots
channel list rendered output
