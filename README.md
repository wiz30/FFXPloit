
<img width="1500" height="532" alt="logo" src="https://github.com/user-attachments/assets/493f4b44-cf74-4c12-8d99-e5fd68fe31e3" />


<div align="center">
  <h1 color=red>FFXPloit</h1>
</div>

*archieved due to laziness of such brain storm features

Brief description:

An open-source forbidden <a href='https://ddnet.org/'>DDNet</a>-based (TeeWorlds) client made by **oka**. Basically, FFN + Exploits = FFXPloit

*FFN fork

<div align="left">
  <h2>Features</h2>
</div>

<h3>Auto-response configurable text via FFN tab in settings</h3>

Includes:

* Trigger text
* Response to the triggered text

<ins>How it works:</ins>

Someone sends a message, for example: "oka: hi". And your client responds with "<sender's name>: hi" (<sender's name> can be disabled).

1. Enter text you want your client to respond to in global chat
2. Enter response text that your client will respond with

Example:

![auto response](https://github.com/user-attachments/assets/febf36d9-7a3d-4112-8a26-0863ed18ab43)


<h3>Avoid freezes (may be buggy at specific circumstances)</h3>

Includes:

* Adjustable slider from 0.0 to 5.0 tiles
  
<ins>How it works:</ins>

You get pushed away from a freezing tile, the distance to get pushed from can be set via slider in settings.

1. Check the box saying "Enabled" under "Auto-Move Away from Freeze Tiles:"

Example:

![2025-07-28 01-08-25](https://github.com/user-attachments/assets/05c03545-0c9b-426a-bc92-10c1021aecfa)


<h3>Auto-shoot laser before entering freezing tile</h3>

Includes:

* Adjustable slider from 0.0 to 5.0 tiles

<ins>How it works:</ins>

You grab laser gun, you ram into the freezing tile, before entering the freezing tile you automatically shoot laser

1. Enable this feature via FFN tab in settings
2. Adjust distance in tiles you want to trigger laser by moving slider (0.0 tiles is totally fine, tested)

> Disable freeze-tiles avoidance, otherwise it will not work

Example:

![2025-07-28 01-14-42](https://github.com/user-attachments/assets/63467c2b-9c16-45c1-b98e-6d013add7e7a)

<h3>Version spoofing</h3>

Includes:

* Adjustable field from 0 to about 99999

<ins>How it works:</ins>

You enter a server with custom-set version

1. Slide the field to wanted version
2. Hit "enable"
3. Log into a server and ask someone to check your version (or if you're admin, use 'status' command in F2)

> ! Must reconnect after applying new version

<h3>Hide XPloit bar</h3>

Just press "insert"

---

<h3>Planned features:</h3>

1. Aimbot
2. Proxy toggle (will require your own proxy server, will think about it)
3. Name stealer
4. Raid
5. Features from FFN

You can submit your ideas in this repo by creating an issue with label "suggestion"

...

<h1>Installation</h1>

As soon as I will upload the source code

<h1>Build</h1>

As a regular DDNet build, do your steps

---

<h1>Pre-release changelog</h1>

1.1.1

[+] Version spoofing

1.2.0

[+] You can now hide XPloit bar by pressing "insert" button while in settings
