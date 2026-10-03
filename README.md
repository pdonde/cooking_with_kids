# Cooking With Toddler

Picture-by-picture cooking games for little kids. Each recipe is one self-contained HTML page with animations, sound effects and a spoken voice.

Live site: https://pdonde.github.io/cooking_with_kids/

## Recipes
- [Noodle Kitchen](noodles/index.html): 16 steps, from washing hands to eating
- [Pancake Kitchen](pancake/index.html): 16 steps of fluffy banana pancakes
- [Egg Sandwich Kitchen](egg%20sandwich/index.html): 17 steps, a fried egg and cheese sandwich toasted in a panini maker (mayo, tomato and ketchup are optional)

## Adding a recipe
1. Make a folder for it, e.g. `pancake/`, and put the game in it as `index.html`.
2. In the game page, keep a back link: `<a href="../index.html">← All recipes</a>`.
3. Add one entry to the `RECIPES` list near the bottom of the top-level `index.html`.
4. Commit and push. GitHub Pages updates in a minute or two.
