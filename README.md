# COSC1336-Programming-Assignment-1-solution

Download Here: [COSC1336 Programming Assignment #1 solution](https://jarviscodinghub.com/assignment/cosc1336-programming-assignment-1-solution/)

For Custom/Original Work email jarviscodinghub@gmail.com/whatsapp +1(541)423-7793

 Your first program will require the use of static methods and println statements. This assignment is
worth 100 points. You are going to write a Java program that produces as output the following
song.
There was an old woman who swallowed a fly.
I don’t know why she swallowed that fly,
Perhaps she’ll die.
There was an old woman who swallowed a spider,
That wriggled and jiggled and jiggled inside her.
She swallowed the spider to catch the fly,
I don’t know why she swallowed that fly,
Perhaps she’ll die.
There was an old woman who swallowed a bird,
How absurd to swallow a bird.
She swallowed the bird to catch the spider,
She swallowed the spider to catch the fly,
I don’t know why she swallowed that fly,
Perhaps she’ll die.
There was an old woman who swallowed a cat,
Imagine that to swallow a cat.
She swallowed the cat to catch the bird,
She swallowed the bird to catch the spider,
She swallowed the spider to catch the fly,
I don’t know why she swallowed that fly,
Perhaps she’ll die.
There was an old woman who swallowed a dog,
What a hog to swallow a dog.
She swallowed the dog to catch the cat,
She swallowed the cat to catch the bird,
She swallowed the bird to catch the spider,
She swallowed the spider to catch the fly,
I don’t know why she swallowed that fly,
Perhaps she’ll die.
There was an old woman who swallowed a horse,
She died of course.
You must exactly reproduce the format of this output.
You are to make use of static methods to avoid the “simple” redundancy. In particular, you are to
make sure that you use only one println statement for each distinct line of the song. For example,
this line:
Perhaps she’ll die.
appears several times in the output. You are to have only one println statement in your
program for producing this line. That is, write a static method for it. The method will then be
called by other methods.
The more complex redundancy has to do with pairs of lines like these:
There was an old woman who swallowed a horse,
There was an old woman who swallowed a dog,
and like these:
She swallowed the dog to eat the cat,
She swallowed the cat to eat the bird,
It is not possible to avoid this redundancy using just methods and simple println statements, so you
are not expected to do so. There is, however, a structural redundancy that you can eliminate with
static methods and this will be worth a point. The key question to ask yourself is whether or not
you have repeated lines of code that could be eliminated if you structured your static methods
differently.
You should also be using static methods to capture the structure of the song. You should, for
example, have a different method for each of the six verses of the song (verses are separated by
blank lines in the output).
You are not allowed to use more advanced features than what we have covered in class. For this
assignment, you should limit yourself to the Java features covered in chapter 1 of the text.
You should include a comment at the beginning of your program with some basic information and
a description of the program, as in:
// Yu-Pa Ng
// 8/29/2016
// COSC1336
// Assignment #1
//
// This program will…
You should name your file Song.java.
You are required to properly indent your code and will lose points if you make indentation
mistakes.
Submission and Grading:
Turn in your Song.java file electronically from the Programming Projects link on the Canvas
course web page. Please make sure to use exactly this file name, including identical capitalization.
Part of your program’s score will come from its “external correctness.” (50 points) External
correctness measures whether the output matches exactly what is expected. (I am very picky about
the output matching exactly. Every character and space must match.) Programs that do not
compile will receive no external correctness points.
The rest of your program’s score will come from its “internal correctness.” (50 points) Internal
correctness measures whether your source code follows the stylistic guidelines specified in this
document.

