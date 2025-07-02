
#shortcuts to remember

npm init -y  <---> creates a package.json file

npm i -D tailwindcss <---> creates a node_module folder with your tailwind dependencies 

npm run build <---> builds the tailwind file into the specified cs file path (which I set up in my package.json)

``` 
 "scripts": {
    "build": "tailwindcss -i ./input.css -o ./css/main.css",
    "watch": "tailwindcss -i ./input.css -o ./css/main.css --watch"
  }
```

``` "build": "tailwindcss -i ./input.css -o ./css/main.css", ``` compile the -i (input) and then -o (output) that's compiled into /css/main.css

