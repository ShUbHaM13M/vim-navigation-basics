# Vim 'navigation' basics

Learning Vim navigation can be a valuable skill for programmers, writers, and anyone who frequently works with text. It offers a unique approach to editing and navigating text that can significantly improve your productivity and efficiency.

After learning just the basics of Vim navigation it will allow you to navigate, edit and perform commands with unparalleled speed, effortlessly moving through code or text.

You will be able to navigate and edit without constantly moving your hands away from the keyboard just to select a word or a whole paragraph.

---

> I started to explore ways to easily navigate using keyboard only when my dad brought a laptop which had a broken touchpad.
> So I looked for ways to -
>
> 1. Open/close windows,
> 2. Navigate holding the <kbd>Ctrl</kbd>,<kbd>Home</kbd>,<kbd>End</kbd>,. etc keys
> 3. Learning commands to start apps or shutdown.

---

Alright to get started you can either install vim in your operating system or you can just use an extension in Vs code which could be a good starting point and also you won't have to worry about how to exit Vim since you can just close Vs code directly.

> Installation the Vim plugin 

https://github.com/ShUbHaM13M/vim-navigation-basics/blob/master/resources/installing-vim-extension.webm

Opening a new file now you will notice the cursor is changed
And if you look at the status bar in the bottom you will notice **-- Normal --** indicating that you are currently in the normal mode
it is the default mode of Vim.
It allows you to navigate the text, copy/cut/paste characters, words and lines, but also roll-back actions, and so on.

> Normal mode cursor

![Vim Normal cursor](https://github.com/ShUbHaM13M/vim-navigation-basics/blob/master/resources/vim-normal-cursor.webp)

> Statusbar in Vs code indicating the current mode

![Vim Normal mode](https://github.com/ShUbHaM13M/vim-navigation-basics/blob/master/resources/vim-normal-mode.webp)

---

### Basic Navigation

You can use the keys:

- <kbd>h</kbd> to move left.
- <kbd>j</kbd> to move up.
- <kbd>k</kbd> to move down.
- <kbd>l</kbd> to move right.

These key presses can be combined with numbers so

- <kbd>5j</kbd> will move the cursor 5 lines down.
- <kbd>13l</kbd> will move the cursor 13 characters to the left.

Navigating around the file using these keys might feel weird at first, but once you get a hang of it you will be able to navigate much quicker.

> Navigating in Vscode using the vim key-bindings 

https://github.com/ShUbHaM13M/vim-navigation-basics/blob/master/resources/navigating-editing-file-with-vim.webm

#### Some other key bindings which makes navigating easier.

- <kbd>w</kbd> - jump by start of words
- <kbd>W</kbd> - jump by start of words ignoring punctuations **.** **;**.., etc
- <kbd>e</kbd> - jump to end of words
- <kbd>E</kbd> - jump to end of words ignoring punctuations **.** **;**.., etc
- <kbd>b</kbd> - jump backward by words
- <kbd>B</kbd> - jump backward by words ignoring punctuations **.** **;**.., etc

> Again these keystrokes can be preceded by a number so
> `2w` would jump two words ahead.

---

#### A Bit Advanced

- <kbd>0</kbd> - start of line
- <kbd>$</kbd> - end of line
- <kbd>G</kbd> - to go to the bottom of the file.
- <kbd>gg</kbd> - to go the top of the file.
- <kbd>Ctrl + d</kbd> - move down half a page.
- <kbd>Ctrl + u</kbd> - move up half a page.
- <kbd>: {num} Enter</kbd> - Go to that line number in the document.

---

If you accidentally go into **Insert** mode while having fun navigating the file using this newly learnt powers, then just press <kbd>Esc</kbd> to go back to **Normal**

That covers the basic of navigation in Vim. It may take upto a few days to get used to this new way of going through your files without using a mouse but it will make your workflow more productive and efficient.
