This repository contains a custom `userChrome.css` script designed to improve the appearance and behavior of the Firefox browser by hiding the top bar (navigator toolbox) in maximized and fullscreen modes, with a trigger area to reveal it when hovering slightly below the default position.

## Features

- **Auto-hide Top Bar**: The top bar (tabs, navigation bar, etc.) is hidden when the window is maximized or in fullscreen mode, providing a cleaner, more immersive browsing experience.
- **Hover Trigger**: A 1px invisible area just below the hidden bar is added so the bar reappears when you hover your mouse slightly below its normal position.
- **Smooth Animation**: The bar is revealed smoothly with a quick transition, providing a responsive feel.
- **Fixed Browser Position**: Ensures that the browser's content fills the entire viewport without overlap, even in fullscreen mode.

## Installation

1. **Locate Firefox Profile Directory**:
   - Open Firefox and type `about:profiles` in the address bar.
   - Under "Profile: Default User" or the active profile, locate the **Root Directory** and click "Open Directory."

2. **Create/Update `chrome` Folder**:
   - In the profile directory, check if there is a `chrome` folder. If not, create a new folder named `chrome`.

3. **Add `userChrome.css` File**:
   - Download or create a new file named `userChrome.css` inside the `chrome` folder.
   - Paste the contents of the script below into the `userChrome.css` file.

4. **Enable Custom Styles**:
   - Type `about:config` in the Firefox address bar and search for the preference `toolkit.legacyUserProfileCustomizations.stylesheets`.
   - Set it to `true` by double-clicking the entry.

5. **Restart Firefox**:
   - Close and restart Firefox to apply the changes.
