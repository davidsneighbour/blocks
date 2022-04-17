## Hooks

@davidsneighbour/blocks uses [layout hooks](https://github.com/davidsneighbour/hugo-hooks) so theme developers can add easily extendable theme hooks. 

| Hook |  | Notes |
| --- | --- | --- |
| **buildup** | [1][2] |  |
| **setup** | [2] |  |
| **head-start** |  | right after the opening `head` tag |
| **head-end** |  | right before the closing `head` tag |
| **body-start** |  | right after the opening `body` tag |
| **container-start** |  | right after the outer container of the main content layout |
| **content-start** |  | inside the content column at the top |
| **content-end** |  | inside the content column at the bottom |
| **sidebar-start** |  | inside the sidebar column at the top |
| **sidebar-end** |  | inside the sidebar column at the bottom |
| **container-end** |  | right before the outer container of the main content layout |
| **body-end** |  | right before the closing `body` tag |
| **teardown** | [2] |  |

[1] This hook has layouts defined within the blocks module. If a submodule or the site wishes to override functionality at this location then the existing code needs to be copied or applied to that hook.

[2] This hook is outside of the HTML structure and should only be used for 
