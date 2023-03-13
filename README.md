# Try out the new `webR`

I just read about `webR` and found the quarto extension `quarto-webr` that enables it.
Awesome!
Let's try it out.
You can see the result [here](https://szeller42.github.io/try-webr/example.html).

## Setting it up

To install `quarto-webr`, I ran the following in the terminal:

    quarto install extension coatless/quarto-webr
    
## Using `webR` in the `qmd`-document

Then, in the `yaml`-header, add

    filters:
      - webr

I don't have a current python library installed, so the syntax is just slightly different.
You don't use curly braces: instead of

\`\`\``{webr}`,

it is

\`\`\``webr`.
