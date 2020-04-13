# Solarized-light + `syntax off`
Warm and minimal colourscheme like beelzebub.

For Emacs version look at [peregrinator/solarizedless.el](https://gitlab.com/peregrinator/solarizedless.el)

>> TODO: ![](screenshots/mephistopheles-dark.png)

## Installation

With VimPlug:

```vim
Plug 'peregrinator/vim-solarizedless'
```

Or just throw solarizedlesss.vim in your colors directory.

## Usage

```vim
set background=light
colorscheme solarizedless
```

## Settings
```vim
" You can adjust colors you want like this:
let g:solarizedless_bg="233"
let g:solarizedless_fg="250"
let g:solarizedless_mute="60"

" Add color noises for syntax highlightning:
let g:solarizedless_syntax_mute=1

" And make parts of it bold:
let g:solarizedless_syntax_bold=1

" Then set light variant of colorscheme
set background=light
colorscheme solarizedless

" And ask yourself: "What have I done?!"
```

## Inspired by
...a bunch of great emacs monochrome themes, [nofrils](https://github.com/robertmeta/nofrils) and :SYNTAX OFF discussions on the internet.

