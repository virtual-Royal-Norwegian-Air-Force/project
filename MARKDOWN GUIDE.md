# Markdown Cheat Sheet

Markdown is a simple way to format text that looks great on the web. Instead of highlighting text and clicking buttons like in Microsoft Word, you just add simple symbols to your text.

When you read a file on GitHub (or eventually on our wiki), it automatically translates those symbols into beautifully formatted pages.

## 1. Headings (Creating a Hierarchy)

Use hashtags (`#`) to create headings. The number of hashtags determines the size of the text. Always put a space between the hashtag and the text!

**What you type:**

```markdown
# Major Section (Book Title)
## Chapter Title
### Sub-Section (Paragraph Header)
```

**Best Practice:** Treat headings like an outline. Always start a page with one `#` (H1), use `##` for the main sections, and `###` for smaller chunks. Don't skip from `#` straight to `###` just because you like the font size.

## 2. Text Emphasis

Use asterisks (`*`) to make text stand out.

**What you type:**

```markdown
The APU burns fuel from the *left tank*. (Italics)
**WARNING:** Ensure the canopy is closed. (Bold)
***CRITICAL:*** Ejection seat is armed. (Bold and Italics)
```

**Best Practice:** Use bolding sparingly! If everything is bold, nothing is bold. Reserve bold text for important words.

## 3. Lists and Checklists

Virtual pilots hate reading walls of text. Use lists heavily to make your manuals scannable.

**Unordered Lists (Bullet Points):** Use dashes (`-`) or asterisks (`*`).

```markdown
**Pre-Flight Walkaround:**
- Check left wing
- Check nose gear
- Check right wing
```

**Ordered Lists (Numbered):** Just type the numbers.

```markdown
**Engine Startup Sequence:**
1. Battery switch ON
2. APU switch START
3. Wait for APU RPM to stabilize
```

**Task Lists (Checkboxes):** Great for tracking what needs to be written.

```markdown
- [x] F-16 Startup Guide is finished
- [ ] F-16 Taxi Guide needs writing
```

## 4. Links and Images

Linking to charts or adding diagrams is essential for our SOPs.

**Adding a Link:** Wrap the text you want people to click in brackets `[ ]`, and put the URL immediately after in parentheses `( )`.

```markdown
Read the [VATSIM Code of Conduct](https://vatsim.net/docs/policy/code-of-conduct) before flying.
```

**Adding an Image:** It is exactly the same as a link, but you put an exclamation mark `!` in front of it.

```markdown
![F-16 Cockpit Diagram](link-to-your-image.jpg)
```

Pro-tip: If you are editing a file on GitHub, you can literally just drag and drop an image from your computer into the text box, and GitHub will write this code for you automatically!

## 5. Blockquotes (For Callouts and Notes)

If you want to pull a direct quote from a real-world military manual, or make a specific "Note" stand out from the rest of the text, use the greater-than symbol `>`.

**What you type:**

```markdown
> **NOTE:** Do not exceed 250 knots below 10,000 feet unless authorized by ATC.
```

## 6. Tables (For Speeds and Frequencies)

Tables are perfect for V-speeds, radio frequencies, or loadouts. You use vertical pipes `|` to separate columns, and dashes `-` to separate the header from the content.

**What you type:**

```markdown
| Airbase | Tower Freq | Ground Freq |
| ------- | ---------- | ----------- |
| Bodø    | 118.100    | 121.500     |
| Ørland  | 118.700    | 121.900     |
```
