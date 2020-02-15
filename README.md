This porting makes blackboard no longer rely on color-theme package,
since Emacs has it's theme mechanism from Emacs 24.

### How to use:

This is a fork of don9z/blackboard-theme which has been customized only
so far as to change the background colour to what I remember as an elementry
school student in the mid 60s growing up in Galveston Texas...  

Between my second and fourth grades, I attended Sam Houston Elementry School, _a beautiful Victorian age school building constructed mostly of quarried stone, sadly long since demolished..._  

The blackboards in the classrooms were wall to wall, constructed of pure high quality quarried polished slate which had a deep dark eggplant color _(almost completely black, but when the sun came in from the side through the large classroom windows you could see, sense, an eggplant indigo/purple glow about it)_ 

The `RGB` value for this colour hovers between `0x100018` and `0x200028`... _(depending on the average brightness/contrast of the display screen it is rendered on)_.

I love this colour as it sets a nice pedagogical background mood for me while I work... Childhood memories aside, there is something magical about this colour! :octocat:

I have not altered anything else as all other colours and sizes etc. make total logical sense... If I do make any more alterations, they will be noted in this README.

To install this forked theme, clone this repository somewhere within your Emacs Lisp path, _(if you use **Harmonic Alchemy Modular Emacs** place your cloned `blackboard-theme` directory within `~/.emacs.d/lisp/my-modules/`)_.  In general, place it somewhere on your **Emacs load path** and follow the rest of the instructions below **_(TBC)_** to get it loaded correctly within your Emacs configuration...

> **Note:** you will not be using the standard theme from MELPA in this case...

Already in MELPA https://melpa.org/#/blackboard-theme

<del>1. First, add a local directory to custome-theme-load-path,
   `(add-to-list 'custom-theme-load-path "~/home/$USER/drop/the/theme/to")`
2. Then drop this theme into it
3. `M-x load-theme`, then choose blackboard, it should work, or, simple use `(load-theme 'blackboard t)` to enable the theme from start.</del>

![screenshot](https://github.com/harmonicalchemy/blackboard-theme/blob/master/screenshot.png?raw=true)
