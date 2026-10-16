# NiceTabs
A minimal patch for Firefox that makes the top bar more consistent.

## What it does
**NiceTabs** Literally just makes there be some padding to the left of the tabs when there wouldn't be any. It makes it aligned relative to the distance away from the screen the hamburger icon is.

> [!IMPORTANT]
> **NiceTabs is *not* supported on macOS.**<br>
> This is because macOS already places window controls on the left side with native padding, making this patch redundant.

## How to Install

1. Open the folder in this repository named after your OS (Or be lazy and just use the universal folder).
2. Open a new tab in Firefox and go to `about:config`.
3. Search for `toolkit.legacyUserProfileCustomizations.stylesheets` and set it to true.
4. Go to `about:support` and locate your Profile Directory row. Click Open Folder.
5. Create a folder named `chrome` if it does not already exist.
6. Copy the `userChrome.css` file from the folder in step 1 into your local chrome folder.

> [!NOTE]
> If you already have a `userChrome.css` file, append the contents of the file from the folder in step 1 to your already existing `userChrome.css`.

7. Restart ***all** open windows* of Firefox.

> [!TIP]
> **Don't be an idiot**<br>
> Make sure to save any work you care about.
