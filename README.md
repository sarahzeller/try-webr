# Try out the new `webR`

I just read about `webR` and found the quarto extension `quarto-webr` that enables it. 
Awesome!
Let's try it out.

## Setting it up

To install `quarto-webr`, I ran the following in the terminal:

```
quarto install extension coatless/quarto-webr
```

Then, in the `yaml`-header, add 

```
filters:
  - webr
```

I don't have a current python library installed, so the syntax is just slightly different.
You don't use curly braces: instead of

````{webr}`,

it is 

````webr`.
