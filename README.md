*This project is under active development and is not stable yet.*

## Planck.js<sup>&alpha;</sup>

Planck.js is JavaScript rewrite of Box2D physics engine for cross-platform HTML5 game development.

**[Check out demos!](http://piqnt.com/planck.js/)**

[![Car](/doc/img/screenshot.png "Play")](http://piqnt.com/planck.js/Car)

Key motivations in development of this project are:
- Taking advantage of Box2D's efforts and achievements
- Developing readable and maintainable JavaScript code
- Optimizing the library for web and mobile platforms
- Providing a JavaScrip-friendly API

### Install


### Examples

Examples can be found in [`example`](/example/) directory.


### API


### Architecture

Planck.js includes Box2D algorithms without modification and its internal architecture and external API are very similar to Box2D.
However [changes](./CHANGES.md) and refactoring are made during rewrite to address differences between C++ and JavaScript.


### Development

Install development dependencies:

    npm install
    bower install

Try examples with live build (see command-line output for URL to open):

    npm run testbed


### References

[**Box2D**](http://box2d.org/) is a popular C++ 2D rigid-body physics engine created by [Erin Catto](https://twitter.com/erin_catto). Box2D is used in several popular games, such as Angry Birds, Limbo and Crayon Physics, as well as game development tools and libraries.

[iforce2d](https://www.iforce2d.net/b2dtut/) website includes a collection of helpful tutorials and resources to learn Box2D.


### License

Planck.js is [available under the zlib license](./LICENSE.txt).