![Graphite Appeal](https://i.imgur.com/UMpsDG6.png)

# Graphite Appeal - Firefox Theme

## Part 1 - Install:

- Install the **Graphite Appeal** theme available [here](https://addons.mozilla.org/en-US/firefox/addon/graphite-appeal/).

## Part 2 - userChrome.css:

The **Graphite Appeal** theme is only complete with its 'userChrome.css', see below how to add it to your Firefox.

You can copy the 'userChrome.css' [here](https://github.com/wandersons13/Graphite-Appeal/blob/main/userChrome/userChrome.css).

### How to install the userChrome.css?

1. **Access the Firefox profile folder:**
   - Open Firefox and in the address bar, type `about:support` and press Enter.
   - In the page that opens, find the "Profile Folder" item and click the "Open Folder" button.

2. **Create the chrome folder:**
   - Inside the Firefox profile folder, look for or create a folder named "chrome" (lowercase).

3. **Paste the userChrome.css file:**
   - Inside the "chrome" folder, paste the "userChrome.css".

4. **Enable userChrome.css in Firefox:**
   - Open Firefox and type `about:config` in the address bar and press Enter.
   - On the advanced settings page, click the "Accept the Risk and Continue" button.
   - In the search bar, type `toolkit.legacyUserProfileCustomizations.stylesheets`.
   - Double-click the found entry to change the value to "true".

5. **Restart Firefox:**
   - Close and reopen Firefox for the changes to take effect.
