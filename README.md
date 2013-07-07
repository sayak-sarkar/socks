# Socks

The presentation tool for [Shoes](http://shoesrb.com). Socks has a simple JSON based declarative syntax like CSS that is very easy to understand and write in. Hence you can cook up a presentation in a few minutes. Socks will use Shoes to convert that to a presentation automatically.

## Presentations

Here is how it would look if you used the `example.json` file with Socks.

![Screen 1](http://i.imgur.com/K07pqNY.jpg)
![Screen 2](http://i.imgur.com/ZHzc8V7.jpg)
![Screen 3](http://i.imgur.com/j8eE2aL.jpg)

## Using Socks

To use Socks you need to have the Ruby and Ruby-devel packages pre-installed in your computer. Also, since Socks is based on Green Shoes, you need to have the Green Shoes gem installed prior to using Socks.

### Installing the dependencies:
Here's a list of installation steps to get [Ruby](http://www.ruby-lang.org/en/), [Ruby-Devel](http://rpm.pbone.net/index.php3/stat/3/srodzaj/1/search/ruby-devel) and [Green Shoes](http://ashbb.github.io/green_shoes/) setup:-

#### For Fedora:
 * Installing Ruby and Ruby-devel: ```sudo yum install ruby ruby-devel```
 * Installing Green Shoes: ```gem install green_shoes```

#### For Debian/Ubuntu:
 * Installing Ruby and Ruby-devel: ```sudo apt-get install ruby ruby-devel```
 * Installing Green Shoes: ```gem install green_shoes```

#### For OpenSuse:
 * Installing Ruby and Ruby-devel: ```sudo zypper install ruby ruby-devel```
 * Installing Green Shoes: ```gem install green_shoes```

### Getting Socks:
 * Clone the repository to your computer: ```git clone https://github.com/sankha93/socks.git```
                                       __OR__
 * Download the zipped package from this link: https://github.com/sankha93/socks/archive/master.zip

### Running your Presentations
 1. Create your presentations in the JSON format shown in the ___example.json___ file.
 2. Run ___socks.rb___: ```ruby socks.rb <your-file-name>.json```

## Yee Haw!

That was just to grab you attention. The implementation of Socks is still incomplete and I am working on it. Any kind of help is appreciated. Just fork this repo, hack on it, and send me a pull request!
