# rEFInd-RetroGame Theme

An old-school retro Theme for rEFInd Boot Manager. rEFInd-RetroGame is a theme inspired by the golden yesteryears of Gaming when pixelated graphics and tiny sprites were the norm. There was something beautiful about the design of those games; the colour schemes, the story lines, the illustraions, etc. rEFInd-RetroGame has tried to encapsulate the same artistic brilliancy and nostalgia to help rEFInd users to relive the past. This theme has tried to come up with an amazing blend by trying to combine Artworks of Retro Games with the Modern Minimalist Icon Design patterns. 

Efforts have been made to include icons that go well with this theme, all while staying true to the core philosphy behind the making of this theme. Icons for all major and some minor Operating Systems, be it the top Linux Distros or BSD distribution, have been included in this theme to ensure smooth usage of this theme for end users of rEFInd Boot Manager.

![](https://img.shields.io/github/repo-size/riftsandroses/rEFInd-RetroGame?style=for-the-badge)
![](https://img.shields.io/github/license/riftsandroses/rEFInd-RetroGame?style=for-the-badge)
![](https://img.shields.io/github/commit-activity/w/riftsandroses/rEFInd-RetroGame?style=for-the-badge)

## Screenshots

## Installation

This theme is very easy to install, it is just a matter of moving files from download location to the rEFInd installation directory. Following is a 3-step guide to installing this theme:

Step-1 : Navigate to Home Directory and Clone the Repository

```bash
  cd ~
  git clone https://github.com/riftsandroses/rEFInd-RetroGame.git
```

Step-2 : Move the Downloaded files to the rEFInd Directory (This requires sudo privileges)

```bash
  sudo mv rEFInd-RetroGame /boot/efi/EFI/refind
```

Step-3 : Add Configuration Code for rEFInd-RetroGame Theme in refind.conf file
```bash
  sudo echo 'include rEFInd-RetroGame/theme.conf' >> refind.conf
```

## Customization Guide

## FAQ

#### 1. How to install rEFInd Bootloader ?

A complete and comprehensive guide to installation of rEFInd Boot Manager can be found on the official website linked below. The installation process might differ for each Operating System so it is advised to go through this website thoroughly before attempting installation on uncommon Operating Systems. Every aspect in regards to the rEFInd Boot Manager can be found here: [rEFInd Official Website](https://www.rodsbooks.com/refind/)

#### 2. How to fix issues of rEFInd-RetroGame theme not applying ?
Most of the issues arising with unsuccessful application of rEFInd-RetroGame theme on the rEFInd Boot Manager can be solved by changing a few lines in refind.conf file and theme.conf file. In refind.conf, it has to be made sure that the 'include' line added by the user must be followed by the correct path to the theme.conf file. Assests of themes like icons and background must have correct names and paths in the theme.conf file too.

#### 3.

## Links
[![portfolio](https://img.shields.io/badge/my_portfolio-000?style=for-the-badge&logo=ko-fi&logoColor=white)](https://github.com/riftsandroses)
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/riftsandroses)
[![twitter](https://img.shields.io/badge/twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white)](https://twitter.com/riftsandroses)


## Feedback

If you have any feedback, please do not hesitate to reach out to me at utkarsh.cpp@gmail.com


## License

[GNU General Public License v3.0](https://www.gnu.org/licenses/gpl-3.0.en.html)
