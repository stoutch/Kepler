# Kepler

Welcome to Kepler!

Kepler is a Ghost theme built off of the default Ghost theme, [Casper](https://github.com/TryGhost/Casper/releases). Built around large front page images and the ability to have portfolio items, Kepler is fast, responsive, and can be used in a wide variety of situations.


## Installation & Instruction

1. [Download the zip file of the latest release.](https://github.com/kevinguebert/Kepler/releases/tag/0.1.0)
2. Go to your Ghost Admin -> Settings -> General
3. Scroll to the very bottom where it says "Themes" and click "Upload a theme"
4. Drag the downloaded zip folder from step 1 to upload

### Create "Portfolio" Page

1. Create a tag called **Portfolio**
2. Add that tag to the navigation under Ghost Admin -> Settings -> Navigation
	(Note, the tag will be `../tag/portfolio`
3. Create a new post and add the tag of **Portfolio**

### Add a Featured Project

1. Create a tag called **Featured**
2. Create a new post, tag it with **Featured** - note, it looks best with an image!

### Add Social Media

1. Head over to the General section of your blog to add your Facebook and Twitter urls
2. Your website will now have the icons in the footer!

### Enable Disqus Support

1. Create your disqus account by following these instructions: [http://academy.ghost.org/adding-disqus-to-your-ghost-blog/](http://academy.ghost.org/adding-disqus-to-your-ghost-blog/)
2. Copy the `s.src` url and go to `post.hbs` and add it in the [disqus section](https://github.com/kevinguebert/Kepler/blob/master/post.hbs#L46)
3. Copy the same url and go to `default.hbs` and update the `script` url [found here](https://github.com/kevinguebert/Kepler/blob/master/default.hbs#L55)

### Enable Subscribers

1. Head over to the Labs section of your blog and at the very bottom, enable subscribers to your website.
2. Kepler automatically comes with a subscription page, so now just enjoy!

## Images

#### Homepage
![Full Screen](https://github.com/kevinguebert/Kepler/blob/gh-pages/readme/screencapture-localhost-2368-1478223420254.png?raw=true)

#### Post Page
![Post Page](https://github.com/kevinguebert/Kepler/blob/gh-pages/readme/screencapture-localhost-2368-acadia-1478223454551.png?raw=true)

#### Portfolio Page
![Portfolio Page](https://github.com/kevinguebert/Kepler/blob/gh-pages/readme/screencapture-localhost-2368-acadia-1478224097857.png?raw=true)





-----

#### Notes & Resources

This theme was built upon the original Ghost Casper theme and is a modifed version. I do not claim to have created this fully on my own and I am opening it up for others to use with no liability on myself.

MIT License

Copyright (c) 2016 Kevin Guebert

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
