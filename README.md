# overlay-hover-icons
Allows scalable size hover icons to be used in publisher overlays

## Instructions 

- Upload zipped files to publisher 
- Drag overlay to preferred size in overlay editor 
- In the query string input field add the url you wish the icon to link to and the type of icon you want to show.

For example:

```
url=http://www.yudu.com&type=twitter
```

If you want to make your own icons to show instead of the ones included in this repo this is possible.
- First make 2 icons, one normal and one with the preferred hover state.

- Put the new images in the img folder

- Update the style.css file and create new css for your icon.
 
So for example if a Micheal Jackson icon is required:

```
.mj {
	background-image: url('img/mj.png');	
}

.mj:hover {
	background-image: url('img/mj-hover.png');
}

```

You can test it all works in the browser by viewing:

```
index.html?url=http://www.yudu.com&type=mj
```
