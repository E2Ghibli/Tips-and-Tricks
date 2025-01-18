# Tips-and-Tricks
All kind of tips and tricks around everything 

<details>
<summary>Windows 10/11</summary>

### Shortcuts

- `[Windows] + [A]`: The action center opens.
- `[Windows] + [E]`: Explorer opens.
- `[Windows] + [G]`: Enter the gaming menu to record your gameplay.
- `[Windows] + [H]`: Start voice input.
- `[Windows] + [I]`: Settings will open.
- `[Windows] + [N]`: Show notification center and calendar.
- `[Windows] + [R]`: Call up the "Run" dialog.
- `[Windows] + [V]`: View clipboard history.
- `[Windows] + [.]`: Call up the emoji menu.
- `[Windows] + [+]`: Start Magnifier.

- `[Windows] + [STRG] + [SHIFT] + [B]`: Reload graphics driver.

### CMD
  
- `winget upgrade --all`: Upgrade all Programs.
  
### Activator
  
- [MAS](https://github.com/massgravel/Microsoft-Activation-Scripts): A Windows and Office activator.
- [Winutil](https://github.com/ChrisTitusTech/winutil): This utility is a compilation of Windows tasks.

</details>

<details>
<summary>Sublime Text</summary>

### Shortcuts

- `[Command] + [D]`: Select a word.
- `[Command] + [Shift] + [D]`: Duplicate Current Line.
- `[Command] + [L]`: Select a line.
- `[Command] + [Shift] + [L]`: Delete Current Line.
- `[Command] + [A]`: Select the entire content within the document.
- `[Command] + [Shift] + [F]`: Cross-File Editing.
- `[Command] + [Shift] + [P]`: Command Palette.

### Settings

- Spell Checker: `Preferences > Settings – User` and add the following line `"spell_check": true`
- Auto Save on Focus Lost: `Preferences > Settings – User` and add the following line `"save_on_focus_lost": true`
</details>

<details>
<summary>Websites</summary>

- [trace.moe](https://trace.moe/): Trace back the scene from an anime screenshot.
- [SauceNAO](https://saucenao.com/): Reverse Image Search.
- [TinEye](https://tineye.com/): Reverse Image Search.
- [AlternativeTo](https://alternativeto.net/): Find better alternatives to the products.
- [opensourcealternative.to](https://www.opensourcealternative.to/): Find open source alternatives.
- [Trello](https://trello.com/): Project management tool.
- [Notion](https://www.notion.so/): Note taking and project management tool.
- [Simple Icons](https://simpleicons.org/): Free SVG icons for popular brands.
- [Carrd](https://carrd.co/): Build one page website free.
- [Namech_k](https://namechk.com/): Check for domain and usernames.
- [PDF DRIVE](https://www.pdfdrive.com/): Search engine for PDF files.
- [Smallpdf](https://smallpdf.com/): PDF tools.
- [cloudconvert](https://cloudconvert.com/): Convert any file type to any other file type.
- [removebg](https://www.remove.bg/de): Remove background of images.
- [BuiltWith](https://builtwith.com/): Find out what websites are Built With.
- [PREPOSTSEO](https://www.prepostseo.com/): Free online tools.
- [Resume Maker](https://www.resumemaker.online/): Create a professional resume in just minutes.
- [WolframAlpha](https://www.wolframalpha.com/): AI for Math, Science and Life questions.
</details>

<details>
<summary>AI's</summary>

- [ComfyUI](https://github.com/comfyanonymous/ComfyUI): A powerful and modular stable diffusion GUI and backend.
- [Midjourney](https://www.midjourney.com/home/?callbackUrl=%2Fapp%2F): Midjourney is an independent research lab exploring new mediums of thought and expanding the imaginative powers of the human species.
</details>

<details>
<summary>Pi-hole</summary>

### DNS Server

- IPV4 Quad9 (unfiltered, no DNSSEC)

### Adlist

01. https://raw.githubusercontent.com/StevenBlack/hosts/master/hosts
02. https://raw.githubusercontent.com/StevenBlack/hosts/master/alternates/fakenews-only/hosts
03. https://raw.githubusercontent.com/PolishFiltersTeam/KADhosts/master/KADhosts.txt
04. https://raw.githubusercontent.com/FadeMind/hosts.extras/master/add.Spam/hosts
05. https://v.firebog.net/hosts/static/w3kbl.txt
06. https://adaway.org/hosts.txt
07. https://v.firebog.net/hosts/AdguardDNS.txt
08. https://v.firebog.net/hosts/Admiral.txt
09. https://v.firebog.net/hosts/Easyprivacy.txt
11. https://v.firebog.net/hosts/Prigent-Ads.txt
12. https://raw.githubusercontent.com/anudeepND/blacklist/master/adservers.txt
13. https://v.firebog.net/hosts/Prigent-Malware.txt
14. http://s3.amazonaws.com/lists.disconnect.me/simple_ad.txt
15. https://pgl.yoyo.org/as/serverlist.php?hostformat=hosts;showintro=0&mimetype=plaintext
16. https://raw.githubusercontent.com/FadeMind/hosts.extras/refs/heads/master/UncheckyAds/hosts
17. https://raw.githubusercontent.com/bigdargon/hostsVN/refs/heads/master/hosts
18. https://raw.githubusercontent.com/DandelionSprout/adfilt/master/AdGuard%20Home%20Compilation%20List/AdGuardHomeCompilationList.txt
19. https://raw.githubusercontent.com/Perflyst/PiHoleBlocklist/master/SmartTV.txt
20. https://raw.githubusercontent.com/Perflyst/PiHoleBlocklist/master/regex.list
21. https://raw.githubusercontent.com/matomo-org/referrer-spam-blacklist/master/spammers.txt
22. https://raw.githubusercontent.com/FadeMind/hosts.extras/master/add.2o7Net/hosts

### Install

Hyperpixel4: https://github.com/pimoroni/hyperpixel4

PADD: https://github.com/pi-hole/PADD

### Raspi Config
sudo raspi-config
  1. System Options
  2. Boot / Auto Login
  3. B1 and B2

### Config
sudo nano /boot/firmware/config.txt
  1. dtparam=i2s=on
  2. dtoverlay=vc4-kms-dpi-hyperpixel4,rotate=270,disable-touch
     dtoverlay=vc4-kms-v3d

### Font
sudo dpkg-reconfigure console-setup
  1. UTF-8
  2. Guess optimal character set
  3. TerminusBold
  4. 10x20
</details>
