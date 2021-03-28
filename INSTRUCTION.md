- [x] Normal use
  `browserify ./src/main.js > ./dist/bundle.js`

- [x] With sourcemaps
  `browserify ./src/main.js > ./dist/bundle.js -d`

- [x] With tinyify
  `browserify ./src/main.js > ./dist/bundle.js --plugin tinyify`
  
- [x] With watchify
  `watchify ./src/main.js -o ./dist/bundle.js -d -v`
