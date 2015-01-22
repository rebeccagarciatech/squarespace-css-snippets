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

## Header
### Hide site title
```css
.site-title { display:none; }
```

## Navigation
### Hide site navigation in Momentum
```html
<style>
header#header {
display: none;
}
</style>
```
source: http://answers.squarespace.com/questions/51860/removing-site-navigation-in-momentum/51914

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

## Newsletter

### lengthen form fields in newsletter block
```css
.newsletter-block .newsletter-form-field-element {
	width: 240px;
}
```
source: http://answers.squarespace.com/questions/48176/how-do-you-lengthen-the-email-address-field-in-a-newsletter-block?page=1#48182

## Blog

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

### change size of tag cloud 
```css
.tagcloud-block .name {font-size: 70% !important;
}
```

### change color of tag cloud
```css
.tagcloud-block .name {color: blue !important;
}
```
source: http://answers.squarespace.com/questions/47640/how-do-i-change-the-text-size-in-a-tag-cloud

Feel free to contribute!

Credits
========

Created by Rebecca Garcia ([@geekgirlweb](http://twitter.com/geekgirlweb)) I'm a Developer Evangelist at [Squarespace](http://squarespace.com) :)