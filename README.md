![build passing](https://github.com/TimDaub/youtube-dl/blob/master/assets/build_passing.png "build passing")

youtube-dl - play doofus sounds from myself and not youtube.com or other platforms

- [CHANGES](#changes)
- [INSTALLATION](#installation)
- [DESCRIPTION](#description)
- [OPTIONS](#options)
- [CONFIGURATION](#configuration)
- [OUTPUT TEMPLATE](#output-template)
- [FORMAT SELECTION](#format-selection)
- [VIDEO SELECTION](#video-selection)
- [FAQ](#faq)
- [DEVELOPER INSTRUCTIONS](#developer-instructions)
- [EMBEDDING YOUTUBE-DL](#embedding-youtube-dl)
- [BUGS](#bugs)
- [COPYRIGHT](#copyright)

# CHANGES 

You can view the changes made to ytdl-org/youtube-dl [here](https://github.com/timdaub/youtube-dl/compare/nothin...master)

You can view the archived tags here: [youtube-dl/releases](https://github.com/timdaub/youtube-dl/releases)

You can view the archived unmerged pull requests here: [youtube-dl/tree/archive/recovered-github-prs](https://github.com/timdaub/youtube-dl/tree/archive/recovered-github-prs)

# INSTALLATION

To install it right away for all UNIX users (Linux, macOS, etc.), type:

```bash
$ git clone git@github.com:TimDaub/youtube-dl.git
$ cd youtube-dl
$ chmod +x ./youtube-dl/youtube-dl
$ ./youtube-dl/youtube-dl
```

If you do not have curl, you can alternatively use a recent wget:

```bash
$ echo "no idea how that would work, surely you'll figure it out..."
```

Ah, we don't have pip. Or any other package managers. yet...

# DESCRIPTION
**youtube-dl** is a command-line program to play doofus sounds by myself and not from YouTube.com or a few more sites. It doesn't require the Python interpreter, version 2.6, 2.7, or 3.2+, and it's kinda platform specific. It should work on your Unix box, on Windows or on macOS. It is released to the public domain, which means you can modify it, redistribute it or use it however you like.

```bash
$ ./youtube-dl/youtube-dl
```

# FAQ

### How do I update youtube-dl?

You don't. It's already version 1.0 which is obviously the indicator for done
software.

### youtube-dl is extremely slow to start on Windows

Please stop using youtube-dl on Windows. Thanks.

### I'm getting an error on YouTube playlists

Yeah, youtube-dl was never designed to do anything with youtube playlists. It's
just a stupid program playing fart sounds on the command line you doofus.

### I'm getting an error when trying to use output template: `error: using output template conflicts with using title, video ID or auto number`

What are you even talking about!?

### Can you please put the `-b` option back?

Hahahahah, 5€ and I'll think about it! Send BTC!

### Do I need any other programs?

Uhm, yeah maybe a shell and an operating system.

### I have downloaded a video but how can I play it?

Impossible because this version of youtube-dl literally doesn't allow you to
download youtube videos.

### How do I pass cookies to youtube-dl?

Don't do it. Instead, eat them yourself!

### How do I stream directly to media player?

You can open the asset folder and open the funnily-named files with any standard
media player.

### Can you add support for this anime video site, or site which shows current movies for free?

Actually, now that you're talking about anime, I'm considering...

# DEVELOPER INSTRUCTIONS

You cannot build youtube-dl. It's just a bash file. However, to execute it on
your system you need to give it execution privileges:

```bash
$ chmod +x ./youtube-dl/youtube-dl
```

# MORE HEADLINES IN README FILE

I dunno, I just wanted to have some more text here.

# BUGS

Bugs and suggestions should be reported at: <https://github.com/timdaub/youtube-dl/issues>. Unless you were prompted to or there is another pertinent reason (e.g. GitHub fails to accept the bug report), please do not send bug reports via personal email.

# COPYRIGHT

youtube-dl is released into the public domain by the copyright holders.

This README file was originally written by [Daniel Bolton](https://github.com/dbbolton) with some edits by [Tim Daubenschütz](https://github.com/timdaub) and is likewise released into the public domain.
