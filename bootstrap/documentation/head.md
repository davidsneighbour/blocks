# Head Tags

Blocks sets up a common set of header tags with it's hook system to add your own content. The following are the tags 
and their individual configuration, if required:

## Base Tags

- Character encoding

    - default: `UTF-8`
    - configuration: `params.head.charset` (string)

- Viewport
    - default: `width=device-width, initial-scale=1, shrink-to-fit=no`
    - configuration: `params.head.viewport` (string)
  
- Title
    - default: `$PAGET_TITLE | $SITE_TITLE`
    - add your own title via title block into your layout file:
      ```gotemplate
      {{ define "title" }}
         My own title
      {{ end }}
      ```
    - TBD: make title layout and content configurable 

- ###
  - default: `###`
  - configuration: `params.head.###` (string)

## Special Tags


## Hooks

- head-init (after head start tag, used only for setup, not output)
- head-start (after charset, viewport and title)
- head-end (before the head end tag)

## Open Search

Blocks uses [DNB Hugo Components / OpenSearch](https://github.com/dnb-org/components/tree/main/opensearch) to add 
open search specifications to the website. 


