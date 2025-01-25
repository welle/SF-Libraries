# Lightning Web Component: Generic Lazy Loading Table

Generic Lightning Datable with lazy loading and sortable columns.

See "Generic Table" to view a usage of this component.

## Features:
- Read-only
- Infinite loading self managed.
- Sortable column self managed.
- Custom column types:
    - columnCustomUrl: @see columnCustomUrl LWC.
- Custom events:
    - onloaded: sent when the component is fully rendered.
    - onrowselection: sent when at least one row is selected in the table.
        * details: 
                - selectedRows: rows selected.
    - onloadmoredata: sent when the component ask for next rows.
        * details: 
            - offset:       current query offset.
            - limit:        query limit.
            - sorting:      query "Sort by".
            - mustBeReset:  the query should be reset (local data rows as well).