# Visual Mode for Vim
Vim editor has something known as Visual Mode and it's really freakin useful. It basically gives you the capability to cut, copy and paste in Vim.

## Commands and Key Combinations

### Activating Visual Mode
When in Vim editor, press ```esc``` to make sure you are in 'Normal Mode'. Then press ```v``` to go into Visual Mode. A display at the bottom of the screen will confirm whether you are actually in Visual Mode or not.

### Selecting Text
Once you're in Visual Mode, press the ```up```, ```down```, ```right``` or ```left``` keys to move the cursor. You will see that the text gets highlighted. Once you have finished selecting your text, you are now ready to cut, copy or paste.

### Copying Text
Once the text has been highlighted, press ```y``` to copy or yank, as vim users like to term it, the text.

### Pasting Text
Once the text has been highlighted, press ```d``` to cut the text.

### Cutting Text
Once the text has been highlighted and then cut or yanked, press ```p``` to paste the text.

## Things To Note
* Assuming you've cut or yanked text, once you exit Vim, you can't enter Vim again and then paste the text. Once you've left the editor, the clipboard with the copied/cut text is cleared.
* Again, assuming you've cut or yanked text, if you delete text using the ```dd``` (delete a line) or ```d``` (delete a character) commands, then you cannot paste the text which was cut or yanked. Don't ask me why, that's just the way it is.
