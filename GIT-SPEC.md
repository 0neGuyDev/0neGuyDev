What's this?
------------

A simple markdown document to talk about how I do my commits and manage my repos, this will generally be used for linking people to it when they may or may not understand my ideas of how to do git commits. 

Labels
------

I recently (24th of March) started using labels commiting, that is to make things simpler to skim, and or grep. Below is a table with a label and it's meaning.

| Label			| Meaning									|
|:--------------|------------------------------------------:|
| [NEW]			| A new file								|
| [FIX]			| A singular fix to one bug/problem			|
| [FIXES]		| Multiple fixes to multiple bugs/problems	|
| [MISTAKE] 	| Grammatical errors or minor errors I made last commit or similar, do not confuse with [CHANGES] |
| [CHANGE(s)]	| Minor changes, rewording a document, comments etc, this is not to be mistaken with [MISTAKE] |
| [FEATURE(s)] 	| A singular new feature					|
| [ADDITION(s)]	| New content or changes that don't belong with [CHANGES] nor [FEATURES] |
| 				|											|
| [OTHER]		| If no other label is suitable use this	|

Furthermore there might also be an issue number beside it, this will always be `[LABEL] Summary #ISSUE`, where "ISSUE" is replaced with the issue ID.

More may come as time passes.

Commit standards/lengths
------------------------

Commit messages are built up off a summary/title (first line) and a description (everything after and on the third line). This is very standard.

Summaries and descriptions can at maximum be 80 chars long per line, however it is preferable for the summary to be 50, and the description to be 80. Use `:set linewidth=NUM` in Vi derivatives to make your life easier.
