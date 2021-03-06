# rofi-shortcuts
The ultimate shortcuts cheatsheet.

Dependencies
==========

  * rofi

How to use
==========
Just attach the script to a keyboard shortcut.

**Example for I3WM**

    cp ./rofi-shortcuts ~/.config/rofi
    bindsym $mod+ctrl+s exec "$(cat ~/.config/rofi/rofi-shortcuts/rofi-shortcuts.conf | rofi -i -dmenu -p "shortcuts")"

Table of contents
==========
* V I M
  - M o v e m e n t.
  - I n s e r t  m o d e.
  - E d i t.
  - V i s u a l  m o d e.
  - V i s u a l  c o m m a n d s.
  - C u t  &  p a s t e.
  - S e a r c h  &  r e p l a c e.
  - S e a r c h  m u l t i - f i l e.
  - E x i t.
  - M u l t i  f i l e   (b u f f e r s).
  - T a b s.
  - C o m m a n d  L i n e.
  - P l u g i n s.
* S U B L I M E
* I 3 W M
  - B a s e.
  - U t i l i t i e s.
  - M u l t i m e d i a  c o n t r o l.
* R A N G E R
  - B o o k m a r k s.
  - t a b s.
  - R a n g e r  m o v e m e n t.
  - R a n g e r  f i l e s.
  - R a n g e r  c o m m a n d s.
  - F i l e  s u b s t i t u t i n g.
  - c u s t o m.
* T I L I X
  - A p p l i c a t i o n.
  - t a b s (s e s s i o n s).
  - C o l u m n s.
  - R e s i z e  c o l u m n.
  - S e a r c h.
* T E R M I N A T O R
  - C r e a t i o n  &  d e s t r u c t i o n.
  - N a v e g a t  i o n.
  - O r g a n i z a t i o n.
  - M i s c e l a n e o u s.
  - G r o u p i n g  &  B r o a d c a s t i n g.
* F I R E F O X
  - C u r r e n t  p a g e.
  - T a b s.
  - h i s t o r y
  - B o o k m a r k s.
  - T o o l s
  - P d f 
  - M i s c
* V I M I U M C
  - V i m i u m c  n a v i g a t i o n.
  - V o m n i b a r.
  - F i n d.
  - N a v i g a t i n g  h i s t o r y.
  - T a b s.
* T H U N D E R D B I R D
* L I B R E O F F I C E
* F R A N Z
* H E X C H A T
* D I S C O R D
* R O F I

More info
==========
* These are my personal shortcuts. All of them are defaults, but feel free to edit rofi-shortcuts.conf with your own.
* Vim shortcuts include the ones from [vim ultimate config](https://github.com/amix/vimrc).

Wanna contribute?
==========
* Pull requests with default shortcuts of missing programs are welcome.

Credits
==========
* https://github.com/hackjutsu/vim-cheatsheet
* https://devhints.io/vim
* https://gist.github.com/heroheman/aba73e47443340c35526755ef79647eb

