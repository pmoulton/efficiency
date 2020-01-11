
# Efficiency
Efficiency tips for human–computer interaction

### Principles
This guide prioritizes avoiding mouse usage and minimizing keystrokes while using standard peripherals.

VIM style arrow movement is utilized to avoid shifting hands to the arrow keys.

### MacOS recommendations

1. __[Alfred](https://www.alfredapp.com/)__
	* Alfred provides fast access to common operations
	* Shortcuts are accessible by `CMD + space` and typing the prefix of the command
		* Website bookmarks `bookmark_name`
		* Opening applications `chrome`
		* Opening files `open filename.ext`
		* Sleeping the computer `sleep`

	* Website bookmarks
	* Typing the prefix and hitting enter will open a new tab with the webpage
	* Unique abbreviations will usually only require two characters to match
		* `wchat` for workchat
		* `dpmoulton` for @pmoulton diffs
		* `tpmoulton` for @pmoulton tasks
		* `dqueue` for my diff queue
2. __[Divvy](https://mizage.com/divvy/)__
	* Divvy enables fast window resizing with a single hotkey of your choice
	* The following commands are user configurable
	* Shortcuts are accessible by `CMD + E` and typing the command
		* `space` snap a window to full screen
		* `w` snap a window to the center (with padding)
		* `h` snap a window to the left half
		* `j` snap a window to the bottom half
		* `k` snap a window to the bottom half
		* `l` snap a window to the right half
		* `o` snap a window to the top right quarter
		* `u` snap a window to the top left quarter
		* `m` snap a window to the bottom right quarter
		* `n` snap a window to the bottom left quarter


3. __Mission control space switching__
> Note: `⌃` denotes control
* See: [pmoulton/keyboard](https://github.com/pmoulton/keyboard) for capslock to control/esc mod
* `⌃H` move one space left
* `⌃L` move one space right

### Programming
The following is more helpful if you use command line tools but it may still be insightful otherwise.

1. __Vi mode for terminal__
	* `set -o vi` enables vi mode for your shell
	* This enables you to hop into visual mode to edit your current input line and much more
	* Add this command to the bottom of your ~/.bashrc file to enable by default

[//]: # (TODO: Mosh)
[//]: # (TODO: Tmux)
[//]: # (TODO: Terminal alias)
