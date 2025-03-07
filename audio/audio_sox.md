## Duide to setting up and executing audio testing in an Apple environment (macOS) 
> using SoX for streaming, channels, recording, and playback

**1. Install SoX:**

> Sound eXchange 

*   **Using Homebrew (Recommended):** If you don't have Homebrew, install it from <https://brew.sh/>.  Then run:

```bash
    brew install sox
```

*   **Alternative (MacPorts):** If you're using MacPorts:

> MacPorts is a free, open-source package manager that helps you install, update, and manage open-source software on macOS

Getting MacPorts 
1. Go to macports.org > DOWNLOAD link
2. Get the .dmg disk image for your operating system
3. Install XCode
4.  Run in the Terminal `xcode-select --install` 

OR

```bash
    sudo port install sox
```

> Note:  Make sure your `PATH` is set up correctly so you can run `sox` from the command line.

*  Linux

```bash
sudo apt-get install sox
# Enable mp3 encoder:
sudo apt-get install sox libsox-fmt-mp3
```



```bash
sudo apt-get install sox libsox-fmt-mp3
```

* Mac OS X

```bash
brew info sox
```

  * One of the extra encoders is provided by libvorbis, offering encoding file as ogg, to isntall this incoder you must have not installed SoX and run:

```bash
brew info sox
brew install sox --with-libvorbis
```

