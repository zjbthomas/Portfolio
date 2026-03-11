# Portfolio

*Junbin Zhang (Thomas), Ph.D.*  
[![LinkedIn](https://custom-icon-badges.demolab.com/badge/LinkedIn-0A66C2?logo=linkedin-white&logoColor=fff)](https://www.linkedin.com/in/junbinzhang/)

Welcome to my project showcase!  
This repository serves as a central hub for exploring the 🎮[**games**](#-toy-arcade-games), 🔬[**research projects**](#-research-corner), 🛠️[**scripts**](#%EF%B8%8F-toy-workshop-scripts), and 🌐[**websites**](#-website-creations) I have developed.

## 🎮 Toy Arcade (Games)

***A collection of fun games I have built.***

| Game | Code | Demo | Description | Highlighted Features | Tech Stack |
| - | - | - | - | - | - |
| **DukeChess** | [![code](https://img.shields.io/badge/code-333333?style=flat)](https://github.com/zjbthomas/DukeChess) | [![play](https://img.shields.io/badge/play-4f7f6a?style=flat)](https://dexaint.itch.io/dukechess)    | ♟️ Digital adaptation of the chess-inspired board game *The Duke* | - AI opponent<br>- Cross-platform multiplayer support (desktop & web)<br>- [**Docker** image](https://hub.docker.com/repository/docker/zjbthomas/dukechess-godot-web/general) available for easy deployment | Desktop:<br>![Godot](https://img.shields.io/badge/Godot-478cbf?style=flat&logo=godot-engine&logoColor=white)<br>Front-end:<br>![React](https://img.shields.io/badge/React-20232a?style=flat&logo=react&logoColor=61dafb) ![JavaScript](https://img.shields.io/badge/JavaScript-323330?style=flat&logo=javascript&logoColor=f7df1e)<br>Back-end:<br>![Java](https://img.shields.io/badge/Java-333333?style=flat&logo=java&logoColor=white) ![Node.js](https://img.shields.io/badge/Node.js-333333?style=flat&logo=node.js&logoColor=68a063) ![Socket.IO](https://img.shields.io/badge/Socket.IO-(WebSocket)-333333?style=flat&logo=socket.io&logoColor=white) ![Redis](https://img.shields.io/badge/Redis-333333?style=flat&logo=redis&logoColor=dc382d)<br>Containerization:<br>![Docker](https://img.shields.io/badge/Docker-8fa3b8?style=flat&logo=docker&logoColor=444) |
| **MemoryDungeon** | [![code](https://img.shields.io/badge/code-333333?style=flat)](https://github.com/zjbthomas/MemoryDungeon) | [![play](https://img.shields.io/badge/play-4f7f6a?style=flat)](http://memorydungeon.junbinzhang.com) | 👾 Roguelike twist on the memory game  | - AI opponent<br>- Heroes with unique abilities<br>- Gacha mechanics | Front-end (desktop):<br>![Godot](https://img.shields.io/badge/Godot-478cbf?style=flat&logo=godot-engine&logoColor=white) ![Qt](https://img.shields.io/badge/Qt-(C++)-333333?style=flat&logo=qt&logoColor=41cd52)<br>Back-end:<br>![Node.js](https://img.shields.io/badge/Node.js-333333?style=flat&logo=node.js&logoColor=68a063) ![Redis](https://img.shields.io/badge/Redis-333333?style=flat&logo=redis&logoColor=dc382d) |
| **LinkWord** | [![code](https://img.shields.io/badge/code-333333?style=flat)](https://github.com/zjbthomas/LinkWord) |  | 🔤 Lightweight Chinese word-chain game |  | ![Python](https://img.shields.io/badge/Python-333333?style=flat&logo=python&logoColor=3776ab) |

> ℹ️ If any of the demo links above do not work, please **[create an issue](../../issues)** so I can take a look.

[⤴️ <u>*back to top*</u>](#portfolio)

## 🔬 Research Corner

***A selection of my most meaningful research projects.***

[![Google Scholar](https://img.shields.io/badge/Google_Scholar-4285F4?logo=googlescholar&logoColor=white&style=flat)](https://scholar.google.ca/citations?user=KJKRoyEAAAAJ)

[![PhD](https://img.shields.io/badge/PhD%20Thesis-Detection,%20Attribution,%20and%20Localization%20of%20Manipulated%20Images-8b1a1a?style=flat)](https://dx.doi.org/10.14288/1.0450146)  
[![MASc](https://img.shields.io/badge/MASc%20Thesis-Analyzing%20Android%20Taint%20Analysis%20Tools:%20FlowDroid,%20Amandroid,%20and%20DroidSafe-8b1a1a?style=flat)](https://dx.doi.org/10.14288/1.0392613)

### 🤖 Image Forensics

#### *Pixel-frequency Hybrid Approaches*
- **Shallow- & Deep-fake Images Localization**  
    [![paper](https://img.shields.io/badge/paper%20(conference)-8b1a1a?style=flat)](https://ieeexplore.ieee.org/document/10074246)
    [![arXiv](https://img.shields.io/badge/arXiv-2601.02566-b31b1b.svg)](https://arxiv.org/abs/2601.02566)
    [![code](https://img.shields.io/badge/code-333333?style=flat)](https://github.com/zjbthomas/ShallowDeepFakesLocalization)  
    ![UperNet](https://img.shields.io/badge/UperNet-9aa5b1?style=flat)
    ![Vision Mamba](https://img.shields.io/badge/Vision%20Mamba-9aa5b1?style=flat)
    ![GNN](https://img.shields.io/badge/GNN-9aa5b1?style=flat)
    ![ONNX](https://img.shields.io/badge/ONNX-8fa3b8?style=flat&logo=onnx&logoColor=444)  
    A deep learning method that detects and localizes manipulated regions in both shallow- and deep-fake images.
    - Built upon the **UperNet** semantic segmentation framework.
    - A journal extension leveraging **Vision Mamba** and **Graph Neural Networks** is currently under review and available on [arXiv](https://arxiv.org/abs/2601.02566).
    - An **ONNX** model converted from the original Python implementation is provided [here](https://github.com/zjbthomas/ShallowDeepFakesLocalization/tree/journal/onnx), with custom functions implemented to support the conversion.

#### *Frequency-domain Approaches*
- **Frequency-based AI-generated Images Detection**  
    [![paper](https://img.shields.io/badge/paper-8b1a1a?style=flat)](https://ieeexplore.ieee.org/abstract/document/10221905)
    [![code](https://img.shields.io/badge/code-333333?style=flat)](https://github.com/zjbthomas/FreqAIDetector)
    [![demo](https://img.shields.io/badge/demo-4f7f6a?style=flat)](https://zjbthomas.github.io/FreqAIDetector/)  
    ![AWS](https://img.shields.io/badge/AWS-8aa399?style=flat&logo=amazonaws&logoColor=444)
    ![ONNX](https://img.shields.io/badge/ONNX-8fa3b8?style=flat&logo=onnx&logoColor=444)
    ![MCP](https://img.shields.io/badge/MCP-9aa5b1?style=flat)  
    A deep learning model that detects images generated by Stable Diffusion models using frequency-domain artifacts (>99% accuracy).  
    - 🏰 Disney images were used as a case study.
    - A live demo is available [here](https://zjbthomas.github.io/FreqAIDetector/), with a backend running on **AWS** (API Gateway, [Lambda](https://github.com/zjbthomas/FreqAIDetector/tree/main/deploy/AWS/Lambda), and S3) and the model exported to **ONNX** for efficient inference.
    - An **MCP** (Model Context Protocol) *Server* is implemented [here](https://github.com/zjbthomas/FreqAIDetector/tree/main/deploy/MCP) as a *Tool* written in **TypeScript**, enabling LLMs to invoke the model for inference.
    

- **Frequency-based AI-generated Images Attribution**  
    [![paper](https://img.shields.io/badge/paper-8b1a1a?style=flat)](https://ieeexplore.ieee.org/abstract/document/10855423)
    [![code](https://img.shields.io/badge/code-333333?style=flat)](https://github.com/zjbthomas/FreqGANAttribution)  
    A frequency-based network that attributes fake images to their source Generative Adversarial Network (GAN) architecture (>95% accuracy).

#### *Sensor-level Approaches*
- **AI-generated Images Detection Trained with Raw Images Only**  
    ![paper](https://img.shields.io/badge/paper%20(available%20soon)-8b1a1a?style=flat)
    [![code](https://img.shields.io/badge/code-333333?style=flat)](https://github.com/zjbthomas/BayerRealOnlyDetector)  
    ![VAE](https://img.shields.io/badge/VAE-9aa5b1?style=flat)  
    A **Variational Autoencoder (VAE)**-based approach trained solely on real/raw images for detecting AI-generated content (~94% accuracy).

- **AI-generated Images Detection by Reconstructing Raw Images**  
    [![paper](https://img.shields.io/badge/paper-8b1a1a?style=flat)](https://link.springer.com/chapter/10.1007/978-3-031-94962-3_2)
    [![code](https://img.shields.io/badge/code-333333?style=flat)](https://github.com/zjbthomas/BayerRecDetector)  
    A method that detects AI-generated images by reconstructing Bayer patterns and comparing statistical differences between real and fake images (~98% accuracy).  
    Notably, this method requires no deep learning.

### 📱 Mobile Security
- **Comparison of Android Static Taint Analyzers**  
    [![paper](https://img.shields.io/badge/paper-8b1a1a?style=flat)](https://www.computer.org/csdl/journal/ts/2022/10/09529015/1wB2FS12ld6)
    [![code](https://img.shields.io/badge/code-333333?style=flat)](https://github.com/LinaQiu/UBCBench)  
    ![Android](https://img.shields.io/badge/Android-8fa3b8?style=flat&logo=android&logoColor=444)  
    A comparative study of **Android** **static taint analysis** tools (*FlowDroid*, *Amandroid*, and *DroidSafe*), evaluating their effectiveness and limitations using standardized benchmarks.
    - We built [**UBCBench**](https://github.com/LinaQiu/UBCBench), a benchmark suite for evaluating Android static taint analysis tools.
    - Bug fixes and improvements were merged by their original authors (details [here](https://resess.github.io/artifacts/StaticTaint/ubcbench/#fixed-bugs)).

- **Android OAuth Vulnerability Analysis**  
    [![report](https://img.shields.io/badge/report-8b1a1a?style=flat)](https://github.com/zjbthomas/OAuthUsage/blob/main/report.pdf)
    [![code](https://img.shields.io/badge/code-333333?style=flat)](https://github.com/zjbthomas/OAuthUsage)  
    A course project that investigates security risks in Android applications using the **OAuth** protocol.

- **Android Password Leakage Detection**  
    [![report](https://img.shields.io/badge/report-8b1a1a?style=flat)](https://github.com/zjbthomas/EECE512/blob/master/report.pdf)
    [![code](https://img.shields.io/badge/code-333333?style=flat)](https://github.com/zjbthomas/EECE512)  
    A course project that detects potential password leakage in Android applications using the *FlowDroid* framework, an Android static analysis tool.

### 🖼️ Image Generation
- **TMO GAN**  
    [![paper](https://img.shields.io/badge/paper-8b1a1a?style=flat)](https://ieeexplore.ieee.org/abstract/document/10074176)
    [![code](https://img.shields.io/badge/code-333333?style=flat)](https://github.com/zjbthomas/TMO-GAN)  
    ![GAN](https://img.shields.io/badge/GAN-9aa5b1?style=flat)  
    A **GAN** designed to tone map high-quality 4K **High Dynamic Range (HDR)** images, significantly enhancing perceptual quality.

### 🥽 Virtual Reality
- **Subjective Evaluation of Foveated Image Quality in Head-mounted Displays (HMDs)**  
    [![paper](https://img.shields.io/badge/paper-8b1a1a?style=flat)](https://sid.onlinelibrary.wiley.com/doi/abs/10.1002/sdtp.14152)  
    ![Unity](https://img.shields.io/badge/Unity-9b8bc1?style=flat&logo=unity&logoColor=444)
    ![OpenVR](https://img.shields.io/badge/OpenVR-9b8bc1?style=flat)
    ![OpenGL](https://img.shields.io/badge/OpenGL-9b8bc1?style=flat&logo=opengl&logoColor=444)  
    A novel subjective evaluation method for assessing the perceptual quality of foveated rendering in HMDs.
    - Developed an interactive voting mechanism using controllers in **Unity** to collect subjective user ratings.
    - Captured **eye-tracking** data via **OpenVR** and **OpenGL** and integrated it into the evaluation pipeline.

### 🎞️ Video Compression
- **Visual-Attention-Model-based HDR Video Compression**  
    ![paper](https://img.shields.io/badge/paper%20(available%20soon)-8b1a1a?style=flat)  
    ![HEVC](https://img.shields.io/badge/HEVC-(HM)-8aa399?style=flat)  
    A visual-attention-driven HDR video compression method that incorporates perceptual saliency into the adaptive Quantization Parameter (QP) assignment of the **High Efficiency Video Coding (HEVC)** standard.

### 🎯 Serious Games
- **BankPet**  
    [![report](https://img.shields.io/badge/report-8b1a1a?style=flat)](https://courses.ece.ubc.ca/518/previous/hit2017W/papers/WuRangZhang.pdf)  
    ![Android](https://img.shields.io/badge/Android-8fa3b8?style=flat&logo=android&logoColor=444)
    ![Arduino](https://img.shields.io/badge/Arduino-8aa399?style=flat&logo=arduino&logoColor=444)  
    A serious game–based banking application featuring a virtual character (🐱 *everyone loves cats!*) designed to help users develop better credit card and personal money management habits, validated through a user study.

[⤴️ <u>*back to top*</u>](#portfolio)

## 🛠️ Toy Workshop (Scripts)

***Handy scripts I have crafted to make life easier.***

### 🐵 Tampermonkey Userscripts (*JavaScript*) 
- **Steam Wishlist Language Highlighter**  
    [![code](https://img.shields.io/badge/code-333333?style=flat)](https://github.com/zjbthomas/Tampermonkey/tree/main/SteamLanguage)  
    ![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-8aa399?style=flat&logo=githubactions&logoColor=444)
    ![Google Chrome Extension](https://img.shields.io/badge/Chrome%20Extension-8fa3b8?style=flat&logo=googlechrome&logoColor=444)  
    Highlights games in a user's Steam wishlist that lack support for specific languages.
    - Language information is retrieved using a **Python** script [here](https://github.com/zjbthomas/SteamOnlineChecker/blob/main/steam_language.py) as a **GitHub Actions** workflow. 
    - A Google Chrome extension version is also available [here](https://github.com/zjbthomas/LanguageInfo).

- **Arknights YiTuLiu Store Optimizer**  
    [![code](https://img.shields.io/badge/code-333333?style=flat)](https://github.com/zjbthomas/Tampermonkey/blob/main/Arknights)  
    Annotates and 🏆**prioritizes** redeemed event resources on a popular third-party Arknights support site, helping players decide what to redeem first.

- **ICBC Road Test Helper**  
    [![code](https://img.shields.io/badge/code-333333?style=flat)](https://github.com/zjbthomas/Tampermonkey/tree/main/ICBC)  
    Simplifies the process of booking road tests on the Insurance Corporation of British Columbia (ICBC) website.

### 🐍 *Python* Scripts 
- **Steam Online Status Checker**  
    [![code](https://img.shields.io/badge/code-333333?style=flat)](https://github.com/zjbthomas/SteamOnlineChecker)  
    ![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-8aa399?style=flat&logo=githubactions&logoColor=444)  
    A tool using **GitHub Actions** to automatically monitor the status of a Steam user and send updates via Telegram messages.

- **PRTS Scraper**  
    [![code](https://img.shields.io/badge/code-333333?style=flat)](https://github.com/zjbthomas/PRTS-Scraper)  
    A lightweight script to scrape Arknights skill icons using MediaWiki APIs.  
    These icons can later be used to train AI image generators to create new ones.

### 💻 Code Contributions
- **web-clipper**  
    [![code](https://img.shields.io/badge/code-333333?style=flat)](https://github.com/zjbthomas/web-clipper)  
    ![Google Chrome Extension](https://img.shields.io/badge/Chrome%20Extension-8fa3b8?style=flat&logo=googlechrome&logoColor=444)  
    I contributed to this Google Chrome extension that supports webpage clipping for popular note-taking apps (e.g., OneNote, Notion) by adding support for OneNote note groups.  
    **The [pull request](https://github.com/webclipper/web-clipper/pull/950) was merged by the original author.**

[⤴️ <u>*back to top*</u>](#portfolio)

## 🌐 Website Creations

***Websites I have built or contributed to.***

- **University of British Columbia, Digital Multimedia Lab**  
    [![live](https://img.shields.io/badge/live-4f7f6a?style=flat)](https://dml.ece.ubc.ca/)  
    ![Hugo Blox](https://img.shields.io/badge/Hugo%20Blox-8fa3b8?style=flat)  
    I designed and currently maintain the website for my Ph.D. research lab, built on the [Hugo Blox](https://hugoblox.com/) framework.  
    I customized the framework to meet specific lab requirements:
    - Publications are categorized into finer-grained types (e.g., conference papers, journal articles), and the search function was rewritten to work within each category.
    - By adding new metadata to page elements, lab members can redirect to their own departmental web pages.
    - Embedded website statistics by modifying the universal footer.

- **Personal Website**  
    [![live](https://img.shields.io/badge/live-4f7f6a?style=flat)](https://people.ece.ubc.ca/~zjbthomas/)  
    ![jQuery](https://img.shields.io/badge/jQuery-8fa3b8?style=flat&logo=jquery&logoColor=444)  
    My personal website built with **HTML** and **jQuery**.  
    🌈 *Refresh the page to see dynamically changing background colors!*

- **BC Liquor Store Explorer**  
    [![demo](https://img.shields.io/badge/demo-shiny-4a6fa5?style=flat)](https://junbinzhang.shinyapps.io/junbinzhang-bcl/)
    [![code](https://img.shields.io/badge/code-333333?style=flat)](https://github.com/STAT545-UBC-hw-2018-19/hw08-zjbthomas)  
    A course project web app that allows users to explore BC Liquor products with filters such as price, type, and country.
    - **Highlighted features**: interactive search and filtering, data visualization with Shiny.
    - **Tech Stack**: R, Shiny

[⤴️ <u>*back to top*</u>](#portfolio)

---

## 🧭 In the End: Why This Portfolio?

This repository serves two purposes:
- It presents an organized overview of my work, making my projects easier to understand and explore for readers beyond individual repositories.
- It also functions as a centralized index of my GitHub projects for long-term organization and reference.

As projects naturally grow across multiple repositories and organizations, GitHub currently offers limited support for presenting them as a coherent body of work. This portfolio serves as a developer-maintained overview that improves **organization and discoverability**, addressing a gap in how evolving personal GitHub project collections are presented.

[⤴️ <u>*back to top*</u>](#portfolio)