## CSS Display Property

## `Defination`

The display property in css is have multiple roles, like how a container looks like and it's children.

### Syntax

```css
selector {
  display: value;
}
```

### How many types of display exists in css

In css have multiple display types now days popular are `flex` and `grid`, and called flexbox layout. [Learn more](https://css-tricks.com/almanac/properties/d/display/) about display property.

```css
.container {
  /* <display-outer> (its natural flow). */
  display: block;
  display: inline;

  /* <display-inner> (its contents) */
  display: flex;
  display: flow-root;
  display: grid;
  display: table;
  display: ruby; /* experimental */

  /* <display-listitem> (generates a content box and an inline list-item box) */
  display: list-tem;
  display: inline list-tem;

  /* <display-internal> (defines table and ruby layouts) */
  display: table-row-group;
  display: table-header-group;
  display: table-footer-group;
  display: table-row;
  display: table-cell;
  display: table-column-group;
  display: table-column;
  display: table-caption;
  display: ruby-base; /* experimental */
  display: ruby-text; /* experimental */
  display: ruby-base-container; /* experimental */
  display: ruby-text-container; /* experimental */

  /* <display-box> (determines whether to display a box or not) */
  display: contents;
  display: none;

  /* <display-legacy> (CSS2 single-keyword syntax) */
  display: inline-block;
  display: inline-flex;
  display: inline-grid;
  display: inline-table;

  /* Two-value examples */
  display: block flow;
  display: inline flow;
  display: inline flow-root;
  display: block flex;
  display: inline flex;
  display: block grid;
  display: inline grid;
  display: block flow-root;

  /* Global values */
  display: inherit;
  display: initial;
  display: revert;
  display: unset;
}
```

## Visulize flexbox from the source

Now days developers used CSS3 and it have some new features like `flexbox` and `grid` for building complex layouts.

- [Display Flex](https://flexbox.malven.co/)
- [Display Grid](https://grid.malven.co/)
