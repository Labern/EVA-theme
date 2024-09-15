# How to use

1. Go to <code>~/.oh-my-zsh/themes</code> and add **<code>custom.zsh-theme</code>**.
2. Open <code>~/.zshrc</code> and add <code>THEME="custom"</code>.

3. To customise, go to <code>~/.oh-my-zsh/themes/custom.zsh-theme</code>.

## Building a prompt
4. Follow the instructions inside the file, such as: <code>PROMPT="%{$fg_bold[blue]%}%n: "</code> 

In this case, it will change the prompt to the user's name in blue.

## Some prompts

### Prompt elements

<code>PROMPT=""</code> dictates the leftmost prompt

<code>RPROMPT=""</code> dictates a prompt on the right

<code>%n</code> = user

<code>%~</code> = working directory

<code>%m</code> = computer

<code>#</code> = leave a comment

### Colours
<code>%{$fg_bold[blue]%}</code> — that is, <code>%{</code> opens the statements, then <code>fg_bold</code> selects the formatting (in this case, bold), and <code>[blue]</code> selects the colour. So you have: "Insert bold text of colour blue".

## Notes

You may need to use <code>chmod +x ~/.zshrc</code> to be able to access it.

Also, make sure to select a text editor you like to open the files, e.g. <code>***nano*** ~/.oh-my-zsh/themes/custom.zsh-theme</code>

This was built from the [EVA theme](https://github.com/garyblocks/eva-zsh-theme), and modified.
