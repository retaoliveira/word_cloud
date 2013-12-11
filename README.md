word_cloud
==========

A little word cloud generator in Python. Read more about it on the [blog
post][blog-post].

## Installation

Get this package:
    
    wget https://github.com/paul-nechifor/word_cloud/archive/master.zip
    unzip master.zip
    rm master.zip
    cd word_cloud-master

Install it:

    sudo pip install -r requirements.txt
    sudo python setup

## Examples

Note that if you are not on Ubuntu, you need to adjust FONT_PATH to point to
some existing font.

Check out [examples/simple.py][simple] for a short intro. A sample output is:

![Constitution](examples/constitution.png)

Or run [examples/more.py][more] to see more options.

## Used in

### Reddit Cloud

[Reddit Cloud][reddit-cloud] is a Reddit bot which generates word clouds for
comments in submissions and user histories. You can see it being operated on
[/u/WordCloudBot2][wc2] ([top posting][wc2top]).

![A Reddit Cloud sample](http://i.imgur.com/tcbZnKW.png)

### <other>

*Send a pull request to add yours here.*

## Issues

Using Pillow instead of PIL might might get you the [`TypeError: 'int' object is
not iterable` problem][intprob] also showcased on the blog.

[blog-post]: http://peekaboo-vision.blogspot.de/2012/11/a-wordcloud-in-python.html
[simple]: examples/simple.py
[simple]: examples/more.py
[reddit-cloud]: https://github.com/paul-nechifor/reddit-cloud
[wc2]: http://www.reddit.com/user/WordCloudBot2
[wc2top]: http://www.reddit.com/user/WordCloudBot2/?sort=top
[intprob]: http://peekaboo-vision.blogspot.de/2012/11/a-wordcloud-in-python.html#bc_0_28B

