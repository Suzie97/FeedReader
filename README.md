[![Ethical Design](https://img.shields.io/badge/Ethical_Design-_▲_❤_-blue.svg)](https://ind.ie/ethical-design)
[![GPLv3 License](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0.en.html)

# Updating behind the scenes
Commnunique is now in development again, and is undergoing changes behind the scenes to update the dependencies and use the latest platform capabilities. Watch this space for more.
---

<p align="center">
  <img src="data/application-icons/hicolor/128x128/apps/com.github.suzie97.communique.svg" alt="Icon" />
</p>
<h1 align="center">Communique</h1>
<p align="center">
  <a href="https://appcenter.elementary.io/com.github.suzie97.communique"><img src="https://appcenter.elementary.io/badge.svg" alt="Get it on AppCenter" /></a>
  <a href='https://flathub.org/apps/details/com.github.suzie97.communique'><img height='51' alt='Download on Flathub' src='https://flathub.org/assets/badges/flathub-badge-en.png'/></a>
</p>

![Screenshot](data/communique-light-screenshot.png)
![Screenshot](data/communique-dark-screenshot.png)

## Your personal journalist
Subscribe to and read RSS/Atom feeds with cross-platform synchronization. Communique is a feed reader with support for a lot of RSS services, like Feedbin, Tiny Tiny RSS, Nextcloud News etc. And ofcourse, you can use Communique to subscribe to and read RSS feeds locally, without logging in to anything.

## Made for [elementary OS](https://elementary.io)

Communique is designed and developed on and for [elementary OS](https://elementary.io). Purchasing through AppCenter directly supports me and elementary. [Get it on AppCenter](https://appcenter.elementary.io/com.github.suzie97.communique) for the best experience.

[![Get it on AppCenter](https://appcenter.elementary.io/badge.svg)](https://appcenter.elementary.io/com.github.suzie97.communique)

## Financial Contribution
You can contribute funds to the project over at Liberapay. Thank you so much 😊️ !! 

<noscript><a href="https://liberapay.com/suzie97/donate"><img alt="Donate using Liberapay" src="https://liberapay.com/assets/widgets/donate.svg"></a></noscript>

## Developing and Building

Flatpak is the recommended way for building Communique. Developing and testing with flatpak helps ensure that everything works correctly inside the flatpak sandbox.
```bash
flatpak-builder build com.github.suzie97.communique.yml --user --install --force-clean
flatpak run com.github.suzie97.communique.yml
```
## Special Thanks to [@jangernert](https://github.com/jangernert)
* More than 90% of the backend of this project is adopted from his project [FeedReader](https://github.com/jangernert/FeedReader). Communique would not have been possible without FeedReader.
