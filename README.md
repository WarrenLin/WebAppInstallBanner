# WebAppInstallBanner
You can deploy code on Firebase directed, because that hosting support HTTPS.

### Requirement
* Is served on HTTPS
* Service worker registered on your site
* Has a web app manifest with
  + short_name
  + 192x192 png icon
  + a related_applications object with information about the app
* For testing usefully, enable chrome://flags/#bypass-app-banner-engagement-checks

### Demo
![Alt text](https://github.com/WarrenLin/WebAppInstallBanner/blob/master/demo.gif)
