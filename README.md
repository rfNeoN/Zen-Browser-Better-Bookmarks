# Better Bookmarks

**Better Bookmarks** overhauls the browser's bookmarks UI, giving you the freedom to customize it the way you like.

## What does this mod actually do?

After installing the mod, you get access to the following options:

- Toggle folder and subfolder icons
- Toggle website icons
- Toggle folders expand arrow
- Toolbar item alignment
- Smooth popup animation
- Hide "open all in tabs" button
- Bookmarks popup background and text color: follow user theme or set a custom color
- Bookmarks sidebar background color: follow user theme or set a custom color

![Preview Image](preview.png)

## Installation

> [!NOTE]
> This mod is not currently available in the Zen browser store. If you'd like to use it, please follow the manual installation steps below or look at [zen docs](https://docs.zen-browser.app/).

Step 1: Download the Files

Download both `chrome.css` and `preferences.json` files to your computer.

Step 2: Locate Your Zen Browser Profile

- Open Zen browser
- In the address bar, type `about:support` and press Enter
- Find Profile Folder and click the Open Folder button next to it

Step 3: Register the Theme

- In your profile folder, locate the `zen-themes.json` file and open it in a text editor
- Important: Carefully add the following JSON block to the main array. Make sure to add a comma , at the end of the previous item before pasting this new one:

```
{
    "Better-Bookmarks": {
        "id": "Better-Bookmarks",
        "name": "Better Bookmarks",
        "description": "Change bookmarks UI the way you like it to be",
        "homepage": "https://github.com/rfNeoN/Zen-Browser-Better-Bookmarks",
        "style": "local",
        "author": "rfNeoN",
        "preferences": "local",
        "version": "1.0.0",
        "createdAt": "2026-06-14",
        "updatedAt": "2026-06-29",
        "enabled": true
    }
}
```
> [!TIP]
> If you're not comfortable editing JSON manually, use a JSON validator or formatter to ensure your syntax is correct.

Step 4: Add the Theme Files

- Navigate to `chrome/zen-themes` inside your profile folder (create these folders if they don't exist)
- Create a new folder named Better-Bookmarks (must match the id from the JSON exactly)
- Paste both downloaded files (`chrome.css` and `preferences.json`) into this new folder

Step 5: Restart Zen Browser

- The theme should now be active. If it doesn't appear, restart the browser completely.
