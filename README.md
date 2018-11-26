# Overload

'Overload' is the working name for the new UI language that will supersede XAML for UI in Tank. The current plan is to embed the [Monaco Editor](https://microsoft.github.io/monaco-editor/) (used by Visual Studio Code) into the `UXScript` document in TED. Syntax highlighting, goto definition, and autocomplete are some of the features expected there.

## Features

This Visual Studio Code extension only supports syntax highlighting.

## Release Notes

### 0.3

- Iteration on design for element-specific logic (ex: mouse event handlers)
- Removed signal keyword (signals now just look like regular let bindings)
- Removed requirement for namespace qualification (ex: `Mouse` instead of `Signal.Mouse`)

### 0.2

Integrated feedback from Ryan and Keith, such as
- Using square brackets around types for 'new' expressions
- Suffix `if` syntax
- Removed tagging and tag type (just using 'strings' now)

### 0.1

Initial version of UI language.