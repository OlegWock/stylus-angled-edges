# Stylus Angled Edges

This is a port of [SASS Angled Edges](https://github.com/josephfusco/angled-edges) for Stylus.

![demo](https://cloud.githubusercontent.com/assets/6676674/16118929/33700404-33a7-11e6-8e94-a9ace624a41a.png)

## Usage

Copy file **angeled-edges.styl** to your project and import it

```stylus
@import 'angeled-edges'
```

Now you can use **angled-adge** mixin

```stylus
angled-edge(location, hypotenuse, fill, width=2800, height=100)
```

The main mixin creates an svg right triangle that is encoded, set as a background image of a pseudo element, and absolutely positioned.

[Demo and full documentation](https://github.com/josephfusco/angled-edges)