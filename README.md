# apply-template
A Tiddywiki plugin with an "apply-template" button for the new Editor Toolbar

Welcome to the apply-template plugin, version 0.8.10.

This plugin adds an apply-template button to the new Editor Toolbar to be shipped with release 5.1.12. Clicking on the beaker-shaped button applies the chosen template to the selection, by transcluding the template with the current tiddler argument set to the text currently selected.

The template available by default, `$:/core/ui/TagTemplate`, is the standard way to render the selection as a tag pill. As a user, you may customize the list of available templates by adding your own to the list field of `$:/custom/apply-template/template-list`. As an illustration as well as an encouragement to find better ideas, its current value is:

    [[$:/custom/apply-template/DuckDuckGo search template]] [[$:/custom/apply-template/Google search template]]

Please give it a try by simply dragging this link to your own wiki! Any suggestion to improve this plugin (including a better suited icon) is very welcome. You may want to use tiddlywiki@googlegroups.com or write directly at cazinx at gmail.com). Of course, don't hesitate to submit a pull request at https://github.com/xcazin/apply-template.
