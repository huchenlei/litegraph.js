
# 1. Unit Testing and Debugging

GL is getting close?
Done up to L3967, gltextures.js
24 problems in lint
Expand on Jest testing to run tests for each class, both in core and in src/nodes/

# 2. Documentation

Set up JSDocs comments for LGraphNode, LLink, LGraphCanvas even if their program is broken.

# 3. Fix Layout Errors (width/height/font/top/left)

Removed ones for context menu.  Others likely on lgraphcanvas, editor, code, etc.

# Examine Issues in old repo, changes from Atlasan

https://github.com/jagenjo/litegraph.js/issues
https://github.com/atlasan/litegraph.js

# Extend classes with a *Canvas class

Shift render related methods and properties to that.