<div align="center">
<img src="assets/banner.svg" alt="Wali Lambert" width="100%">
</div>

---

I build small, finished things that people can open and use today. Some run
entirely on your own device with no account and no tracking. The rest talk to
a server only because the job needs one.

```text
$ cat ~/now
forsakeai      a free AI humanizer that runs in the browser
quiet-courier  a daily newspaper for Kindle and Kobo, launched October 2026
fullhearts     Minecraft modpacks that launch on the first try
schedule.az    booking platform for Baku's service businesses
tankobon       manga chapters to one .cbz per volume, for e-readers

$ echo $STACK
typescript · python · go · javascript · next.js · postgres · react-native
```

### Live

**[ForsakeAI](https://yatovoid.github.io/forsakeai/)** &nbsp;·&nbsp; TypeScript, Svelte, WebGPU
A free AI humanizer that runs in the browser. It marks the phrases that make
text read as machine-written, then rewrites it with a 4B model on your own
graphics card, or through your own API key. Every change is shown and can be
undone, and numbers, names and links are locked so the facts survive. On a
sample ad, a commercial detector went from 90% AI to 8%. No account, nothing
uploaded.
**[Try it](https://yatovoid.github.io/forsakeai/)** &nbsp;·&nbsp; [source](https://github.com/YatoVoid/forsakeai)

**[The Quiet Courier](https://quietcourier.com)** &nbsp;·&nbsp; Python, TypeScript, Next.js, Postgres
A daily newspaper for e-readers. Every morning at 5 a.m. local time it lands on
a Kindle or Kobo as one finished edition laid out like an early-1900s
broadsheet: local weather, world news in brief, long reads from The
Conversation and NASA, a page from a newspaper printed 100 years ago that day,
a serial novel chapter, puzzles and a poem. Then it ends. Licensed sources
only, no ads.
**[quietcourier.com](https://quietcourier.com)** &nbsp;·&nbsp; [sample edition](https://quietcourier.com/sample) &nbsp;·&nbsp; [source](https://github.com/YatoVoid/quiet-courier)

**[Full Hearts](https://fullhearts.app)** &nbsp;·&nbsp; TypeScript, Next.js
A Minecraft modpack builder. Pick mods and it resolves every dependency,
matches versions to your loader, and checks the set runs together against live
Modrinth and CurseForge data before exporting one `.mrpack`. New to mods, a
short quiz builds a set for you. No account needed.
**[fullhearts.app](https://fullhearts.app)** &nbsp;·&nbsp; [source](https://github.com/YatoVoid/FullHearts)

**[Schedule.az](https://schedule.az)** &nbsp;·&nbsp; TypeScript, Next.js, Postgres
A multi-tenant booking platform and directory for local service businesses:
barbershops, salons, spas, tutoring centers, gyms. Phone-OTP accounts, staff
calendars with time-off exceptions, SMS-confirmed bookings, and analytics
computed from what was actually charged, not what was listed. Live and taking
its first businesses.
**[schedule.az](https://schedule.az)** &nbsp;·&nbsp; [source](https://github.com/YatoVoid/schedule.az)

**[Tankobon](https://github.com/YatoVoid/manga-to-ereader)** &nbsp;·&nbsp; Python, Qt
Packs downloaded manga chapters into one ordered `.cbz` per volume, ready for
Kindle Comic Converter. Chapters a site left without a volume number are
placed in the right volume, and incomplete chapters are flagged before
anything is written. Desktop app and command line for Windows, macOS and
Linux, and on the AUR.
**[Download](https://github.com/YatoVoid/manga-to-ereader/releases/latest)** &nbsp;·&nbsp; `yay -S tankobon` &nbsp;·&nbsp; [source](https://github.com/YatoVoid/manga-to-ereader)

**[YatoVoid Music Box](https://yatovoid.github.io/yatovoid-music-box/)** &nbsp;·&nbsp; JavaScript, Web Audio
An 8-bit music editor in the browser. Notes go on a piano roll, each bar gets
a chord, and it plays back with NES-style square and triangle waves plus a
bass line and backing that follow the chords. Exports WAV that loops without a
gap, MIDI, or a song file to open again later.
**[Try it](https://yatovoid.github.io/yatovoid-music-box/)** &nbsp;·&nbsp; [source](https://github.com/YatoVoid/yatovoid-music-box)

**[Vitals Local](https://yatovoid.github.io/vitals-local/)** &nbsp;·&nbsp; JavaScript, no dependencies
Health reference and symptom triage in the browser. An adaptive question flow
picks whichever question narrows the causes most, over published decision
rules such as Wells, Alvarado, Ottawa and SNNOOP10. Red flags are hard rules no
score can override. 65 languages, translated on the device, nothing sent
anywhere.
**[Try it](https://yatovoid.github.io/vitals-local/)** &nbsp;·&nbsp; [source](https://github.com/YatoVoid/vitals-local)

**[Witch Atelier](https://yatovoid.github.io/witch-atelier/)** &nbsp;·&nbsp; JavaScript, no dependencies
A spell circle drawing tool in the style of Witch Hat Atelier. A freehand
stroke is read by its own shape rather than matched against one fixed template
per sign, and finished circles are checked against a full spellbook.
**[Try it](https://yatovoid.github.io/witch-atelier/)** &nbsp;·&nbsp; [source](https://github.com/YatoVoid/witch-atelier)

### Work

**[WhaleTale](https://whaletale.tech)** &nbsp;·&nbsp; website, English and Russian
The site for WhaleTale, a hardware company in Azerbaijan that builds
biometric, security, transport and infrastructure systems in-house, from PCB
design to deployment: automated border gates, ID terminals, connected city
buses.
**[whaletale.tech](https://whaletale.tech)**

**Client work** &nbsp;·&nbsp; [CRUNCH Burgers](https://yatovoid.github.io/crunch-burgers/), a website rebuild
for a Baku burger chain, in Azerbaijani, English and Russian.

### Run it yourself

**[YatoStream](https://github.com/YatoVoid/YatoStream)** &nbsp;·&nbsp; Go
A local anime and manga server: library scanning that tolerates messy folder
names, torrent search and direct streaming, AniList sync, manga reading, and
apps for desktop and mobile. Runs on your own machine.

**[Karaoke Queue](https://github.com/YatoVoid/karaoke-queue)** &nbsp;·&nbsp; JavaScript
A local network song request queue that replaces paid per-song karaoke
systems. Guests queue songs from a tablet, a second screen drives the venue's
speakers, and it all runs off one machine with no signup.

**[Pekko Fridge](https://github.com/YatoVoid/Pekko-Fridge)** &nbsp;·&nbsp; React Native
A private expiry tracker for food, medicine and cosmetics. Reads the printed
date with the camera on the device and reminds you before things go off.

**[TLP Battery Tuner](https://github.com/YatoVoid/tlp-battery-tuner)** &nbsp;·&nbsp; Shell
One command for sane battery settings on any Linux distribution. Also on
[Homebrew](https://github.com/YatoVoid/homebrew-tlp-battery-tuner).

**[Macro Tool](https://github.com/YatoVoid/Macro-Tool)** &nbsp;·&nbsp; Python
Macro recording and playback for Linux under X11.

### Reach me

```text
$ echo $EMAIL
wali.lambert1960@gmail.com
```
