<a href='https://ind.ie/ethical-design'><img style='margin-left: auto; margin-right: auto;' alt='We practice Ethical Design' src='https://img.shields.io/badge/Ethical_Design-_▲_❤_-blue.svg'></a>

<p align="center">
  <img src="data/application-icons/hicolor/128x128/apps/org.gnome.FeedReader.svg" alt="Icon" />
</p>
<h1 align="center">Communique</h1>

![Screenshot](data/communique-light-screenshot.jpg)
![Screenshot](data/communique-dark-screenshot.jpg)

## Your personal journalist
Subscribe to and read RSS/Atom feeds with cross-platform synchronization. Communique is a feed reader with support for a lot of RSS services, like Feedbin, Tiny Tiny RSS, Nextcloud News etc. And ofcourse, you can use Communique to subscribe to and read RSS feeds locally, without logging in to anything.

## Made for [elementary OS](https://elementary.io)

Communique is designed and developed on and for [elementary OS](https://elementary.io). It will be available on [AppCenter](https://appcenter.elementary.io) in the near future. Purchasing through AppCenter directly supports me and elementary. Get it on AppCenter for the best experience.

## Developing and Building

Flatpak is the recommended way for building Communique. Developing and testing with flatpak helps ensure that everything works correctly inside the flatpak sandbox.
```bash
cd build-aux/flatpak/
flatpak-builder build org.gnome.FeedReader.yml --user --install --force-clean
flatpak run org.gnome.FeedReader
```
## Special Thanks to [@jangernert](https://github.com/jangernert)
* More than 90% of the backend of this project is adopted from his project [FeedReader](https://github.com/jangernert/FeedReader). Communique would not have been possible without FeedReader.
