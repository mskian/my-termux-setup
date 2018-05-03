# My Termux setup
Here is My Termux Terminal Emulator Setup &amp; Packages 🔖

Linux on Android 💯

## Download Termux

Termux Terminal Emulator for Android

Get it from Google Play store 💯

- Install Termux - https://play.google.com/store/apps/details?id=com.termux&hl=en
- Install Termux API  - https://play.google.com/store/apps/details?id=com.termux.api&hl=en

## My Setup & Packages

- Update Termux

```
apt-get update
apt upgrade
```

- Install cURL

```
pkg install curl
```

- Install git

```
pkg install git
```

- Install wget

```
pkg install wget
```

- Install python3 & python2 (https://wiki.termux.com/wiki/Python)

**Python2**

```
pkg Install python2
```
**Python3**

```
pkg install python
```

- Install jq (pre Format JSON result)

```
pkg install jq
```

- Install libxml2-utils

```
pkg install libxml2-utils
```

- Install grep (about grep - https://en.wikipedia.org/wiki/Grep)

```
pkg install grep
```

- Install bc (Arbitrary Precision Calculator language)

```
pkg install bc
```

- Install htop (Task manager & system Monitor)

```
pkg install htop
```

- Install figlet

```
pkg install figlet
```

- Install httping (pinging tool for HTTP requests)

```
pkg install httping
```

- install dnsutils (Mostly i use this tool for find the website/blog IP address)

```
pkg install dnsutils
```

- Install FFmpeg (Handling video, audio, and other multimedia files and streams)

```
pkg install ffmpeg
```

- Install Termux API (Full info about this - https://termux.com/add-on-api.html)

```
apt install termux-api
```

- Termux SD Card Permission ( https://termux.com/storage.html )

```
apt update && apt upgrade
```

```
termux-setup-storage
```

Termux Storage permission did not create symlink for all folders - ( https://github.com/termux/termux-app/issues/591 )

```
cd $HOME
ls
```

- List the Installed Packages

```
pkg list-installed
```

- Uninstall/Remove Packages

```
pkg uninstall <package-name>
```

- Clear bash Path cache

```
hash -r
```

- Termux Help

```
pkg help
```

- Enable Extra Keys ( https://termux.com/touch-keyboard.html ) **Volume UP+Q**

Learn More about Termux Visit - https://termux.com/

Bookmark this Page More Updates on the way 😊

