# bin2dec 

This is an atempt to create a base converter using [React](https://github.com/facebook/react). It's inspired by another project called [app-ideas](https://github.com/florinpop17/app-ideas), which suggest some creative ideas of apps to practice new skills/technology's instead the good old "to do list". The original idea is to make a simple binary to decimal translator, however, I decided to make something like a google translate for number and their number bases.

## Preview

Expected result (To be honest, have some details that I didn't decided yet)

### When the user enter in the page

<img src='./bin2dec-print1.png'  height='350'>&nbsp;<img src='./bin2dec-mobile1.png' height='350'>

### In use

<img src='./bin2dec-print2.png'  height='350'>&nbsp;<img src='./bin2dec-mobile2.png' height='350'>

## Getting started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Requirements

- [Node.js](https://nodejs.org/en)
- [React](https://reactjs.org/)
- [React Media](https://github.com/ReactTraining/react-media)
```$ npm install react-media```
- [React Router](https://reactrouter.com/web/guides/quick-start)
```$ npm install react-router-dom```

### Installing

First, in the terminal, enter in the project folder and type

```$ git clone https://github.com/raissonsouto/bin2dec.git```

Than enter in the directory created

```$ cd bin2dec```

And install the dependencies

```$ npm install```

Finally, run the app

```$ npm start```

## Features

### Already Running

- Translate
- bases selector

### Working on

- dynamic textarea
- Mobile version

### Future features

- Translate v2.0
- A step by step to show the translation process
- bin2bin (In bin2dec, the program translate a number in some base to the same number but in another base. In bin2bin (I didn't find in a better name), the idea is to translate this binary to another binary represetation (like two's complement, excess-128, etc))

# bugs

- This isn't an actual bug, but is something that I doubt. I don't know if it's better change the input value when the user change the input base or if I keep the typed value
- mobile: infinite width and 2x height
- mobile: base selector behind the input box

## Author

- **Raisson Souto**

## Acknowledgement

- [app-ideas](https://github.com/florinpop17/app-ideas)

