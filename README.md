# train
An activity to learn about writing to a database.

Using Tailwind framework. Docs can be found here: https://tailwindcss.com/docs/

Tailwind is a utility baced css framework, but with a cool twist, you can make a list of css rules into your own components. This requires tailwind to process the css using its own "directives". Sadly this makes your CSS file look like it's full of errors in the text editor. See https://tailwindcss.com/docs/extracting-components

-- "Tailwind encourages a "utility-first" workflow, where new designs are initially implemented using only utility classes to avoid premature abstraction."

# Setup and build process

Tailwind requires node v6
Run `nvm use 6` to switch

In order to build the css, you must process it with tailwind using this command:
./node_modules/.bin/tailwind build styles/main.css -c ./tailwind.js -o ./styles/output.css

Running onchange to run the tailwind command every time the main.css file changes:
`npm run watch` 

