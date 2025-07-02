# Ash Sharp Theme

## Dark Theme for Visual Studio Code

![Ash Sharp Theme](https://res.cloudinary.com/ashrafsadacloudinary/image/upload/f_auto,q_auto/thky2gvmfntgkqnawfsk)

## Theme Preview

![Theme Preview](https://res.cloudinary.com/ashrafsadacloudinary/image/upload/v1693337655/efbgrveyrhikw8p8jpsy.png)

## Installation

1. Open **Extension's** sidebar panel in VS Code. "View → Extensions"
2. Search for "Ash Sharp Theme"
3. Click **Install**
4. Click **Reload**
5. File > Preferences > Color Theme > **Ash Sharp Theme**

## Features

- Dark theme with a focus on readability and aesthetics
- Designed for a comfortable coding experience
- Supports a wide range of languages and file types
- Custom syntax highlighting for popular languages
- Optimized for dark backgrounds

## Contribute or Customize

As this theme is open-source, you may contribute or customize this theme.
When changing the theme colors, please do NOT change the order of "TokenColors" scopes.

## Token Colors Order

Token colors order matters, when VS Code reads these scopes to implement the theme extension.
We have divided the *Token Colors* into the following sections, to maintain the best order of scopes.

To create a well-structured and effective `tokenColors` array in a VS Code theme, including punctuation scopes, here's a recommended order that balances specificity, readability, and override safety:

1. :key: **Core Keywords**: These are the keywords of most languages, font style (bold)

    1. "keyword"
    1. "keyword.control"
    1. "keyword.operator"
    1. "keyword.other"

1. :beginner: **Storage**: Refers to keywords that introduce storage declarations—like `static`, `extern`, or `register` in C/C++

    1. "keyword.control"
    1. "keyword.operator"

1. :construction: **Core Constant Syntax**: These are the core built-in types of most languages, font style (none)

    1. "constant.numeric"
    1. "constant.language"
    1. "constant.character"
    1. "constant.other"

1. 🧠 **Identifiers & Variables**: These define names and references, font style (italic)

    1. "Variable"
    1. "variable.language"
    1. "variable.name"
    1. "variable.other"
    1. "variable.object"
    1. "variable.other.ReadWrite"
    1. "variable.parameter"

1. 🧠 **Symbols Types & Functions**: These define names, types, and functions font style (none)

    1. "entity"
    1. "entity.name"
    1. "entity.name.class"
    1. "entity.name.function"
    1. "entity.name.method"
    1. "entity.name.section"
    1. "entity.name.selector"
    1. "entity.name.tag"
    1. "entity.name.type"
    1. "entity.other"
    1. "entity.other.attribute-name"
    1. "entity.other.inherited-class"

1. 🧠 **Supported Types & Functions**: These define supported names, types, and functions font style (none)

    1. "support"
    1. "support.attribute"
    1. "support.class"
    1. "support.constant"
    1. "support.function"
    1. "support.other"
    1. "support.type"
    1. "support.variable"

1. 🧾 **String & Literals**: For character values written directly in code, as strings (reference-heap, mutable) or literals (value-stack, read-only)

    1. "string"
    1. "string.interpolated"
    1. "string.other"
    1. "string.quoted"
    1. "string.regexp"
    1. "string.unquoted"

1. 🧾 **Semantic Tokens & Labels**: For character values written directly in code, as strings (reference-heap, mutable) or literals (value-stack, read-only)

    1. "ellipses.c": Variadic function syntax, uses by C derived languages, that represents a string literal like (...)
    1. "emphasis": used in Markdown or markup-like scripting languages, applies italic styling or text wrapped in single asterisks `*text*` or underscores `_text_`
    1. "strong": used in Markdown or markup-like scripting languages, applies bold styling or text wrapped in double asterisks `**text**` or double underscores `__text__`

1. 💬 **Comments & Documentation**: To visually separate commentary from code

    1. "comment.line"
    1. "comment.block"
    1. "comment.documentation"

1. ✨ **Punctuation**: These define structure and delimiters

    1. "punctuation.definition.string.begin / .end"
    1. "punctuation.definition.comment"
    1. "punctuation.separator.key-value"
    1. "punctuation.terminator.statement"
    1. "punctuation.section.block.begin / .end"
    1. "punctuation.definition.parameters.begin / .end"

1. :bricks: **Meta & Structural**: These wrap or describe other scopes

    1. "meta.function"
    1. "meta.class"
    1. "meta.block"
    1. "meta.embedded"

1. :surfer: **Markup & Markdown**: Catch-all, rarely used, invalid, or general, font style (none)

    1. "markup.*" (for Markdown, etc.)

1. :speech_balloon: **Plain Text**: Plain Text general, font style (none)

    1. "text.*"

1. :speech_balloon: **Log Text**: Log Text general, font style (none)

    1. "log.*"

1. :exclamation: **Fallback and Uncategorized**: any other rules not categorized

    1. "switch-*"
    1. "tag.*"
    1. "*.*"

1. :wolf: **Wildcards & Invalid**: Wildcards, Invalid, or illegal, font style (none)

    1. "invalid"

1. :floppy_disk: **Source**: All supported languages source, font style (none)

    1. "source"

🔸**Tip**: Place punctuation rules after strings/comments but before general fallback scopes. This ensures punctuation doesn’t override the content it surrounds.

This order helps ensure that specific tokens get styled first, and broader structural or fallback rules don’t unintentionally override them.

## Feedback and Issues

For any feedback or issues you can contact me on [GitHub](https://github.com/AshrafSada/ashsharptheme/issues)

## License

This theme is released under the [MIT](https://github.com/AshrafSada/ashtheme/blob/main/LICENSE)
