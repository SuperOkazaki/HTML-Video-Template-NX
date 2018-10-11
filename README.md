# HTML-Video-Template-NX

This provides a simple framework for making easy to use installable video players for Nintendo Switch. Videos are (obviously) not provided, but easy to make and instructions can be found under the **Encoding** header.

If you just want to get up and running, head down to the **Usage** section and get going.
If you want to preview what it looks like on the Switch console, go to the **Preview** section.

For use with HomebrewWebFramework (can't link it here).

# Features
- Made in simple HTML with no copyrighted/SDK tools, so it can be used if a non-SDK html to .nsp maker comes out
- Responsive and customizable GUI that looks great on the Switch's screen
- Slots for up to 12 videos on a page
  - Later on, this will support more slots on a page, and a configurable second page
- Titles for each video on the main GUI
- Descriptions for each video on the main GUI
- Icons for each video on the main GUI
- Centered banner at the top for the title of the collection
- Template .bmp images for the Horizon app icon

# Usage
1. **Find and download XorTroll's HomebrewWebFramework.** 
  - I can't link it here, but the word on the streets is that you can find it on a specific Discord.
2. **Download the latest release from GitHub**
3. **Edit the headers and descriptions in `index.html` to suit your needs**
  - Individual Video Headers are located at:
      - Line 34
      - Line 40
      - Line 46
      - Line 52
      - Line 58
      - Line 64
      - Line 70
      - Line 76
      - Line 82
      - Line 88
      - Line 94
      - Line 100
  - Episode descriptions are located on the line directly below the header
4. **Edit the individual images**
  - These are located in the `img` directory and are named corresponding to the video number.
  - They are 140x140 .png files and support transparency
  - If you just replace the files without changing the filename, no HTML editing will be necessary
5. **Edit the banner image at the topic**
  - This is `img/banner.png` and is a 1280x140 .png that supports transparency
  - If you replace the file without changing the filename, no HTML editing will be necessary
6. **Edit the attribution at the bottom**
  - At line 122 in `index.html` there is a space to put your name in, if you so choose.
  - I would appreciate if you left the Template credit there, too
7. **Edit the videos**
  - These are located in the `vid` directory
  - The filenames correspond to the same numbering for the headers and images. Just replace the video files and you're good.
  - See the **Encoding** section of the readme for the most reliable results.
8. **Package into a .nsp**
  - Load the project directory into HomebrewWebFramework
  - For an app icon, use a 24-bit 1024x1024 .bmp file
    - If you don't know how to make these, or just want to test the project without making an icon, sample ones are provided in the release.
9. **Install using Tinfoil**
  - I don't care whether you use ReiNX or SX OS, or whatever. But you should use Tinfoil rather than SX's installer.
  
# Encoding
Follow these directions to make the most reliable videos.

The recommended tool is Handbrake. Enable these settings, and optionally make a preset for easier encoding.

- Set video resolution to 1280 x 720 (larger sometimes crashes the browser)
- Enable the "Web Optimized" setting
- Output as .mp4
- If using subtitles, make sure to choose the "burn-in" option.
- Only encode one audio and video track into the file

# Preview
[Here is what it looks like when you download the base template](https://i.imgur.com/Dv1Kzfn.jpg)

[Here is an example of what someone has made, of the show **Oshiete! Galko-chan**](https://imgur.com/cMu3cqm.jpg)

# FAQ and Troubleshooting

**Q: Why can't you link to HomebrewWebFramework?**

A: I just can't. Don't ask me to provide it, because I won't.

**Q: The NSP keeps freezing my Switch when it is launched. What do?**

A: Make sure to enable the "select user on launch" option in the builder.

**Q: Tinfoil says that the NCA is invalid. What do?**

A: Try building with another keygen. 4.0.1-4.1 works well in my experience.

**Q: HomebrewWebFramework is crashing. What do?**

A. Make sure your app icon is a 24-bit .bmp.
