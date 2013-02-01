# Solarized for LimeChat

LimeChat is an IRC client for OS X. You can get it at http://limechat.net/mac/

Solarized is a supremely well thought-out color scheme. Read more here: http://ethanschoonover.com/solarized

## Preview
I've created a theme for Limechat for both dark:

![Solarized Dark](https://raw.github.com/paulcpederson/solarized-limechat/master/dark.png)

And light:

![Solarized Light](https://raw.github.com/paulcpederson/solarized-limechat/master/light.png)

## Responsive
Both of these themes have one breakpoint at 720px. Smaller than this, the font-size is set to 12px. Larger than 720px, the font size is 14px. The body is given a max-width of 960px so that even if the Limechat window gets very large, the character count of each line will not be uncomfortable to read. The content will simply center in the window.

## Installing 
Installing Limechat themes is easy, just:

```
# Clone the github repo	
git clone https://github.com/paulcpederson/solarized-limechat.git /tmp/solarized-limechat

# Copy the files over to your Limechat Themes folder
mv /tmp/solarized-limechat/*  ~/Library/Application\ Support/LimeChat/Themes/

# Remove the Temporary folder
rm -rf /tmp/solarized-limechat
```

Then just choose "Solarized Light" or "Solarized Dark" inside limechat's preferences.
