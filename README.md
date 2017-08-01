# karma-starter-pack
This is literally the result of performing the following commands (some of which are interactive):

On windows:
```
npm init
npm install --save-dev karma karma-jasmine karma-phantomjs-launcher jasmine-core
node_modules\.bin\karma init

```

On *nix:
```
npm init
npm install --save-dev karma karma-jasmine karma-phantomjs-launcher jasmine-core
./node_modules/.bin/karma init

```

## Interactive commands
### `npm init`

Mostly you can just press enter on every question. To save time later, you can set up 
the `test command` at the init phase: type in:
`karma start`

### `karma init`
Q: Which testing framework do you want to use?  
A: `jasmine` (default)  

Q: Do you want to use Require.js  
A: `no`  

Q: Do you want to capture any browsers automatically?
A: `PhantomJS` followed by an empty line (use `tab` to select)

Q: What is the location of your source ant test files?  
A: `src/**/*.js`  
   `test/**/**.spec.js`  

_(ignore warnings about no files matching the given pattern -- they will come!)_  

Q: Should any of the files included by the previos patterns be excluded ?
A: (leave blank for none)  

Q: Do you want Karma to watch all the files and run the tests on change ?  
A: `yes`