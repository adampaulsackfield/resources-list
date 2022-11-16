# VSCode

## Shortcuts

- In VSCode if you select a word that you want to wrap in something, like quotes, brackets, etc. Then you can just highlight something and press the squarebracket or whatever you want to wrap it in.
- `option` - While holding the option key you can select multiple cursors and type multiple lines at the same time. So if you're adding a class to multiple divs then you can do it all in one go.
- `option + command` + `up or down arrow` - Same as above but will insert new cursors above. Only works if same formatting on each line really.
- `command + d` - This is very useful as it will select the next instance of whatever you have highlighted.
- `command + f` - Find. Very useful feature is find and replace. Say you want to change all instances of a class called `headerListItem`. You could open find and in the replace part put what you want to change it to and then click replace all.
- `command + b` - Toggle the sidebar open / closed.
- `control + shift + backtick` - Open the intergrated terminal.
- `command + p` - Searches in current project, so `command + p` then start typing a file name and press enter to open it.
- `command + shift + p` - Command palette to run installed commands.
- `command + l` quickly followed by `command + o` - Will open live server for the current file.

## Extensions

- [Arrow Function Snippets](https://marketplace.visualstudio.com/items?itemName=deinsoftware.arrow-function-snippets&ssr=false#overview) - Nice little snippet for creating arrow functions (`af` becomes `() =>`) and (`afa` becomes `(arg) =>`).
- [Auto Rename Tag](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-rename-tag&ssr=false#overview) - When renaming an HTML tag, this extension will also renamde the corrosponding closing tag.
- [Better Comments](https://github.com/aaron-bond/better-comments.git) - Highlights TODO and FIXME with a background colour. Also changes colour with `!` for red, `*` for green, and `?` for blue comments. Easier to notice them.
- [Code Time](https://marketplace.visualstudio.com/items?itemName=softwaredotcom.swdc-vscode&ssr=false#overview) - Track your time spent in VSCode.
- [Prettier](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode&ssr=false#overview) - Code formatting.
- [Todo Tree](https://github.com/Gruntfuggly/todo-tree.git) - Searches the current project for any comments containting TODO and FIXME. It then shows you list of each and the file it is in.
- [TailWindCSS IntelliSense](https://github.com/tailwindlabs/tailwindcss-intellisense) - Autocompletion for all TailWindCSS classes.

## Emmet

Emmet is great for the helping you complete HTML & CSS very quickly. Type your shortcut then press `tab`. The cursor will then be placed where you would logically be about to type.

---

### Examples HTML

- `article.price` outputs:

```html
<article class="price"></article>
```

- `header#profile` outputs:

```html
<header id="profile"></header>
```

You can get pretty crazy with these:

- `div.header-navigation>header+nav` will output the following:

```html
<div class="header-navigation">
	<header></header>
	<nav></nav>
</div>
```

- `ul>li.list-item*6` will output the following:

```html
<ul>
	<li class="list-item"></li>
	<li class="list-item"></li>
	<li class="list-item"></li>
	<li class="list-item"></li>
	<li class="list-item"></li>
	<li class="list-item"></li>
</ul>
```

### Examples CSS

- `tac` outputs

```css
text-align: center;
```

- `mt`outputs

```css
margin-top: ;
```

## Shortcut Examples

**Option / ALT + Click**
![GIF showing command](https://github.com/adampaulsackfield/resources-list/blob/main/images/optionclick.gif)

**Command / Control + D**
![GIF showing command](https://github.com/adampaulsackfield/resources-list/blob/main/images//commandd.gif)

**Command + Option + Arrow**
![GIF showing command](https://github.com/adampaulsackfield/resources-list/blob/main/images//optioncommandarrow.gif)
