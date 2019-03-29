
To start recording, press `q` in normal mode followed by `a` letter (a to z). That starts recording keystrokes to the specified register. Vim displays recording in the status line. Type any normal mode commands, or enter insert mode and type text. To stop recording, again press `q` while in normal mode.

To playback your keystrokes, press `@` followed by the letter previously chosen. Typing `@@` repeats the last playback.

Use the normal command in Ex mode to execute the macro on multiple/all lines:

Execute the macro stored in register a on lines 5 through 10.

```
:5,10norm! @a
```
Execute the macro stored in register a on lines 5 through the end of the file.

```
:5,$norm! @a
```
Execute the macro stored in register a on all lines.

```
:%norm! @a
```
Execute the macro store in register a on all lines matching pattern.

```
:g/pattern/norm! @a
```
To execute the macro on visually selected lines, press V and the j or k until the desired region is selected. Then type :norm! @a and observe the that following input line is shown.

```
:'<,'>norm! @a
```
Enter :help normal in vim to read more.
