![](logo.png?raw=true)

Auto generated documentation (Alpha)

Functionality so far:

Generates a tree folder structure in node, that is rendered as a treegrid in the browser. Click on a file (non-root level) to populate main view.

Coming soon:

Generates a documentation guide including function names and parameters, function dependencies, and more. Initially compatible with jQuery and plain JavaScript function namespacing, soon to be compatible with React, Redux, Angular 1, Angular 2 and other frameworks on request.

Usage

node agd relativePath

e.g. node agd '../../'

Generated code.json.

Run 'node http-server' then open the browser to view the file structure rendered in the sidebar. Larger projects can take up to a minute or two to render.

See code.json for example generated data.

To-do: Add code content for top level files. Move tree html generation into node.

Contact html5css3@outlook.com

MIT License

Example generated tree structure

![](tree.png?raw=true)

