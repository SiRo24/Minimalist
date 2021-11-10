# Minimalist
Minimalistic Firefox Theme using userChrome.css.

Save space and only focus on the neccessery things.
<br>The current Tab title and its favicon are fully displayed alongside the URL bar. 
Other tabs only get displayed on hover.

![ezgif com-gif-maker(1)](https://user-images.githubusercontent.com/80770571/141157882-a65e7639-3375-46fc-82b2-155ca5376e2a.gif)
Tab size increases on hover for better visibility.

## Compatibility
Works perfectly fine on the most current Firefox
<br>Tested on 94.0.1

## Attention
Forwards and backwards buttons are removed in this skin, it's meant to be used with keyboard mouse shortcuts
<br>(maybe a button version coming in the future)
<br>
<br>If you firstly install the theme it might look not as expected, so you have to adjust your Firefox Symbol bar

## Installation

1. In `about:config` change those values to true:

**`toolkit.legacyUserProfileCustomizations.stylesheets`**  --> (basic support for css)
<br>**`gfx.webrender.all`** --> (support for background blur features, used in the URL bar and on many websites)
<br>**`layout.css.backdrop-filter.enabled`** ^

2. Type in `about:support` and find the path of your Firefox `Root Directory`.
3. In there, if it doesn't already exist, create a folder called `chrome`. Paste the .css file without changing its name
4. Restart Firefox and enjoy your new theme!

