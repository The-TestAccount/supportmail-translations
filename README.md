# Folder structure
```
module
  | LC_MESSAGES
    | message.po <- target-file
```

## Standard Translations
```py
# Comments start with # at the start of a line
msgid "Either the ID for the identification or the text that's getting translated."
msgstr "The translated text here"
```

## Multi-Line translations
```py
msgid "theID"
msgstr ""
"New\n"
"line"
```

Note, that every line except the last one has to end with `\n` in order for the new line to work
`\n` represents a newline-character

If no .po-file is given, then it's just plain text.

### Questions? Create a discussion or ask in the [dev-chat](https://discord.com/channels/1064594649668395128/1110943162458980354).
