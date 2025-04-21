# WYSIWYG Drag & Drop Editor

A minimal WYSIWYG editor with the following features:

- Slash command system (`/heading`, `/list`, etc.) with fuzzy matching
- Drag & Drop support for content blocks
- Keyboard navigation (Enter to insert, Backspace to remove empty blocks)
- Fully dynamic block creation via a single configuration array (`blockTypes`)
- No dependencies, pure JavaScript

To add new block types, simply extend the `blockTypes` array – no further code changes needed.

[Demo](https://wihal.github.io/wysiwyg-editor/)