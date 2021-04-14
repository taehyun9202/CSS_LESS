# CSS_LESS

## less css compiler practice

## install dependencies
npm i -g less

mpn i -g less-watch-compiler


## getting started

add following in less-watch-compiler.config.json file
```
{
    "allowedExtensions": [".less"],
    "minified": false,
    "sourceMap": false,
    "watchFolder": "less",
    "outputFolder": "css"
}
```

run **less-watch-compiler less css** in command line

find .less file im less folder and compile to css folder
