Developed a page navigator component. Using this component, we will be able to retrieve and show a set of records page by page, rather than fetching all records once. High usability and high reusability of the component are very important.
The component is designed such that it can receive the following parameters as its properties:
- dataGrid: The grid which it will be aligned to.
- DatabaseName: The target database
- TableName: Name of a table in database from which it is going to select
- rowsPerPage: No. of rows for being shown in each page of the grid
- pageNo: No. of the current page, i.e.; the page which we want to load.

The developed component is able to handle simple queries.
