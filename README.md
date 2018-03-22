Template for using [revealjs](https://github.com/hakimel/reveal.js).

# Idea

- Clone this repo
- Run the install script
- It makes some opinionated changes (details will follow)
- You have a clean new start for your presentation

# Prerequisites

Only tested with Linux. YMMV dependent on your OS.

- wget
- tar

Using RevealJs obviously requires NodeJs. This setup does not require NodeJs.

# Initial setup 

After cloning this repo:

- Run `./setup.sh`. It will remove the `.git` folder so you can start from scratch.
- `cd slides && npm install && npm start`

That's it!

# Project structure

- `slides`: the revealjs presentation
- `code`: empty folder for code samples. Use this folder for live coding samples! If you don't do live coding, you can delete this folder.

# And Windows?

Pull requests are welcome! PowerShell or BAT Hackers, where are you?

Or use the minimal bash shell included with Git-for-windows. Or the Full-Linux Support with Windows10. Or Cygwin. Or...

# Showcases

- [x] Background images with markdown
- [x] Change highlighting of code samples (step by step)
- [x] slide customizations using `data-*` attributes in markdown
- [x] company logo on each slide

# Screenshots

![company logo](screenshots/company-logo.png)

![code syntax highlighting](screenshots/code-syntax-highlighting.png)

![backround image](screenshots/background-images.png)

![tagcloud](screenshots/tagcloud.png)