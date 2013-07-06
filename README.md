Playing with Functional Javascript
==================================

This is the repository to contain all the code I'm using while reading [__Functional Javascript__](http://shop.oreilly.com/product/0636920028857.do) by [@fogus](https://twitter.com/fogus).

###The Setup

Due to lazyiness, this is the best setup I've seen so far (assuming [Node.js](http://nodejs.org/) and Ruby is installed) is installed).

1. Install underscore via `npm`:

	`npm install underscore`

2. Install `guard` and `guard-shell`:

	`gem install guard`

	`gem install guard-shell`

3. Place a file called `Guardfile` (a sample is provided) in the same directory as your project. 

Use split panes. Half will be your code, and run `guard` in the directory of your project on the other pane.

Here's how it looks like on my terminal:

![ScreenShot](http://i42.tinypic.com/ja8ff5.jpg)

###Enjoy!

Now, everytime you save your code, the result will be outputted in the next pane. 

Super sweet.

