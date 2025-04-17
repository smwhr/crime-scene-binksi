![image](https://github.com/user-attachments/assets/dcf9fb37-957a-4d49-9947-9ada2cc4b17d)


Crime scene is the [binksi](https://smwhr.itch.io/binksi) adaptation of the [crime scene example](https://github.com/inkle/ink/blob/master/Documentation/WritingWithInk.md#7-long-example-crime-scene) found in ink's documentation.

You can [play the scene on itch.io](https://smwhr.itch.io/crime-scene).

The original ink script is [almost unchanged](https://gist.github.com/smwhr/7de51aba40e91d0ee77cb9858d5771ef/revisions) and, most importantly the flow (always keeping a forward momentum) is faithfully reproduced.

Notable changes include :
- some choices are changed to [tagged choices](https://smwhr.github.io/binksi/docs/binksi-syntax.html) because they are an interaction with a physical object
- some choices are moved a level deeper in order to put them behind a tagged choice
- added some default choices to allow the player to walk around
- choice text is shortened to fit in the 40 characters limitation
- SPAWN_AT and CUTSCENE are sprinkled all over to give life to the scene

