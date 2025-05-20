# LinuxConfigs

## Zen Browser

Zen browser configs. I also use natsumi-browser, so there may be problems if used without. Also unsure how it behaves with normal firefox.

- Includes userChrome.css, userContent.css and natsumi-config.css;
- Place in the chrome folder (To find it, go to about:profiles, and click "Open Directory" on the "Root Directory" field)

## Dracut

Dracut myflags config.

- This one is just to force early loading of the nvidia drivers (sometimes they wouldn't load on time);
- Place in /etc/dracut.conf.d/

## Locale

Locale config with my personal preferences.

- Place in /etc/

## Fastfetch

Fastfetch config with my personal preferences.

- Place in ~/.config/fastfetch/

## Ghostty

Ghostty terminal config with my personal preferences.

- Place in ~/.config/ghostty/

## Kitty

Kitty terminal config with my personal preferences.

- Place in ~/.config/kitty/

## Oh My Posh

Oh My Posh personal profile.

- Place in ~/.config/ohmyposh/

## Zsh

Zsh personal config

- Careful with the alias and exported PATH, could have errors if the paths don't exist;
- Place as a dot file (.zshrc) in ~/
