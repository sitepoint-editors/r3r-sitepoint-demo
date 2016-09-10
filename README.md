# Building a Game with ReactJS and WebGL

This is demo code to accompany the SitePoint article "Building a Game with ReactJS and WebGL"

This basic example follows the [Presentational and Container Components](https://medium.com/@dan_abramov/smart-and-dumb-components-7ca2f9a7c7d0#.z4oi835if) example. The logic is managed in **GameContainer** in the `containers/` directory. The view code, game entitites, etc, live in `components/`.

The game logic is separated entirely from react and managed with the **reducer functions** in the `game-reducers/` folder.

The game state is set once per `requesetAnimationFrame` callback in `GameContainer.js`.

This project use Babel, Webpack, and ESLint for ES6 syntax, asset management and code quality tools.

## Requirements

* [Node.js](http://nodejs.org/)

## Installation Steps (if applicable)

1. Clone repo
2. Run `npm install`
3. Run `npm start`
4. Visit [http://localhost:8080/webpack-dev-server/index.html](http://localhost:8080/webpack-dev-server/index.html)

## License

The MIT License (MIT)

Copyright (c) 2016 SitePoint

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
