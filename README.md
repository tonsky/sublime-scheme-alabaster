# Alabaster Color Scheme

A light color scheme with minimal amount of highlighting for Sublime Text 3.

## Motivation

Most color schemes highlight everything they can, ending up looking like a fireworks show.

Instead, Alabaster uses minimal highlighting; it defines just four classes:

  1. Strings
  2. All statically known constants (numbers, symbols, keywords, boolean values)
  3. Comments
  4. Global definitions

Additionally:

- Alabaster does not highlight standard language keywords (if, else, function, etc). They are usually least important and most obvious part of any program.

- Alabaster highlights comments. Most schemes try to dim comments by using low-contrast greys. I think if code was complex enough that it deserved an explanation then it’s that explanation we should see and read first. It would be a crime to hide it.

- Alabaster doesn’t use font variations. It’s hard to scan code when it jumps between normal, **bold** and *italics* all the time. Also, not all fonts provide bold/italics variants.

- Having minimal amount of rules means you can consciously use them to look for the exact piece of information you need. Most other “fireworks” schemes provide only one meaningful contribution: if it’s colored it’s probably syntactically correct. Instead, in Alabaster you can actually remember all the rules, and e.g. if you need to look for a string you know that you’re looking for a green token. And all the strings really pop out because there are not many other things highlighted.

- Alabaster only highlights things that parser could identify reliably. I believe that if highlighting works only partially then it does more harm than good. When highlighting works reliably, your brain learns to rely on it. When it’s not reliable, your brain spends precious brain cycles to re-check everything it sees on the screen.

## Variations

Alabaster BG is a variation of the same scheme but it uses background color for highlighting instead of text color. The idea is that it is easier to read when all text is black rather than when it changes color every few words. The colored background in that case creates a separate layer which is easier to ignore if you just trying to read the words.

Alabaster Dark is just a dark version based on the same principles.

Alabaster Mono and Alabaster Dark Mono are monochromatic version, with only cursor and occasional errors/search results highlighted.

![Screenshot](alabaster_family.png)

## What our users [are saying](https://marketplace.visualstudio.com/items?itemName=tonsky.theme-alabaster&ssr=false#review-details)?

> It's like I had this weight on my eyes, and now it's gone. Awesome!

– Alex Sugak ★★★★★

> After your theme others looks like unreadable neon things 🤯

– lamartire ★★★★★

> Minimalistic cool

– denisgrib ★★★★★

> Super minimal and undistracting. Easy to read.

– Josh Bernitt ★★★★★

> A little bit confusing at first if you're from The Dark Land. But then you just chill.

– aenor.realm ★★★★★

## Installation

Both schemes are packed in the same package.

### Via Package Control

First, install Alabaster via Package Control:

1. `Tools` → `Command Palette...` → `Package Control: Install Package`
2. Select `Alabaster Color Scheme` and press Enter.

Then, enable it:

3. Select `Preferences → Color Scheme ...`
4. Pick `Auto`, then `Alabaster` (or `Alabaster BG`) for light variant and `Alabaster Dark` for dark variant.

## Variations

- for Visual Studio Code [tonsky/vscode-theme-alabaster](https://github.com/tonsky/vscode-theme-alabaster)
- for Vim [agudulin/vim-colors-alabaster](https://github.com/agudulin/vim-colors-alabaster)
- for NeoVim [p00f/alabaster.nvim](https://git.sr.ht/~p00f/alabaster.nvim)
- for JetBrains IDEs (IntelliJ IDEA etc) [tonsky/intellij-alabaster](https://github.com/tonsky/intellij-alabaster)
- for Sublime Text 2 (unofficial) [freetonik/Travertine](https://github.com/freetonik/Travertine)
- Dark for Visual Studio Code [apust/vscode-rubber-theme](https://github.com/apust/vscode-rubber-theme)
- for LigthTable [tonsky/alabaster-lighttable-skin](https://github.com/tonsky/alabaster-lighttable-skin)
- for [CudaText](https://sourceforge.net/projects/cudatext/files/addons/themes/theme.Alabaster.zip/download)
- for Windows Terminal [awbv/Windows-Terminal-Alabaster-Scheme](https://github.com/awbv/Windows-Terminal-Alabaster-Scheme)
- for Xresources [anmolmathias/xresources-alabaster](https://github.com/anmolmathias/xresources-alabaster)
- for iTerm2 [mkaschenko/iterm2-theme-alabaster](https://github.com/mkaschenko/iterm2-theme-alabaster)
- for Emacs [uzhne/alabaster-emacs](https://github.com/uzhne/alabaster-emacs/blob/master/alabaster-theme.el)
- for Android Studio [chrisetheridge/alabaster-android](https://github.com/chrisetheridge/alabaster-android)
- for Kitty Terminal [anmolmathias/kitty-alabaster](https://github.com/anmolmathias/kitty-alabaster)
- for Warp Terminal [arsenydubrovin/warp-alabaster-theme](https://github.com/arsenydubrovin/warp-alabaster-theme)
- for Zed [tsimoshka/zed-theme-alabaster](https://github.com/tsimoshka/zed-theme-alabaster)

## See also

[Writer Color Scheme](https://github.com/tonsky/sublime-scheme-writer): minimal color scheme for long-term writing.

[Profile Switcher](https://github.com/tonsky/sublime-profiles): Switch quickly between writing and coding profiles.

[Fira Code](https://github.com/tonsky/FiraCode/): Best coding font in the world.

## Credits

Made by [Niki Tonsky](https://twitter.com/nikitonsky).

## License

[MIT License](./LICENSE.txt)
