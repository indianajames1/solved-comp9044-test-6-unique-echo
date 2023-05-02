Download Link: https://assignmentchef.com/product/solved-comp9044-test-6-unique-echo
<br>
Write a Perl program uniq_echo.pl that prints its command-line argument to standard output, similar to echo command in Shell, except only the first occurrence of any argument should be printed, Repeat occurrences should not be printed.

<table width="961">

 <tbody>

  <tr>

   <td width="961">$ <strong>./uniq_echo.pl echo echo echo</strong> echo$ <strong>./uniq_echo.pl bird cow bird cow fish bird cow fish bird</strong> bird cow fish$ <strong>./uniq_echo.pl how much wood would a woodchuck chuck</strong> how much wood would a woodchuck chuck $ <strong>./uniq_echo.pl d c b d c a a d</strong> d c b a$ <strong>./uniq_echo.pl</strong></td>

  </tr>

 </tbody>

</table>

Your answer must be Perl only. You can not use other languages such as Shell, Python or C.

You may not run external programs, e.g. via system or backquotes.

When you think your program is working you can autotest to run some simple automated tests:

$ <strong>2041 autotest uniq_echo</strong>

When you are finished working on this exercise you must submit your work by running give:

$ <strong>give cs2041 test06_uniq_echo uniq_echo.pl</strong>

Write a Perl program which reads lines from its input until it reads an line that has been entered <em>n</em> times.

Your program should then print “Snap: ” followed by the line.

Your program will be given <em>n</em> as a command line argument. Your program should print nothing if the end-of-input is reached before any line is repeated <em>n</em> times.

You can assume the lines are ASCII, you should not assume anything else about the lines.

Your answer must be Perl only. You can not use other languages such as Shell, Python or C.

You may not run external programs, e.g. via system or backquotes.

For example:

$ <strong>./snap_n.pl 2</strong> <strong>hi how are you hi </strong>

Snap: hi

$ <strong>./snap_n.pl 2</strong> <strong>hi hi hi hi hi hi hi hi hi hi hi hi </strong>

Snap: hi hi

$ <strong>./snap_n.pl 4</strong>

<strong>Hello World Line 2 </strong>

<strong>Hello World Line 3 </strong>

<strong>Hello World Line 4 </strong>

<strong>Hello World </strong>

Snap: Hello World

No error checking is necessary.

When you think your program is working you can autotest to run some simple automated tests:

$ <strong>2041 autotest snap_n</strong>

When you are finished working on this exercise you must submit your work by running give:

$ <strong>give cs2041 test06_snap_n snap_n.pl</strong>

Write a Perl program, sort_file_lines.pl which is given one argument, a file name.

Your program should print the lines of the file in order of length, shortest to longest.

Lines of equal length should be sorted alphabetically.

You can asusme the lines in the file contain ASCII. Yoy should not assume anything else about the lines in the file.

Your answer must be Perl only. You can not use other languages such as Shell, Python or C.

You may not run external programs, e.g. via system or backquotes.

No error checking is necessary.

For example:

$ <strong>cat file.txt</strong> tiny short line medium line longgggggg line a equal line b equal line c equal line even longggggggggggggggggggggggggggggggggggggggggggerr

$ <strong>sort_file_lines.pl file.txt</strong> tiny short line medium line a equal line b equal line c equal line longgggggg line

even longggggggggggggggggggggggggggggggggggggggggggerr

When you think your program is working you can autotest to run some simple automated tests:

$ <strong>2041 autotest sort_file_lines</strong>

When you are finished working on this exercise you must submit your work by running give:

$ <strong>give cs2041 test06_sort_file_lines sort_file_lines.pl</strong><img decoding="async" data-recalc-dims="1" data-src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2022/04/210-1.png?w=980&amp;ssl=1" class="lazyload" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==">

 <noscript>

  <img decoding="async" src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2022/04/210-1.png?w=980&amp;ssl=1" data-recalc-dims="1">

 </noscript>