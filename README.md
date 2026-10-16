# NiceTabs
A minimal patch for Firefox that makes the top bar more consistent.

## What it does
Literally just adds padding to the left of the tabs.
Doesn't affect MacOS since the traffic light window controls already basically do this.

## How to Install
> [!NOTE]
> If you already have a userChrome.css, skip all the steps, just append the code inside this repository's `userChrome.css` to the end of your userChrome.css

1. Open a new tab in Firefox and go to `about:config`.
2. Search for `toolkit.legacyUserProfileCustomizations.stylesheets` and set it to **true**.
3. Go to `about:support` and locate your **Profile Directory** row. Click **Open Folder** (or *Show in Finder* on macOS).
4. Create a folder named `chrome` if it does not already exist.
5. Save this repository's `userChrome.css` file directly inside that `chrome` folder.
6. Restart Firefox.
