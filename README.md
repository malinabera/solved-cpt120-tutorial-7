Download Link: https://assignmentchef.com/product/solved-cpt120-tutorial-7
<br>
<ol start="3">

 <li>Follow the materials under Canvas→ <a href="https://rmit.instructure.com/courses/56609/modules">Modules→We</a> <a href="https://rmit.instructure.com/courses/56609/modules">e</a><a href="https://rmit.instructure.com/courses/56609/modules">k</a><a href="https://rmit.instructure.com/courses/56609/modules">  </a><a href="https://rmit.instructure.com/courses/56609/modules">7</a> <a href="https://rmit.instructure.com/courses/56609/modules">…</a></li>

</ol>

<table width="741">

 <tbody>

  <tr>

   <td width="741">5.1 Complete this exercise with the help of your group tutor. However, your tutor will not be able to write the code on your behalf. Instead, they will give general guidance.Get the MusicLibraryW7.java file from Canvas→Discussions→Tutorial Discussions→Class ? (where ? is your group) and get it in to your Eclipse (If you cannot find the file, ask your group tutor). Familiarise yourself with the program first (such as by running and tracing through the code) and then modify it as follows:1.                   Create a constructor and move all of the code from the main method to the constructor and get the code to work as before. When written correctly, the main method should only contain the following two lines:MusicLibrary <u>ml</u>; ml=<strong>new</strong> MusicLibrary();2.                   Move the declarations of maxNumSongs, songTitles, songLocations and currentNumSongs from the constructor to the class block and make them <u>private</u>. These will be known as object member variables. E.g.<strong>public</strong> <strong>class</strong> MusicLibrary { <strong>private</strong> <strong>int</strong> maxNumSongs; <strong>private</strong> String[] songTitles; <strong>private</strong> String[] songLocations; <strong>private</strong> <strong>int</strong> currentNumSongs;Note: You must not have any = (equal) signs in front of the above declarations; All object member initialisations must be performed in the constructor. Also, the word ‘static’ must only be used in the main method’s definition.3.                   In your constructor, add <strong>this</strong>. (this dot) to the start of any mention of an object member variable name. E.g.maxNumSongs = 3; Should be changed to:<strong>this</strong>.maxNumSongs = 3;… and so forth for all object member variables (there are many such places).4.                   Create a method each for the three menu items of the application.5.                   Move at least one segment of repeated code to its own method. This method should take one or more parameters and return an appropriate value.</td>

  </tr>

 </tbody>

</table>

Page 1 of 2

<ol start="6">

 <li>Make the necessary changes to make the constructor accept a parameter specifying the maximum number of songs.</li>

 <li>Make the necessary changes so that, when adding a song, if a song by the same title already exists, the user is able to specify a new location for the song. When written correctly, this should not result in duplicated entries for the same song title.</li>

 <li>Make the necessary changes so that, when adding a song and if out of room, the arrays are expanded. You must not use ArrayList or similar data structures to achieve this functionality. Ask your group tutors if you are not sure.</li>

</ol>

5.2. Add comments in the style required by Assignment 2. See rubric in section 9 of the Assignment 2 PDF.

<ol start="6">

 <li>If you have not submitted your final version of A2, add comments explaining your plan. Note that this will not be marked but it is to help you progress.</li>

</ol>