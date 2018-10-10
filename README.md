# HTML-Video-Template-NX

This project currently works, but has no documentation on usage yet. If you are familiar with web development, it won't be hard to decipher, but for the rest of you, documentation is coming soon.

For use with HomebrewWebFramework (can't link it here).

This provides a simple framework for making easy to use installable video players for Nintendo Switch. Videos are (obviously) not provided, but easy to make and instructions can be found under the **Encoding** header.

# Usage


# Encoding
Follow these directions to make the most reliable videos.

The recommended tool is Handbrake. Enable these settings, and optionally make a preset for easier encoding.

- Set video resolution to 1280 x 720 (larger sometimes crashes the browser)
- Enable the "Web Optimized" setting
- Output as .mp4
- If using subtitles, make sure to choose the "burn-in" option.
- Only encode one audio and video track into the file

# FAQ and Troubleshooting

**Q: Why can't you link to HomebrewWebFramework?**

A: I just can't. Don't ask me to provide it, because I won't.

**Q: The NSP keeps freezing my Switch when it is launched. What do?**

A: Make sure to enable the "select user on launch" option in the builder.

**Q: Tinfoil says that the NCA is invalid. What do?**

A: Try building with another keygen. 4.0.1-4.1 works well in my experience.

**Q: HomebrewWebFramework is crashing. What do?**

A. Make sure your app icon is a 24-bit .bmp.
