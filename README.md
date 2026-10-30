<div align="center">

# Cadenza

**Music at the edge of your desktop. Useful tools within reach.**

Rust · Windows · Keyboard first

</div>

Cadenza is my independent desktop software project: a compact audio player that grows into a workspace for listening, creating and exploring. I am building it while studying Management & Artificial Intelligence at LUISS, using AI-assisted development alongside hands-on design, testing and refinement.

## A small interface with room to explore

- **Listen:** local music libraries, online YouTube playback, favourites, editable queues, shuffle and track repeat.
- **Shape the sound:** equalisation, custom presets, a frequency explorer and a compact two-deck DJ workspace.
- **See the sound:** a live spectrum, smooth track navigation, PC-audio visualisation and optional microphone visualisation.
- **Stay in flow:** keyboard controls, desktop search, quick web access and compact panels that can be pinned or moved.
- **Keep useful tools close:** a calculator with conversions and plotting, a typing studio with local history, and audio recording.
- **Take a break:** keyboard-friendly games with persistent local progress.

The interface is designed around a simple idea: the controls you use often should be easy to reach, while deeper tools should stay out of the way until you need them.

## How I build

The application core and interface are written in Rust. Native Windows integration handles audio devices, media controls and desktop behaviour. Development focuses on readable interactions, responsive animation, bounded storage and preserving user data across updates.

AI is part of my development workflow. I use it to explore ideas, implement and review changes, investigate failures and build tests; the result still has to work in the actual application.

## Privacy and ownership

Listening preferences, typing history, recordings and game saves are stored locally. Online features use an explicit account connection. Distributable packages are prepared separately from personal music, account credentials and development data.

Dependency licences, component notices and asset credits are preserved with the project.

## Release status

This repository is private while the next combined release is being verified. Matching source, installer files, checksums and release notes will be added after the build and installation checks are complete.

A passing unit test is one part of verification. Native playback, save compatibility, interface behaviour and installation are checked separately; outstanding checks are not represented as passes.

---

Built by [Justeck](https://github.com/Justeck).
