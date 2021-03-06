# Spacegray

A set of custom UI themes for Sublime Text 2/3. It's all about hype and minimal and comes in different flavors with accompanying [Base16](https://github.com/chriskempson/base16) color schemes.

***

### Themes

#### Spacegray

Default flavor based on Base16 Ocean Dark color scheme.

![image](screenshots/spacegray.png)

#### Spacegray Light

Light variation based on Base16 Ocean Light color scheme.

![image](screenshots/spacegray-light.png)

#### Spacegray Eighties

A variation based on Base16 Eighties Dark color scheme.

![image](screenshots/spacegray-eighties.png)

***

### How to Install

#### ~~Via Package Control~~

~~The easiest way to install is using [Sublime Package Control](https://sublime.wbond.net), where Spacegray is listed as `Spacegray`.~~

1. ~~Open Command Palette using menu item `Tools -> Command Palette...` (⇧+⌘+P on Mac)~~
2. ~~Choose `Package Control: Install Package`~~
3. ~~Find `Spacegray` and hit Enter~~

#### Manual

You can also install the theme manually:

1. Download the latest [.sublime-package file](https://github.com/albertxing/spacegray/releases/download/2.0.0/Spacegray.sublime-package) from the releases
2. Copy into the "Installed Packages" directory

***

### How to Activate

Activate the UI theme and color scheme by modifying your user preferences file, which you can find using the menu item `Sublime Text -> Preferences -> Settings - User` (⌘+, on Mac).

You can choose whichever flavor you like, but don't forget to change *both* color scheme and UI theme so they match.

***Note: Don't forget to restart Sublime Text after activating the theme.***

#### Settings for Spacegray

```
{
  "theme": "Spacegray.sublime-theme",
  "color_scheme": "Packages/spacegray/base16-ocean.dark.tmTheme"
}
```

#### Settings for Spacegray Light

```
{
  "theme": "Spacegray Light.sublime-theme",
  "color_scheme": "Packages/spacegray/base16-ocean.light.tmTheme"
}
```

#### Settings for Spacegray Eighties

```
{
  "theme": "Spacegray Eighties.sublime-theme",
  "color_scheme": "Packages/spacegray/base16-eighties.dark.tmTheme"
}
```

***

### Thanks

The Spacegray Eighties variation is contributed by [Yoshua Wuyts](https://github.com/yoshuawuyts).
