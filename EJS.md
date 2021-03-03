# EJS
Includes notes taken from How To USE EJS to Template Your Node Application by: Chris Sev

## EJS
### EJS stands for 'Embedded JavaScript' and is a simple templating language that allows the generation of HTML markup with plain JS.

### EJS uses a simple syntax and is is easy to install with `npm install ejs` 
### Example Tags:
- `<%` 'Scriptlet' tag, for control-flow, no output
- `<%_` ‘Whitespace Slurping’ Scriptlet tag, strips all whitespace before it
- `<%=` Outputs the value into the template (HTML escaped)
- `<%-` Outputs the unescaped value into the template
- `<%#` Comment tag, no execution, no output
- `<%%` Outputs a literal '<%'
- `%>` Plain ending tag
- `-%>` Trim-mode ('newline slurp') tag, trims following newline
- `_%>` ‘Whitespace Slurping’ ending tag, removes all whitespace after it