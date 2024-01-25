CPL-Contrib README

New contributions for the Champlain Problem Library (CPL) should appear here.  

By putting problems in this area, the problem authors are giving
CPL maintainers permission to copy problems from this area to the CPL.
The copies are then maintained by the CPL which may modify problems
as needed to blend into the CPL in terms of content and style.

Please put your contributions in a subdirectory prefixed with your intials, 
in the format NN-Contrib. 

> For example, JD-Contrib subdirectory contains 
Jane Doe's contributions.  

#Requests for format:

1. **Tagging**  
   Problems here do not needed to be fully "tagged" for the CPL. However, it is helpful if you could include at least the following:
   * Tags for your name, the date, and our institution
   * Subject and possibly Chapter tags: 
   	* See [current DBchapter and DBsection tags](https://raw.githubusercontent.com/openwebwork/webwork-open-problem-library/main/OpenProblemLibrary/Taxonomy2) 
   	* See also [current Keyword list](https://hobbes.la.asu.edu/Holt/keywords.html)
> For example, a tag preamble looks like this:  
> \## DBsubject('Calculus - multivariable')  
> \## DBchapter('Calculus of vector valued functions')  
> \## DBsection('Limits and continuity')  
> \## Date('2018/09/24')  
> \## Author('Jane Doe')  
> \## Institution('Champlain College Saint-Lambert')  
> \## TitleText1('')  
> \## EditionText1('')  
> \## AuthorText1('')  
> \## Section1('')  
> \## Problem1('')  
2. **File naming**  
Please prefix your .pg files with your initials (capitalized) and two digits for the year.
> For example, so if Jane Doe wrote a WeBWorK problem in 2016 on limits, she  named the file JD16limits.pg
3. **Referencing Image Files**  
In addition, if a file references other files such as image files,
please include a tag to indicate what those files are.  So, if a file
uses "image1.png" and "mypic.gif", then include the line     
> \## RESOURCES('image1.png', 'mypic.gif')      
to let us know what those files are.  
Please do not have an image file accessed by more than one problem.  Instead,
just make a copy of the image and have the pg files reference different image
files.  It costs a tiny bit of memory, but makes the files more portable.


