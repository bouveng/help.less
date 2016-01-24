# help.less
CSS authoring tool that provides live DOM annotations for defined css patterns.

```
/* syntax rules */
.grid > .grid {
    .annotation('!','WARNING 2X nested GRID - Please do consider .grid-cell instead. <a href="#">Styleguide Grid System section 4.2</a>');
}
```