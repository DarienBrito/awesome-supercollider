# Awesome SuperCollider[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

![chaos](chaos-algo.png "chaos")

> A curated list of SuperCollider stuff

# Contents

<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->


- [Learning resources](#learning-resources)
  - [Written tutorials](#written-tutorials)
  - [Videos](#videos)
  - [Books](#books)
  - [Research papers](#research-papers)
  - [Others](#others)
- [Quarks and extensions](#quarks-and-extensions)
  - [Live coding](#live-coding)
  - [Controllers](#controllers)
  - [Network](#network)
  - [Patterns](#patterns)
  - [Maths](#maths)
  - [Immersive audio](#immersive-audio)
  - [FX](#fx)
  - [Synthesis](#synthesis)
  - [GUI](#gui)
- [Physical/embedded computing](#physicalembedded-computing)
- [Clients](#clients)
  - [Language clients](#language-clients)
  - [Livecode interfaces](#livecode-interfaces)
- [IDE alternatives](#ide-alternatives)
- [Forums](#forums)
- [Tools](#tools)
- [Contribute](#contribute)
- [License](#license)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

## Learning resources

### Written tutorials
- [A gentle introduction to SuperCollider](https://ccrma.stanford.edu/~ruviaro/texts/A_Gentle_Introduction_To_SuperCollider.pdf) –  Introduction to SC by Stanford's CCRMA
- [Thor Magnussons Scoring Sound](https://leanpub.com/ScoringSound) - Cookbook containing synthesis recipes among other things
- [howto_co34pt_liveCode](https://theseanco.github.io/howto_co34pt_liveCode/) - Livecoding tutorial
- [Nick Collins' SuperCollider tutorial](http://composerprogrammer.com/teaching/supercollider/sctutorial/tutorial.html) - Course material for a 12 week course on SuperCollider 
- [udk00-Audiovisual_Programming](http://redfrik.github.io/udk00-Audiovisual_Programming/) - Fredrik Olofsson's course materials for UdK Berlin
- [Pseudoclasses with events](https://web.archive.org/web/20141008053015/http://www.tmroyal.com/supercollider-pseudoclasses-with-events.html) - Faking object-oriented programming in SuperCollider with Events

### Videos
- [SuperCollider Tutorials](https://www.youtube.com/watch?v=yRzsOOiJ_p4&list=PLPYzvS8A_rTaNDweXe6PX4CXSGq4iEWYC) - Tutorials by Eli Fieldsteel covering a range of subjects
- [Live Coding Tutorials](https://www.youtube.com/playlist?list=PLlWmK4qVXO37vgyLeNe8ElF15pInARU6x) - Tutorials specifically about live coding
- [Masterclass "The Ambisonic Toolkit"](http://www.ambisonictoolkit.net/documentation/supercollider/tutorials/) - A general introduction to ambisonics and the ATK
- [Ultimate Arduino-To-Supercollider Tutorials- Control Signals for Digital Audio](https://www.youtube.com/playlist?list=PLAXkVXyP6y5PF2Xy0hMWiKuIdf2Zu6xnG) - How to use the Arduino micro computers with SC

### Books
- [Introduction to SuperCollider](https://www.logos-verlag.de/cgi-bin/engbuchmid?isbn=4017&lng=eng&id=) - Written by Andrea Valle, includes pdf. Published 2016.
- [The SuperCollider Book](https://mitpress.mit.edu/books/supercollider-book) – The essential reference. Edited by Scott Wilson, David Cottle and Nick Collins. Foreword by James McCartney. Published 2011.

### Research papers
- [NNdef: Livecoding Digital Musical Instruments in SuperCollider using Functional Reactive Programming](http://www.friendlyvirus.org/files/Miguel-Negrao-NNdef-FARM-2018.pdf)

### Others
- [scinterviews.com](http://scinterviews.com/) - SuperCollider interviews

## Quarks and extensions

### Live coding
- [SuperDirt](https://github.com/musikinformatik/SuperDirt) - The sound engine of the TidalCycles pattern language 
- [JITLibExtensions](https://github.com/supercollider-quarks/JITLibExtensions) - Some extensions to the common JITLib classes
- [ixiLangQt](https://github.com/thormagnusson/ixilangQt) - The ixi lang live coding environment is a simple visual system presenting a high entry-level control over synth definitions and samples in SuperCollider

### Controllers
- [Modality Toolkit](https://github.com/ModalityTeam/Modality-toolkit) - Powerful and modal controller library
- [NanoKontrol2](https://github.com/davidgranstrom/NanoKontrol2) - Interface for using Korg NanoKONTROL2 with SuperCollider

### Network
- [Utopia](https://github.com/muellmusik/Utopia) - Network Music Apps in SuperCollider
- [BenoitLib](https://github.com/cappelnord/BenoitLib) - Collaborative and synchronized performances

### Patterns
### Maths
### Immersive audio
- [The Ambisonic Toolkit](https://github.com/ambisonictoolkit/atk-sc3) - Toolkit for working with spatial sound in the ambisonic domain

### FX
- [vstplugin](https://git.iem.at/pd/vstplugin/releases) – IEM's VST Plugin integration for SuperCollider (and Pure Data)
- [Vowel](https://github.com/supercollider-quarks/Vowel) - Convenience Class for Vowel Creation

### Synthesis
- [CaosPercLib](https://github.com/josecaos/caosperclib) - a Collection of Percussion Classes for SuperCollider
- [CaosBox](https://github.com/josecaos/caosbox) - a not-so-common LiveCoding/AlgoRave music GUI secuencer/processor for the CaosPercLib

### GUI
- [wsGUI](https://github.com/dyfer/wsGUI.quark) - User interfaces displayed in a web browser, locally and over the network
- [Automation](https://github.com/neeels/Automation) - Record and playback live GUI activity in supercollider audio synth

## Physical/embedded computing
- [Prynth](http://prynth.github.io/) - Prynth are programmable sound synthesizers powered by Raspberry Pi
- [supercolliderStandaloneRPI2](https://github.com/redFrik/supercolliderStandaloneRPI2) - Standalone for Raspberry Pi 2 or 3 with Raspbian Stretch including the full IDE
- [supercolliderStandaloneRPI1](https://github.com/redFrik/supercolliderStandaloneRPI1) - Standalone for Raspberry Pi 1 or Zero with Raspbian Stretch including the full IDE
- [Bela](https://blog.bela.io/2017/10/29/bela-and-supercollider-live-coding-sensors/) - Bela is an embedded computing platform for creating responsive interactive applications

## Clients
### Language clients
- [SuperColliderJS](https://crucialfelix.github.io/supercolliderjs/) - JavaScript client
- [hsc3](http://hackage.haskell.org/package/hsc3) - Haskell client 
- [Lua2SC](https://github.com/sonoro1234/Lua2SC) - Lua client
- [ScalaCollider](https://github.com/Sciss/ScalaCollider) - Scala client
- [supriya](https://github.com/josiah-wolf-oberholtzer/supriya) - Python client

### Livecode interfaces
- [TidalCycles](http://tidalcycles.org/) - Haskell based live coding environment for patterns
- [FoxDot](https://foxdot.org/) – Python based live coding environment running on top of SuperCollider
- [Overtone](http://overtone.github.io/) - Collaborative live coding using Clojure
- [xi](https://github.com/xi-livecode/xi) - A domain-specific language for live coding musical patterns in Ruby 

## IDE alternatives
- [atom-supercollider](https://github.com/crucialfelix/atom-supercollider) - SuperCollider integration for Atom
- [scvim](https://github.com/supercollider/scvim) - Vim plugin
- [scnvim](https://github.com/davidgranstrom/scnvim) - NeoVim plugin
- [scel](https://github.com/supercollider/scel) - Emacs interface

## Forums
- [scsynth.org](http://scsynth.org/) - Official SuperCollider forum
- [Slack](https://scsynth.slack.com/) - The SuperCollider Slack
- [Lurk](https://talk.lurk.org/channel/supercollider) – Livecode chat 
- [Mailing list](https://www.birmingham.ac.uk/facilities/ea-studios/research/supercollider/mailinglist.aspx) - Official mailing list

## Tools
- [Cookiecutter template for SuperCollider quarks](https://github.com/madskjeldgaard/cookiecutter-quark) - A SuperCollider package (quark) generator using the Cookiecutter cli program. The fastest way to get setup for a quark.

## Contribute

All contributions welcome! 

Read the [contribution guidelines](contributing.md) first.

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0)

To the extent possible under law, Mads Kjeldgaard has waived all copyright and
related or neighboring rights to this work.

Table of Contents generated using doctoc
