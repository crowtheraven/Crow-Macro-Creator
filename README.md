# UPDATE COMING SOON

Note: RUN AS ADMINISTRATOR. It probably won't work in-game otherwise.

There will be a UI! I'll leave this UI-less version available though for people who are too cool for the UI.

UPDATED: https://github.com/crowtheraven/Macro-Manager-With-Gui <---- there's the version with the gui. It's ugly, but it works.

# Crow-Macro-Creator
Program for gaming used to help easily set up your own macros and switch between different macros. Edit the .csv yourself and run the .exe. Source code is included for those interested.

Supports both keyboard presses and mouse clicks. Doesn't detect mouse clicks yet.
Turns on when you press "enter-r-enter."
Also turns on when you press "/p r enter." So if you change to party chat and type r, it'll think you're ready.
Turns off when you press enter.
Other commands for turning it on/off are on settings.csv.
The macros are edited on def.csv. Other macros can be added by you creating your own .csv files.
The code is designed to easily switch between multiple macros, so go ahead and make up to 10 of them and have  fun.
Editing the macros on excel is not advised because it'll try to autoformat - and you don't want that. Use notepad.

Note: these are .csv files, which stands for "comma separated values." They are divided into three 
columns that the code reads from. Each column is separated by a comma. Every line in the file must
have at least two commas in it, making three or more columns. The fourth column or any more after the
third column will be unread by the code and can be used for making any comments you want.

Formatting for the leftmost column (inputs):
Only one key can be used for each line.
Regular keys should be in '' or "".
Special keys should have Key. typed out, followed by the key. Such as Key.shift or Key.f5. They can't be in '' or "".

Formatting for the second (on_press) and third columns (on_release):
The second column keys are instantly pressed by the machine as soon as you press the input key associated with them.
The third column keys are instantly pressed by the machine as soon as you let go of the input key associated with them.
Regular keys or groups of keys are just typed out normally.
Special keys need to be inside {} like {tab} or {f8}.
Waits can be added also inside {}. {0.05} will tell the code to wait 0.05 seconds before pressing the keys after it.
Multiple keys can be pressed at the same time using <>. <{shift}f> will press shift+f (so, a capital F).
Mouse clicks can be added inside (). r = right click and l = left click. So (rl) is right click then left click.

TERA players send gold to Crooow on Velika NA.
