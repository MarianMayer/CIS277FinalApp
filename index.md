# Final App CIS 277 by Marian Mayer

## SCOPE:
Generating CNC programs, require external programming software, and it's a relatively time consuming process.
Many times though, the programs are very similar, and only few parameters are changing from a process to another. Yet, usually, the programmer has to still go through the entire process of generating a new program, even if there is only one number that changed.
To save time, the program I am proposing, will take preexisting programs, which for the purpose of this project we will call "templates", and change only the few numbers(parameters) required to genereate a new program.
To do so, the program has to be able to find the parameters in relatively large text files. I am using "tags", but also validation of the tags, as for example the tag "W" can be part of a word or a command in itself.

To me, the most dificult part seemed to be parsing the strings, and scanning them character by character, and take decisions along the way.
I found to be very satisfying though, when I was able to load the program on the machine and be able to actually run it and produce a part.

For final app presentation, I made a presentation using screen-o-cast, and email the mpg file to the professor. Then I was presenting in class, showing the presentation.
