# i3firefox-theme
- It is the fork and the customized version of the [cankurttekin's wmfox](https://github.com/cankurttekin/wmfox)

## Screenshot
__Hint: Keyboard driven firefox extension: [Surfingkeys extension](https://github.com/brookhong/Surfingkeys)__
- __[My personal Surfingkeys.js config file](https://gist.github.com/mirbehroznoor/de0df8ad9870a69d00e998087f66a0f2)__

![](screenshots_i3firefox-theme.jpg)

---

# Installation

## Mozilla firefox directory

* Go to url: `about:support`

* Under heading `Applicaton Basics` look for section `Profile Directory` and click on the `Open Directory`

* Look for the folder `chrome` or manually create one __OR__ via terminal:

```bash
mkdir -p chrome
```

## `userChrome.css`

### Clone the repository in the `chrome/` folder

* `git clone https://github.com/mirbehroznoor/i3wmfirefox.git`

* Paste the `userChrome.css` file in `chrome/` folder

### Manually create and copy `userChrome.css` contents

* Go to the directory `chrome/` and create the file `userChrome.css`

* Copy and Paste the contents of `userChrome.css`

## Firefox Permissions

* Go to url `about:config`

* Search for `toolkit.legacyUserProfileCustomizations.stylesheets` set it to __TRUE__

* Restart the Firefox to enjoy your new theme

## Keys

* `Ctrl l` or `F6` slides down the navigation bar with url selection

## Advice

   There are no __one-size-fits-all__ theme

   __Have Fun Experimenting__

## Previous i3wm firefox theme 
- [i3wm-firefox-theme](https://github.com/mirbehroznoor/i3wm-firefox-theme)

# Acknowledgments

- [cankurttekin's wmfox](https://github.com/cankurttekin/wmfox)
- [Dook97's firefox-qutebrowser-userchrome](https://github.com/Dook97/firefox-qutebrowser-userchrome)
- [aadilayub's firefox-i3wm-theme](https://github.com/aadilayub/firefox-i3wm-theme)
