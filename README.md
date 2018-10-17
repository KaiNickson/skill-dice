# skill-dice skill

Dice rolling skill for the mycroft assistant.
This skill rolls dice in RPG notation.

Command syntax:
 - _wake word_ roll 3d6
 - _wake word_ roll three six-sided dice
 - _wake word_ roll dice
 - _wake word_ roll two dice
## Current state

Working features:
 - rolls dice when spoken in RPG notation

## BUGS
Skill does't recognisse the word "a".
Asking to roll "a d20" resolves to the default 1 D6

## TODO

-shorten the diceroll soundclip
-better dialog strings. current ones sound uncanny with the current TTS (too many monotone uterances of the sord "dice"). Maybe MIMIC2 will do this better?
-make guess optional
-there is a bug where the STT has difficulties interpreting the right number. This is probably something that should be resolved on STT/mycroft-core level
