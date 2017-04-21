# @data-ui/data-table

Performant table components that can handle a lot of data.
Wraps [react-virtualized](https://github.com/bvaughn/react-virtualized) and provides a lot
of HOC wrappers for flexibility.

## Styles
This library doesn't override any styles or classnames from the base `react-virtualized` libray,
which you can read more about
[here](https://github.com/bvaughn/react-virtualized/blob/master/docs/customizingStyles.md).

For convenience the base `react-virtualized` stylesheet is coppied for import with the
appropriate loader via
* `import '@data-ui/data-table/styles.css';`

Alternatively you can pass table, header, row classNames or style objects to the wrapped <Table/> component.

## Development
* `npm install`
* `npm run dev|prod`

## @data-ui packages
- --> @data-ui/data-table
- [@data-ui/demo](https://github.com/williaster/data-ui/tree/master/packages/demo)