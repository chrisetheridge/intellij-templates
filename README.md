# IntelliJ templates

Code snippet templates for IntelliJ, mostly Clojure.

## File structure

Each language will have its own XML file for snippets. Copy the snippet files you want into:
```
    # For OSX:
    ~/Library/Application\ Support/JetBrains/<idea version>/templates

    # For Linux:
    ~/.config/JetBrains/<idea version>/templates

    # For Windows:
    C:\Users\<user>\AppData\Roaming\JetBrains\<idea version>/templates
```

## Snippets

### Clojure

```
    comm
```

Creates a comment block and adds a require statement for `datomic.api`.