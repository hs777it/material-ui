List
====

A simple list component.

Props
-----

| Name | Type | Default | Description |
|:-----|:-----|:--------|:------------|
| children | node |  |  |
| className | string |  | The CSS class name of the root element. |
| component | union:&nbsp;string<br>&nbsp;func<br> | 'div' | The component used for the root node. Either a string to use a DOM element or a ReactElement. |
| padding | bool | true |  |
| subheader | node |  |  |

Any other properties supplied will be spread to the root element.