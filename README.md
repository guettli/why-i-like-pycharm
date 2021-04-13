# Why I like PyCharm

Some random notes


## Intro

* Community Edition is enough (which is free). I don't need the professional version.

* comments are in lightgray. I like this. Comments are less important than code.

* Not committed changes are highlighted with a green bar. You can easily get back to the original (or show the diff).

* unused variables easy to spot, since they are lightgray.


## Searching / Navigation

* shift-shift: Search eveywhere (even in PyCharm config). Look at the top: All, Classes, Files, Symbols, Actions, Git.

* ctrl-shift-a: Like shift-shift then "Actions".

* ctrl-shift-f: Like ctrl-f (find), but in all files.

* alt-shift cursor left/right: Navigate through the code places you visited during the last minutes.

* ctrl-e: List of last files: I like this to "blindly" jump between two files. Usualy production-code and test-code.

* ctrl-click on method name: Find usage/definition.

* OOP: You can jump up to the implemenetation of the parent class, and down to the child classes (Blue circle near the line number)

* Below the code window there is a line where you can see the upper levels (method name, class name).

* Exclude directories containing generated data. For example "staticfiles" directory in a Django context: right click "Mark Directory as > Excluded"

## Editing

* strg-alt-shift l --> reformat code

* ctrl-shift-r: Like ctrl-r (replace), but in all files.

* Mark method name, right mouse click: Refactor/rename

* Mark region, right mouse click: "Rearactor / "Extract to method".


# Tests

* Execute pytest directly. You might need to change the default test-runner first.

* Execute Django's runserver: Run / Edit Configuration / add ...


## git


* shift-shift "hist sel" --> History for Selection. Great!

* Handling git merge conflicts is better with PyCharm than the tool Meld: If two commits added roughly the same line, you see the difference
between both lines.

* Somehow I prefer to do the usual git operations (checkout, commit, push, log) with the command-line. 

## Appearance

* I reduce the font-size of non-code. And I increase (and change) the font-size of the code.  Again "shift-shift font" will bring you to the place for configuring this.

## Misc

* copy+paste history (But I prefer CopyQ which is a clipboard manager for the whole desktop, not just the IDE).

* Debugger (I try to avoid it. I prefer to write tests and assertions).

* Integrated terminal. But [IDEA-155783 "Alt ." not working](https://youtrack.jetbrains.com/issue/IDEA-155783)

* TODO list: Pycharm lists all TODOs. That's cool, if you somehow restrict that the main branch does not contain TODOs (only branches are allowed to have them). Otherwise the list is unusable since your new TODO items are between year old TODO items which are not part of your current task.

* Copy import-string of a file: right mouse click on a method, context menu "Copy / Paste Special .. Copy Reference"

## General

* Typing with ten fingers has the benefit that you can keep your eyes on the monitor and immediately check the characters you write. I have seen people looking up to the monitor and down to the keyboard several hundret times per day. That's exhausting. 
* Search with your IDE, not with your eyes. Example: if you want to a particular place in the file use ctrl-f. Don't scroll down/up and search with your eyes.



## Related

* [Güttli Django Tips](https://github.com/guettli/django-tips)
* [Güttli's opinionated Python Tips](https://github.com/guettli/python-tips)
* [Güttli working-out-loud](https://github.com/guettli/wol)


