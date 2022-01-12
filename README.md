# depaul-brand-consistency

There are two separate areas of focus. First, the preview page that displays the actual modules. Second, each individual modules that will get used.

As expected, running into issues with redefining simple bootstrap classnames with dpu specific classnames like 'container'. Will use dpu- prefix for those conflicts and bc- prefix for brand consistency specific classnames.

# design breaking notes against figma doc

- fonts used not consistent within the brand page itself
- unique button elements shown throughout the page
-

add photo grid, skip the nav bar for now, convert the container names

## pixel perfect

There is pixel perfect and then there's responsive. The term pixel perfect applies only to a design that is not expected to reflow and change shapes and layout. This is because of the use of relative units vs pixel units. Likewise, when creating in the design phase, a mockup does need to abide by the same rules followed by the code. Line heights have to remain uniform instead of dependent on if the word is using ascenders because browsers measure from the baseline. The same uniformity has to be applied to container margins and padding.
