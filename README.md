# rEFInd-RetroGame Theme
![](https://user-images.githubusercontent.com/63180210/167790981-0c4ee882-d1d9-4ce6-a894-d69e8bf1c2ef.png)

&emsp;An old-school retro Theme for rEFInd Boot Manager. rEFInd-RetroGame is a theme inspired by the golden yesteryears of Gaming when pixelated graphics and tiny sprites were the norm. There was something beautiful about the design of those games; the colour schemes, the story lines, the illustraions, etc. rEFInd-RetroGame has tried to encapsulate the same artistic brilliancy and nostalgia to help rEFInd users to relive the past. This theme has tried to come up with an amazing blend by trying to combine Artworks of Retro Games with the Modern Minimalist Icon Design patterns. 

&emsp;Efforts have been made to include icons that go well with this theme, all while staying true to the core philosphy behind the making of this theme. Icons for all major and some minor Operating Systems, be it the top Linux Distros or BSD distribution, have been included in this theme to ensure smooth usage of this theme for end users of rEFInd Boot Manager.

![](https://img.shields.io/github/repo-size/riftsandroses/rEFInd-RetroGame?style=for-the-badge)
![](https://img.shields.io/github/license/riftsandroses/rEFInd-RetroGame?style=for-the-badge)
![](https://img.shields.io/github/commit-activity/y/riftsandroses/rEFInd-RetroGame?style=for-the-badge)  
\
**QUICK TIP:**  *rEFInd Boot Manager can easily be installed on Debian-based Linux Distros by running `sudo apt-get install refind -y` in the Linux Terminal window.*


## Screenshot
![](https://user-images.githubusercontent.com/63180210/167786632-f3143356-b3b6-4491-b99e-e7f50ddc5068.png)

## Installation

&emsp;This theme is very easy to install, it is just a matter of moving files from download location to the `rEFInd` installation directory. Following is a 3-step guide to installing this theme:

Step-1 : Navigate to `Home` Directory and Clone the Repository

```bash
  cd ~
  git clone https://github.com/riftsandroses/rEFInd-RetroGame.git
```

Step-2 : Move the Downloaded files to the `rEFInd` Directory (This requires sudo privileges)

```bash
  sudo mv rEFInd-RetroGame /boot/efi/EFI/refind
```

Step-3 : Add Configuration Code for rEFInd-RetroGame Theme in `refind.conf` file
```bash
  sudo echo 'include rEFInd-RetroGame/theme.conf' >> refind.conf
```


## Customization Guide

&emsp;One of the major selling point of rEFInd Boot Manager is the ability to easily customize the Boot Manager according to your need without needing to learn programming specifically for this purpose. Besides the numerous themes available online for free, here are two ways to customize the rEFInd Boot Manager for free. Using these methods gives you access to every aspect of the Boot Manager for customization hence, giving you even greater control on the Themeing and Customization of you rEFInd Boot Manager.

1. **Concise Guide (for Intermediate & Advanced Users) :**
    In the `refind.conf` file found in the `refind` directory, there is an extensive yet short guide on syntaxes and their usages for customization which are commented out. Feel free to go through those comments and implement your own customizations.
2. **Comprehensive Guide (for Knowledgeable Beginners) :**
    On the official website of rEFInd linked here : [rEFInd Official Website](https://www.rodsbooks.com/refind/), a very detailed and comprehensive guide can be found on customizations. This documentation on the Official Website will walk users through syntaxes, their usages and cautionary steps and measures to avoid breaking the installation. 

&emsp;Care must be taken to ensure that all due research is done before attempting these advanced customizations as they might render your Hard Disk and Data unusuable promoting you to make fresh installations. It is advised to have some basic knowledge of Operating Systems and File Storage & Systems Managements.


## FAQ

#### 1. How to install rEFInd Boot Manager on my Laptop or Personal Computer ?

A complete and comprehensive guide to installation of rEFInd Boot Manager can be found on the official website linked below. The installation process might differ for each Operating System so it is advised to go through this website thoroughly before attempting installation on uncommon Operating Systems. Every aspect in regards to the rEFInd Boot Manager can be found here: [rEFInd Official Website](https://www.rodsbooks.com/refind/)

#### 2. How to fix issues of rEFInd-RetroGame theme not applying on rEFInd Boot Manager ?

Most of the issues arising with unsuccessful application of rEFInd-RetroGame theme on the rEFInd Boot Manager can be solved by changing a few lines in `refind.conf` file and `theme.conf` file. In `refind.conf`, it has to be made sure that the 'include' line added by the user must be followed by the correct path to the `theme.conf` file. Assests of themes like icons and background must have correct names and paths in the `theme.conf` file too.

#### 3. How do I get my Operating System logo to show up on rEFInd Boot Manager ?

Most of the popular Operating Systems are supported. In case you are a user of an uncommon Operating System which does not get detected by rEFInd Boot Manager then it is better to get in touch with the creators of rEFInd Boot Manager. If rEFInd Boot Manager supports your Operating System but it does not show up due to absence of a logo in this theme then feel free to reach out via e-mail to request addition of that logo in this Theme Pack.


## Links
[![portfolio](https://img.shields.io/badge/my_portfolio-000?style=for-the-badge&logo=ko-fi&logoColor=white)](https://github.com/riftsandroses)
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/riftsandroses)
[![twitter](https://img.shields.io/badge/twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white)](https://twitter.com/riftsandroses)


## Feedback

If you have any feedback or requests, please do not hesitate to reach out to me at utkarsh.cpp@gmail.com


## License

[GNU General Public License v3.0](https://www.gnu.org/licenses/gpl-3.0.en.html)
