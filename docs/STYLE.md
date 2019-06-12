# Style Guidelines

> Thank you for considering contributing to our project. Your help is welcome and appreciated. Before moving forward with repository changes, please take a moment to look over the following links which describe our purpose and our community standards.

- [License][doc-1]
- [Documentation][doc-2]
- [Code Of Conduct][doc-3]
- [Contribution Guidelines][doc-4]
- [Content Organization][doc-6]

---

## Table Of Contents

### Headings

|                               |
| :---------------------------- |
| [Philosophy][head-1]          |
| [General Programming][head-2] |
| [Commenting][head-3]          |
| [Spacing][head-4]             |
| [Formatting][head-5]          |
| [Naming][head-6]              |
| [Comparisons][head-7]         |

---

## Philosophy

> Our general purpose is to create something simple, elegant, and easy to read. To these ends, we design and change functionality based on these core philosophies:

- Prefer simplicity over complexity
- Prefer single functionality over multiple features
- Avoid duplicating existing functionality
- Avoid breaking existing functionality
- Comment to make functionality understandable
- Space to make functionality readable
- Name to make functionality navigable

---

## General Programming

> Often, there are multiple ways to design, build, and code to get desired functionality.  Programming guidelines help to make functionality more natural to follow and more stable. To these ends, keep the following in mind:

- Avoid globals when possible
- Avoid deprecated features and use modern alternative solutions
- Use strong typing when available
- Explicitly close files and sockets when done working with them
- Import files/packages/modules on separate lines

---

## Commenting

> Commenting is intended to make the purpose and usage of functionality more easily understood. To this end, keep the following in mind:

- Comment often
- Do not comment obvious functionality
- Explain the purpose of major sections with block comments
- Clarify sub-sections with single line comments
- Comment files at the top with block comments
- Comment classes/functions immediately after class/function headings with block comments
- Comment and document arguments, returns, and handled exceptions with block comments

---

## Spacing

> Appropriate spacing makes functionality more readable. It is like taking a written narrative and separating each part into chapters, and each section into paragraphs. Proper spacing will help make distinct pieces of functionality stand out.  To these ends, keep the following in mind:

- Include two blank lines between top-level definitions
- When indenting indent with four spaces
- When indenting indent without tabs
- Do not mix tabs and spaces
- Indent child elements by four additional spaces
- Follow standard rules for the use of spacing around punctuation
- Do not include whitespace inside parentheses, brackets, or braces
- Do not place whitespace before a comma, semicolon, or colon
- Include whitespace after a comma, semicolon, or colon, except at the end of the line
- Do not include whitespace before an open parentheses/bracket/brace that starts an argument list, indexing, or slicing
- Surround assignment operators, comparison operators, booleans, and arithmetic operators with a single space on either side
- Do no use whitespace to align tokens on consecutive lines vertically
- Do not include trailing whitespace

---

## Formatting

> Good formatting keeps functionality in distinct pieces, it keeps the feature in files relatively short, it aids in readability, and it keeps efforts consistent. To these ends, keep the following in mind:

- Use UTF-8 encoding
- Keep lines under 80 characters
- Attempt to keep functions under 40 lines
- Use parentheses sparingly
- Mind punctuation, spelling, and grammar

---

## Naming

> Consistent naming can help navigate functionality within files as well as across multiple files. To these ends, keep the following in mind:

- Prefer lowercase in names
- Always use the same casing when working with named items
- Make names descriptive
- Avoid single character names
- Avoid hyphens (-) in names
- Avoid double underscores in names
- Avoid numbers in names
- Avoid characters that are  not ASCII characters in names
- Follow the naming scheme:
    - module_name
    - package_name
    - ClassName
    - method_name
    - ExceptionName
    - function_name
    - GLOBAL_CONSTANT_NAME
    - global_var_name
    - instance_var_name
    - function_parameter_name
    - local_var_name

---

## Comparisons

> Consistent handling of boolean expressions and comparisons helps make code readable and sets correct expectations for functionality to follow. To these ends, keep the following in mind:

- Use multi-line conditional expressions with indents
- Use implicit boolean for evaluations if an implicit boolean is available

---

[//]: # (Document Links)

[doc-1]: ../LICENSE
[doc-2]: ../README.md
[doc-3]: ../CODE_OF_CONDUCT.md
[doc-4]: ./CONTRIBUTING.md
[doc-5]: ./STYLE.md
[doc-6]: ./ORGANIZATION.md

[//]: # (Resource Links)

[res-1]: ../resources/default-01-thumb.jpg
[res-2]: ../resources/default-01.jpg
[res-3]: ../resources/default-02-thumb.jpg
[res-4]: ../resources/default-02.jpg

[//]: # (Directory Links)

[dir-1]: ../code
[dir-2]: ../docs
[dir-3]: ./content
[dir-4]: ./examples
[dir-5]: ./research
[dir-6]: ../resources
[dir-7]: ../scripts
[dir-8]: ../tests

[//]: # (Web Links)

[web-1]: https://github.com/matthewwsavoie/default
[web-2]: https://github.com/matthewwsavoie/default/issues
[web-3]: https://github.com/matthewwsavoie/default/issues/new
[web-4]: https://help.github.com
[web-5]: https://help.github.com/articles/about-pull-requests
[web-6]: https://opensource.guide/how-to-contribute/
[web-7]: https://www.contributor-covenant.org
[web-8]: https://www.contributor-covenant.org/faq
[web-9]: https://www.contributor-covenant.org/version/1/4/code-of-conduct.html

[//]: # (Heading Links)

[head-1]: #philosophy
[head-2]: #general-programming
[head-3]: #commenting
[head-4]: #spacing
[head-5]: #formatting
[head-6]: #naming
[head-7]: #comparisons
