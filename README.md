# Animate.css Snippets for Sublime Text
A collection of snippets from [Animate.css](https://daneden.github.io/animate.css/ "Animate.css") for Sublime Text.

## Usage
In Sublime Text, enter `animatecss-` followed by an animation name as listed on  [Animate.css](https://daneden.github.io/animate.css/ "Animate.css"). Then hit the `Tab` key to generate the aniamtion code. For example:

```
animatecss-bounceOutDown
```
Will generate: 
```
@-webkit-keyframes bounceOutDown {
  0% {
    -webkit-transform: translateY(0);
    transform: translateY(0);
  }

  20% {
    opacity: 1;
    -webkit-transform: translateY(-20px);
    transform: translateY(-20px);
  }

  100% {
    opacity: 0;
    -webkit-transform: translateY(2000px);
    transform: translateY(2000px);
  }
}

...

.bounceOutDown {
  -webkit-animation-name: bounceOutDown;
  animation-name: bounceOutDown;
}
```

## Installation
The easiest method is to use [Package Control](https://sublime.wbond.net/ "Package Control").  In Sublime Text, press `Command+Shift+P` on OS X or  `Control+Shift+P` on Windows/Linux, then go to "Package Control:Install Package". Search for "Animate.css", and enter to install.

## License
Animate.css Snippets for Sublime Text is licensed under MIT. (http://opensource.org/licenses/MIT)

## Credits
- [Andrew Deniszczyc](link:http://andrewdeniszczyc.com/) - Animate.css Snippets for Sublime Text
- [Daniel Eden](link:http://daneden.me/) - [Animate.css](https://daneden.github.io/animate.css/ "Animate.css")