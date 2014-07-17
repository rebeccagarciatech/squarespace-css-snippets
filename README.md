Squarespace CSS Snippets
========================
Here are some CSS hacks you can use without having to use Javascript to change Squarespace elements.


## Heart 'Like' Icon 
### display heart like icon & text inline
```css
.sqs-simple-like.clicked .like-icon, .sqs-simple-like:hover .like-icon {
	display: inline-block;
}
```

### change the hover & clicked color of heart like icon
```css
.sqs-simple-like.clicked .like-icon, .sqs-simple-like:hover .like-icon {
	background-color: #000;
}
```

## Forms

### hide required asterisk
```css
.required span {
	display: none;
}
```

### change form input text
```css
.form-wrapper .field-list .field .field-element {

}
```

### change blog RSS text
```css
.social-rss { 
}
```

### change font color of date on blog page
```css
time.published a:link {
color: #000;
}

.entry-footer a, .entry-footer .sqs-simple-like, .entry-footer .squarespace-social-buttons {
color: #000;
}
```
source: http://answers.squarespace.com/questions/48393/how-do-i-change-the-font-color-of-the-date-on-my-blog-page

Feel free to contribute!

Credits
========

Created by Rebecca Garcia ([@geekgirlweb](http://twitter.com/geekgirlweb)) I'm a Developer Evangelist at [Squarespace](http://squarespace.com) :)