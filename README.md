# Portfolio
Welcome to my project showcase! This repository serves as a central hub for exploring the tools, scripts, and projects I have developed.

## 🎮 Toy Arcade (Games)

***A collection of fun games I have built.***

- [DukeChess](https://github.com/zjbthomas/DukeChess) [[demo](https://dexaint.itch.io/dukechess)]: a digital adaptation of the chess-inspired board game "The Duke".
    - **Highlighted features**: AI opponent, cross-platform multiplayer support (desktop & web).
    - **Tech stack**: Godot (desktop); React & JavaScript (front-end); Java, Node.js & WebSocket/socket.io (back-end).
- [MemoryDungeon](https://github.com/zjbthomas/MemoryDungeon) [[demo](http://memorydungeon.junbinzhang.com)]: an enhanced version of the traditional memory game, with a roguelike gameplay experience.
    - **Highlighted features**: AI opponent, heroes with unique abilities, and gacha mechanics.
    - **Tech stack**: Godot & Qt in C++ (desktop).
- [LinkWord](https://github.com/zjbthomas/LinkWord): a lightweight Chinese word-chain game.
    - **Tech stack**: Python.

## 🔬 Research Corner

***A selection of my most meaningful research projects.***

- [UBCBench](https://github.com/LinaQiu/UBCBench) [[paper](https://www.computer.org/csdl/journal/ts/2022/10/09529015/1wB2FS12ld6)]: a set of benchmarks for analyzing Android static taint analysis tools. Bug fixes and improvements were merged by their original authors (details [here](https://resess.github.io/artifacts/StaticTaint/ubcbench/#fixed-bugs)).
- [ShallowDeepFakesLocalization](https://github.com/zjbthomas/ShallowDeepFakesLocalization) [[paper](https://ieeexplore.ieee.org/document/10074246)]: a deep learning solution that effectively localizes modified regions in fake images.
- [TMO-GAN](https://github.com/zjbthomas/TMO-GAN) [[paper](https://ieeexplore.ieee.org/abstract/document/10074176)]: a Generative Adversarial Network (GAN) designed to produce high-quality 4K High Dynamic Range (HDR) images, significantly
improving perceptual quality.

## 🛠️ Toy Workshop (Scripts)

***Handy scripts I have crafted to make life easier.***

Some userscripts for [Tampermonkey](https://www.tampermonkey.net/), built using **JavaScript**:
- [Steam Wishlist Language Highlighter](https://github.com/zjbthomas/Tampermonkey/tree/main/SteamLanguage): highlights games in a user's Steam wishlist that lack support for specific languages.
    - Language information is retrieved using a **Python** script [here](https://github.com/zjbthomas/SteamOnlineChecker/blob/main/steam_language.py) as a **Github Actions** workflow. 
    - A Google Chrome extension version is also available [here](https://github.com/zjbthomas/LanguageInfo).
- [Arknights YiTuLiu Store Optimizer](https://github.com/zjbthomas/Tampermonkey/blob/main/Arknights): annotates and optimizes redeemed event resources on a popular third-party Arknights support site, helping players decide what to redeem first.
- [ICBC Road Test Helper](https://github.com/zjbthomas/Tampermonkey/tree/main/ICBC): simplifies the process of booking road tests on Insurance Corporation of British Columbia (ICBC) website.

Some tiny scripts based on **Python**:
- [SteamOnlineChecker](https://github.com/zjbthomas/SteamOnlineChecker): a tool using **Github Actions** to automatically monitor the status of a Steam user and send updates via Telegram messages.
- [PRTS-Scraper](https://github.com/zjbthomas/PRTS-Scraper): a lightweight script to scrape Arknights skill icons using MediaWiki APIs. These icons can later be used to train AI image generators to create new ones.

Some modifications on other tools:
- [web-clipper](https://github.com/zjbthomas/web-clipper): I contributed to this Google Chrome extension that supports webpage clipping for popular note-taking apps (e.g., OneNote and Notion) by adding support for OneNote note groups. The [pull request](https://github.com/webclipper/web-clipper/pull/950) was merged by the original author.