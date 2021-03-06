# mocp-i3blocks-status
Shows mocp song name and state in your i3 bar (made for i3blocks)

![Screenshot](https://github.com/curtmack/mocp-i3blocks-status/raw/master/screenshots/example.png)

## Prerequisites
Requires the following CPAN packages:

* `File::HomeDir`
* `IPC::Run3`
* `YAML::Tiny`

## Configuration
The script is highly configurable thanks to grotesque overdesign.

Upon first run, the script will dump a default YAML configuration file called `.mocpstatusrc.yml` in your home directory. You can use this as a guide for configuring it yourself.

## Example usage
Add the mocpstatus script to your i3blocks command directory, then add the following to your i3blocks.conf:

```
# mocp song info
[mocpstatus]
interval=1
```

## Screenshots

### Seekbar styles

Unicode:
![Unicode](https://github.com/curtmack/mocp-i3blocks-status/raw/master/screenshots/unicode_seekbar.png)

ASCII:
![ASCII](https://github.com/curtmack/mocp-i3blocks-status/raw/master/screenshots/ascii_seekbar.png)

### Default settings

Long:
![Long](https://github.com/curtmack/mocp-i3blocks-status/raw/master/screenshots/default_long_format.png)

Short:
![Short](https://github.com/curtmack/mocp-i3blocks-status/raw/master/screenshots/default_short_format.png)
