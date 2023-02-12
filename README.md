# Minimalist (not working currently)
Minimalistic Firefox Theme using userChrome.css.

Save space and only focus on the neccessery things.
<br>The current Tab title and its favicon are fully displayed alongside the URL bar. 
Other tabs only get displayed on hover.

![ezgif com-gif-maker(1)](https://user-images.githubusercontent.com/80770571/141157882-a65e7639-3375-46fc-82b2-155ca5376e2a.gif)
Tab size increases on hover for better visibility.

## Compatibility
Update:
Even though Firefox added backdrop support by default the blur in this theme doesnt work perfectly.

## Attention
Forwards and backwards buttons are removed in this skin, it's meant to be used with keyboard or mouse shortcuts
<br>(maybe a button version coming in the future)
<br>
<br>If you firstly install the theme it might look not as expected, so you have to adjust your Firefox Symbol bar

## Installation

1. In `about:config` change those values to true:

**`toolkit.legacyUserProfileCustomizations.stylesheets`**  --> (basic support for css)
<br>**`gfx.webrender.all`** --> (support for background blur features in the top bar)
<br>**`layout.css.backdrop-filter.enabled`** Not necessary Firefox v 103 and above

2. Type in `about:support` and find the path of your Firefox `Profile Directory`.
3. In there, if it doesn't already exist, create a folder called `chrome`. Paste the .css file without changing its name
4. Restart Firefox and enjoy your new theme!

