# Recipe for Banana Crumb Muffins

This is [the recipe for Banana Crumb Muffins](http://allrecipes.com/recipe/17652/banana-crumb-muffins/), laid out as a Git repository.
Just for fun.

> [!NOTE]
> The git graph below should be read from bottom to top (because that's how the git client I used for this screenshot shows git graphs)
>
> Regardless, the core idea stands that representing recipes as a graph—with separate branches per recipient merging when they should be mixed together—rather than linear instructions could be useful idea to entertain 😉


![git graph](git-graph.png)

* Each commit represent a step in the recipe.
* Each commit contain one file per ingredient that needs to be added to the recipe.
* A branch represent a bowl or any container, so everything that happens on a given branch is done in the same bowl.
* When branches merge, this means that you should put the content of one bowl into another.

----

![recipe-photo](Banana%20Crumb%20Muffins.jpg)
