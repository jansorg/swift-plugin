## Cross-platform Swift language support for JetBrains IDEs 2023.2.

<br>[discussions](https://github.com/jansorg/swift-plugin/discussions) · [bug tracker](https://github.com/jansorg/swift-plugin/issues) · [newsletter](https://lists.j-a.dev/subscription?f=fUWUAxYS1O09VBQtL0S0YJrJHotnoE7f35nm892D9KiINm3fsOPw9MTMtRSzN2PDzK)
<br>
<br>

**This plugin is in an early state and under active development!**
<br>
It's cross-platform and available for all JetBrains 2023.2 IDEs (currently in EAP).
<br>

***Important**: This plugin will become a freemium or a paid plugin in the future.*
<br>
For now, this plugin is free to use and does not need a license.
<a target="_blank" href="https://lists.j-a.dev/subscription?f=fUWUAxYS1O09VBQtL0S0YJrJHotnoE7f35nm892D9KiINm3fsOPw9MTMtRSzN2PDzK">
Join the Swift plugin newsletter</a> to receive updates about the plugin and its development.
<br>
<br>

**[Please join the discussions](https://github.com/jansorg/swift-plugin/discussions) to shape the future of this plugin.**
<br>

**Available features** (all in an early state):

- Support for the language specification of Swift 5.9 beta
- Code completion
- Go to declaration
- Find usages and reference highlighting
- Rename refactoring
- Quick documentation with colored rendering of embedded code blocks
- Structure view
- Code folding with custom settings for default code folding
- Language injection support for string and multiline string literals
- File templates for common Swift declarations
- Syntax highlighting
- Color schema settings
- ToDo item highlighting
- Navigation bar support
- Brace matching for `()`, `{}`, `[]`
- Comment support

Some of the features listed above are based on Apple's `sourcekit-lsp` and need an installed Swift toolchain. The implementation was tested with the current stable version of Swift.
<br>

**Known limitations** of the already available features:
- Renaming a function declared in a `protocol` does not yet rename all implementations of this function.
