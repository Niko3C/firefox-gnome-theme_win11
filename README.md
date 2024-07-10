# firefox-gnome-theme_win11

## Introduction

This configuration file was modified based on [Firefox-gnome-theme](https://github.com/rafaelmardojai/firefox-gnome-theme) , and I used the author Rafaelmardojai who provided file has some errors when running on the Windows 11 platform, thus the file I uploaded is based on the author's revision. If any Win users have problems using firefox gnome theme, they can refer to my project as a reference.

## Manual installation

1. Go to `about:support` in Firefox.
2. Application Basics > Profile Directory > Open Directory.
3. Copy the **Chrome** folder and **user.js** file I provided to the Profile Directory
4. Restart Firefox.

## Required Firefox preferences

We provide a **user.js** configuration file in `configuration/user.js` that enable some preferences required by this theme to work.

You should already have this file installed if you followed one of the installation methods, but in any case be sure this preferences are enabled under `about:config`:

- toolkit.legacyUserProfileCustomizations.stylesheets

This preference is required to load the custom CSS in Firefox, otherwise the theme wouldn't work.

- svg.context-properties.content.enabled

This preference is required to recolor the icons, otherwise you will get black icons everywhere.

> For other non essential preferences checkout `configuration/user.js`.

## Uninstalling

1. Go to your profile folder. (Go to `about:support` in Firefox > Application Basics > Profile Directory > Open Directory)
2. Remove `chrome` folder and **user.js** file.
3. Restart Firefox.

## Results Show

![](https://raw.githubusercontent.com/Niko3C/PicGo-img/main/firefox-gnome-theme.png)

## Other issues

If you have any questions, you can raise a new issue and we will discuss it together. If you have any other questions, please provide feedback to my email: 3313288623@qq.com