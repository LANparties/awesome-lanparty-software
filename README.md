# Awesome LAN Party Software

An awesome list with awesome software for awesome LAN parties and their organizers.

## How to get something on this list:

Please create a pull request via GitHub.
If you are not sure where to put something, open an issue instead ;)

## Software

### LAN Party Management

- [DOTLAN Intranet](http://intranet.dotlan.net/) – "das komplette Intranetsystem für die Ausrichtung einer Lanparty"
- [LANSuite](https://lansuite.github.io/lansuite/) – "A Content Management System designed especially for the needs of LAN-Parties"
- [LANager](https://github.com/zeropingheroes/lanager) – "LAN party management web application"
- [BYCEPS](https://byceps.nwsnet.de/) – "A tool to prepare and operate LAN parties (even under different brands), big (1,000+ attendees) and small, both online on the Internet and locally as an intranet system, for both organizers and attendees"
- [LanHUB](https://LanHUB.net) – LAN Event management system focused on player engagement and easy registration
- [KRRU LAN-Party Management System](https://github.com/KRRUg/KLMS) - CMS (Content management system) for LAN-Parties. Everything you need to present and manage your event in a modern design.
- [Lan2Play's Eventula Event Manager](https://github.com/Lan2Play/eventula-manager) – currently updated fork of Eventula Event Manager with an extended featureset
- [LanSurfer Intranet](https://github.com/TcT2k/lansurfer_intranet) – "LanSurfer was a european portal for organizing LAN parties available around the Year 2000. This is the the ancient PHP intranet component that was available for LAN parties." `historical`
- [LANshock](https://github.com/bkonetzny/LANshock) – `historical`
- [Lansite](https://github.com/tannerkrewson/lansite) – "A web app for LAN parties designed to be a simple, central information hub for all attendees"
- [LAN](https://github.com/mfairchild365/lan) – "Guest management/communication application for LANs (LAN parties)"

### Server Management

- [ansible-lanparty](https://github.com/ti-mo/ansible-lanparty) – "Collection of integrated Ansible roles used to run LAN events"
- [puppet-lanserver](https://github.com/pseiler/puppet-lanserver) – "Collection of several lanservices running in a puppet context"

### Gameserver Management

- [LinuxGSM](https://linuxgsm.com/) – The command-line tool for quick, simple deployment and management of Linux dedicated game servers.
- [srcds_exporter (python)](https://github.com/991jo/srcds_exporter) – A stats exporter for prometheus that supports most of the SRCDS based gameservers.
- [srcds_exporter (golang)](https://github.com/galexrt/srcds_exporter) – A stats exporter for prometheus written in Go and tested with Garry's Mod.
- [get5](https://github.com/splewis/get5) – CS:GO Sourcemod plugin for competitive matches/scrims.
- [eBot](https://github.com/deStrO/eBot-CSGO) – CSGO Server Bot for easy match creation (might be outdated).
- [TMT](https://github.com/JensForstmann/tmt2) – A tool to supervise/manage Counter-Strike 2 matches.
- [srcdstop](https://github.com/991jo/srcdstop) – A CLI tool that shows how many people are on your SRCDS servers.
- [gsltctrl_minimal](https://github.com/991jo/gsltctrl_minimal) – A little script to manage GSLT tokens.
- [srcds-perfmon](https://github.com/OpenSourceLAN/srcds-perfmon) – A little utility to track the performance of a SRCDS server.
- [kubernetes-lanparty](https://github.com/OpenSourceLAN/kubernetes-lanparty/)  How to put all of your game servers into Kubernetes.
- [GameAdminHelper](https://github.com/DavidKMartel/GameAdminHelper) – "Helps manage game servers. Provide a menu for most common game admin tasks. Designed primarily for LAN parties."
- [LAN game scanner](https://github.com/991jo/lan-game-scanner)
- [Pterodactyl Panel](https://github.com/pterodactyl/panel) – "Pterodactyl is the open-source game server management panel built with PHP7, Nodejs, and Go. Designed with security in mind, Pterodactyl runs all game servers in isolated Docker containers while exposing a beautiful and intuitive UI to administrators and users."
- [Cloud Pterodactyl wings (CloudLAN Tools)](https://github.com/cloudlan-tools/cloudlan-tools) - Automatically deploy and manage cloud-based Pterodactyl wings with the use of Terraform or OpenTofu.
- [gameserver_webinterface](https://github.com/amshove/gameserver_webinterface) – "Webinterface für LAN-Partys zum einfachen Starten/Stoppen/Verwalten von Gameservern."
- [Wilfred](https://github.com/wilfred-dev/wilfred) – "Wilfred is a command-line interface for running and managing game servers locally. It uses Docker to run game servers in containers, which means they are completely separated. Wilfred can run any game that can run in Docker."
- [standalone-rcon-client](https://github.com/Egosar93/standalone-rcon-client) - "The Standalone RCON Client is a web-based tool for securely sending RCON commands to CS2 servers."

### Gameserver Configs

- [Archived ESL Configs](https://github.com/lan-dot-party/ESL-Configs)
- [Generic Docker game servers](https://github.com/OpenSourceLAN/gameservers-docker)

### Switch Configuration Tools

- [procurve_conf](https://github.com/991jo/procurve-conf) – A little script to put configs on HP ProCurve switches.

### File Sharing

- [D-LAN](https://www.d-lan.net/) – A free LAN distributed file sharing software.

### Network-related software

- [Service Discovery Helper](https://github.com/OpenSourceLAN/service-discovery-helper) – A program that forwards (some) broadcast traffic to other networks.
- [bcast-bridge](https://git.kopf-tisch.de/razzor/bcast-bridge) – A PHP script that generates iptables rules that forward broadcast traffic to other networks. Used at NorthCon and LANresort.
- [gamebridge](https://github.com/netwarlan/gamebridge) - Gamebridge allows you to carve up your LAN party network into many VLANs. Usually, this is a no-no for LAN parties due to the broadcasts needed to find local LAN game servers. Gamebridge rebroadcasts those game server finding beacons across many VLANs without passing anything else (ARP, BPDU, other non-game server broadcasts, etc.) using Linux ebtables. Very simple to set up and deploy. Created by [NETWAR](https://www.netwar.org)
- [QStat](https://github.com/multiplay/qstat) – "A command-line program that displays information about Internet game servers."
- [GrokStat](https://github.com/vorot93/grokstat) – "Fast game server query tool. Retrieves information about game servers. Inspired by QStat."
- [Discord Gameserver Notifier](https://github.com/lan-dot-party/Discord-Gameserver-Notifier) - Software so search local network of Gameserver and send Webhook into Discord Channel on new findings

### Caching

- [lancache](https://github.com/bntjah/lancache)
- [LanCache.net](https://lancache.net/)
- [lancache-autofill](https://github.com/zeropingheroes/lancache-autofill) – A script to fill a lan caching server
- [steam-lancache-prefill](https://github.com/tpill90/steam-lancache-prefill) – A self-contained, portable alternative to lancache-autofill with more features for steam games
- [battlenet-lancache-prefill](https://github.com/tpill90/battlenet-lancache-prefill) – A self-contained, portable alternative to lancache-autofill with more features for battlenet games
- [origin-docker](https://github.com/OpenSourceLAN/origin-docker) – Single docker image that will serves most major CDNs

### Monitoring

- [CheckMK](https://checkmk.com) – Free Monitoring System that can monitor almost everything and if a check is missing, write you own simple check.
- [checkmk-RCONserver](https://github.com/Hornochs/checkmk-RCONserver) – A local check for CheckMK to monitor GoldSrc Games (CS 1.6, Ricochet etc) and Source Games (CS:GO etc.).
- [Uptime-Kuma](https://github.com/louislam/uptime-kuma) - Easy to host monitoring solution with a variety of checks from simple pings over TCP checks to gameserver queries. Native installation and Docker deployment solution are available.

### Uncategorized

- [reboot-lan](https://github.com/Fohdeesha/reboot-lan) – "lanning + Infra for reBOOT LAN Party"
- [Eventula Mapper](https://eventula.com) – Event Mapping API
