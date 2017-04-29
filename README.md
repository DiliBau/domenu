[![](https://github.com/mechanicious/domenu/blob/gh-pages/logo-domenu.png?raw=true)](http://mechanicious.github.io/domenu/) doMenu

Specialized version of Nestable plugin, for back-end hierahical menu creation. 

--

### Installation
Bower: `bower install domenu`

NPM: `npm install domenu`

--

### Fork changes
This fork exposes the `createNewListItem` function on the `PublicPlugin` object. Please read the [documentation](http://mechanicious.github.io/domenu/) for more details about `PublicPlugin`.
The `createNewListItem` is used to dynamically add a menu item without having to click the add button. It accepts an object to fill the data fields of the list item.

Usage:
```
$('#domenu-0').domenu().createNewListItem({title: 'Item 02', id: 324});
```

### Official Documentation
You can find documentation for this project on [doMenu website](http://mechanicious.github.io/domenu/) or browse through the branches to find out about the earlier versions.

--

### Feedback

Are you having any suggestions, awesome ideas, or just would like to share what you think? Leave [Feedback](https://github.com/mechanicious/domenu/labels/feedback)!

--

### License & Credits
Copyright © 2016 Mateusz Zawartka | BSD & MIT license

Built upon Nestable from [David Bushell](http://dbushell.com/)

--

<a href='https://pledgie.com/campaigns/31198'><img alt='Click here to lend your support to: doMenu Donations and make a donation at pledgie.com !' src='https://pledgie.com/campaigns/31198.png?skin_name=chrome' border='0' ></a>

