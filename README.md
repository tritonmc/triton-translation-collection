# triton-translation-collection

A collection of translations made by the community to use with Triton!

## Using these translations in your server

1. Find the folder for the plugin you want. If it doesn't exist, leave a suggestion in our [Discord server](https://triton.rexcantor64.com/discord) or [create a request](https://github.com/diogotcorreia/triton-translation-collection/issues/new/choose).
2. Copy `output.json` to your `translations` folder.
3. Rename it to something meaningful (like the name of the plugin).
4. By default, all plugins are translated, at least, in `en_GB`. If you want to add your own translations in a language that's not provided, you can do so in TWIN.
5. _(Optional)_ If you don't have the same language name for the same language, use the `Find and replace` feature in your favorite text editor to change it.

## Generating translations from the original files

If you don't want to use the already generated `output.json`, you can use the [generator tool](https://github.com/diogotcorreia/triton-collection-generator) yourself.

## Contributing

All changes should be made by forking this repository and performing a pull request.

### Adding new plugins

If there is a plugin that you'd want to see here, please [open a request](https://github.com/diogotcorreia/triton-translation-collection/issues/new/choose).  
Additionally, if you want to contribute to the repository, create a folder with the name of the plugin and create a `README.md`, following the layout of `PLUGIN_TEMPLATE.md`.

The input files should have the name of the language they belong to.

### Adding a new language

If you want to add a new language to an already existing plugin, just clone an already existing input file from the source language and translate it yourself.
Then simply create a pull request to add it.  
If you're able to, please generate an output file using the generator yourself, but if you don't, we'll do it for you.

### Editing translations

It's the same as the previous section, except that you don't have to create the file ;)