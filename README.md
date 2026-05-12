**This Shortcut is for macOS only as it requires the use of Pandoc. If you try to use it on iOS/ipadOS, it will fail!**

I have hundreds of .pages documents from over the years and have recently decided to start using Obsidian. In order to get the most use out of all of its features, I wanted to convert my old documents to markdown. Doing them one at a time was a chore not worth doing so I wrestled with Shortcuts until I got this mostly working and then let Claude/ChatGPT wrestle over who was smartest to get the rest figured out. Long story short: they're both still stupid and this took way too long to get working.

When you run the pages2obsidian shortcut, it does the following: prompts you to select one or multiple .pages documents, prompts you to choose the final export location, exports .pages to .docx in the background, and then runs a Shell Script which converts the .docx file to an Obsidian flavored .md file with Pandoc. Finally, it deletes the .docx file as that only served as an intermediary.

Check the text doc if you'd like to examine the Shell Script.

Again, a prerequisite for using this Shortcut is having Pandoc installed on your Mac. If you don't have it, you'll get an error with directions on how to install it with terminal.
