Lusynth
=======

Lusynth is first and foremost a programming language. It is, secondarily, an editor. The idea behind the language is this: most programmers are wasting time working in words in order to build syntax trees. A proper programming environment allows a programmer to work in syntax trees. To this end, Lusynth embraces several core principles

 * The Lusynth editor is incapable of creating a file that is not valid Lusynth
 * There are no arguments about code formatting in Lusynth. There is a single correct representation for a particular syntax tree.
 * Text operations make no sense in Lusynth. You do not diff lines, you diff subtrees. You do not commit files, you add named subtrees.
