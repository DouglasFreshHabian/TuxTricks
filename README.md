<p align="center">
  <img src="https://github.com/DouglasFreshHabian/TuxTricks/blob/main/Graphics/Tux-Clown-3.png" alt="My Image" width="400">
</p>

<h1 align="center">
🤡 TuxTricks
	</h1>


Welcome to TuxTricks, a whimsical yet powerful collection of fun, quirky, and sometimes downright bizarre Linux tools and commands. Whether you're new to Linux or a seasoned terminal ninja, these tools will make you smile—and maybe even teach you something new.

## 🎪 Tools Showcase

Here are some of the most entertaining and curiosity-sparking tools available on Linux:

fortune-mod – Displays a random quote or aphorism

cowsay – Talking cow ASCII art

xcowsay – A pop-up GUI cow that talks!

cowsay-off – Silences the cow for more serious moments

figlet – Transforms text into ASCII art banners

toilet – Like figlet, but with color and flair

cmatrix – The Matrix-style screen rain effect

oneko – A cat chases your mouse cursor

espeak – Converts text to speech

libaa-bin – ASCII Art rendering utilities

bb – A classic ASCII animation of space and music

pv – Monitor data transfer with progress

aview – Convert images to ASCII

x11-apps – Includes fun tools like xeyes

sysvbanner – Prints system-style banners

funny-manpages – Joke man pages for Linux commands

xjokes – X11 desktop pranks and visual oddities

rev – Reverses text input for playful or practical manipulation

yes - it repeatedly outputs a string or character (by default, the letter `y`) **until killed or stopped**.
## 🔍 Installation and Usage Examples

xjokes
```bash
sudo apt install xjokes
```
> Tools included: yasiti, blackhole, mori1, and mori2 – small visual tools to play with your X display.
---

oneko
```bash
sudo apt install oneko
```

Launch a cat that chases your mouse:
```bash
oneko
```

Customize:
```bash
oneko -name fresh       # Name the kitty 'fresh'
oneko -toname fed       # Launch a second kitty to chase 'fresh'
oneko -tora             # Use tiger stripes
oneko -dog              # Use a puppy instead
oneko -sakura           # Cherry blossom version
oneko -tomoyo           # Anime style kitty
```
---

fortune
```bash
sudo apt install fortune
```
Print to the screen a random fortune
```bash
fortune
```
Use it with cowsay for added fun:
```bash
fortune | cowsay
```
---

pv
```bash
sudo apt install pv
```
Simulate slow typing:
```bash
echo "Fresh Forensics is your go-to source for learning Linux" | pv -qL 10
```
---

aview
```bash
sudo apt install aview
```
Convert images to ASCII in the terminal:
```bash
asciiview image.jpg
```
---

xeyes (from x11-apps)
```bash
sudo apt install x11-apps
```
Little eyes that follow your mouse around the screen.
```bash
xeyes
```
---

banner
```bash
sudo apt install sysvbanner
```
Prints system-style text banners.
```bash
banner Hello
```
---

rev
```bash
sudo apt install util-linux
```
Reverse any string of text:
```bash
echo "scisnerof hserf" | rev
# Output: fresh forensics
```
---

yes
```bash
sudo apt install coreutils
```

Specify a custom string:
```bash
yes "Fresh Forensics"
```
If you want to answer 'yes' to all prompts from a command (e.g., `rm -i`), you can pipe `yes`:
```bash
yes | rm -i *.txt
```
`yes` can be used to generate a heavy stream of output to test system performance or CPU load:
```bash
yes > /dev/null &
```
> This runs in the background and stresses your CPU by printing `y` to nowhere



