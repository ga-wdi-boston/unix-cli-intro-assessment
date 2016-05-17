![General Assembly Logo](http://i.imgur.com/ke8USTq.png)

# Unix/CLI Diagnostic

## Challenge

Carry out all of the following tasks using _only the command line_! As is
usually the case, you're welcome to use any resource you can find (except
another student, of course) to reach your answer.

## Navigating the Filesystem

Complete each of following steps, **in order** :

1. Create a new directory called `cli-diagnostic` inside the root directory of
this repository (`unix-cli-diagnostic`).

2. Create a new file inside `cli-diagnostic` called `rhyme.txt`.

3. Open `rhyme.txt` using Atom (via the terminal) and add the following text:

 "The rain in Spain falls mainly in the plain."

 Once you've done this, save the file and quit.

4. Make a directory inside `cli-dliagnostic` called `temp`. Inside it, create a new blank file called `temp.md`.

5. Navigate back up to `cli-diagnostic`, and delete the `temp` directory (with `temp.md` inside of it).
Use `ls` to show the contents of `cli-diagnostic` - was `temp` deleted?

yes

## Absolute and Relative Paths

Open up this file in Atom, and write your answers below (where indicated).

1. Is `/Users/blah_blah/Desktop` a relative path or an absolute path? How do you know?

 <!-- Answer Starts Here -->
 Absolute path since it starts at the absolute beginning at the root.
  <!-- Answer Ends Here -->


2. Suppose that we're working on a project, and we want to use a font that's being hosted somewhere on the internet. Would we use an absolute or relative path to refer to it? Why?
 <!-- Answer Starts Here -->
 Absolute path since it's hosted in the internet, we need all the information to be able to retrieve the font. Every computer who tried to display the website will need the whole path.
 <!-- Answer Ends Here -->

3. Now suppose that we have an image file living inside our project. Would we refer to it with an absolute or relative path? Why?

 <!-- Answer Starts Here -->
 I would choose a relative path since it's shorter. We don't necessaryly need the absolute path since everything is stored in my project folder and the computer knows how to find it with relative path.
 <!-- Answer Ends Here -->

<hr>

You're done! Refer back to README.md.