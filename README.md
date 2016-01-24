# help.less
CSS authoring tool that provides live DOM annotations for defined css patterns.

```Less
/* syntax rules */
.grid > .grid {
    .annotation('!','WARNING 2X nested .GRID - Please do consider .grid-cell instead.
                     See <a href="/styleguide/#4.2">Styleguide Grid System section 4.2</a>');
}
```