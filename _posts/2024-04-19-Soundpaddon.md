---
title: Soundpaddon
date: 2024-04-19 00:00:00 +/-TTTT
categories: [Frontend, Backend]
tags: [Node, Svelte, SvelteKit, Electron]
pin: true
---

Soundpaddon is an application that adds a few features around Soundpad.

Try it out (it has a demo !) : [https://www.soundpaddon.app](https://www.soundpaddon.app){:target="_blank"}

![Soundpaddon's logo](/assets/img/posts/soundpaddon/logo.svg)

# What is Soundpad ?

[Soundpad](https://www.leppsoft.com/soundpad){:target="_blank"} is a program that allows you to play sounds through your microphone (or any audio input device). It is often used by streamers, roleplayers or gamers for various purposes.

# Why create Soundpaddon ?

While Soundpad is a great program, it lacks some features that could be useful for some users. Soundpaddon aims to fill this gap by providing a few additional features.

# Features

## Remote control

Soundpad exposes an API to control through IPC (with a named pipe). Soundpaddon uses this API to provide a web interface to control Soundpad remotely.

![Diagram of Soundpaddon's communication with Soundpad](/assets/img/posts/soundpaddon/diagram.svg)

The main purpose of this feature is to control Soundpad with a spartphone or tablet, but it can be used on any device on the same network with a web browser.

## Importing from YouTube

Soundpaddon allows you to import sounds from Youtube by pasting the URL of a video. Soundpaddon also provides a way to import only a segment of a video by specifying a start and end time.

This is useful to import only a part of a video, for example a sound effect or a music loop.

## Importing from Soundbanks and web pages

Soundpaddon can import sounds from Soundbanks (a collection of sounds) and extract audio files from web pages. This is useful to import a large number of sounds at once.

# Gallery

![Alt text](/assets/img/posts/soundpaddon/gallery1.png)

![Alt text](/assets/img/posts/soundpaddon/gallery2.png)

[You can try out the demo here](https://soundpaddon.app/panel?demo){:target="_blank"}

[Peruse the code here](https://github.com/Seblor/Soundpaddon){:target="_blank"}