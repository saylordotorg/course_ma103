---
layout: default
title: "MA103: Multivariable Calculus"
course_description: "An examination of the definitions of the basic trigonometric functions and their properties, trigonometric equations and identities, the laws of sines and cosines, polar coordinates and graphs, parametric equations, and elementary vector operations."
next: ../Unit04
previous: ../Unit02
---
**Unit 3: Double Integrals and Line Integrals in the Plane** <span
id="3"></span> 
*In Single-Variable Calculus, you learned that the integral of a
function is the area below the graph of the function and over a
specified interval.  The double integral of a function of two variables
is the volume below the graph of the function and over a specified
region.  In Single-Variable Calculus, you approximated the area under a
curve by taking slices of the area.  You will now approximate the volume
under a function by taking slices of the entire volume. *  
    
 *In Single-Variable Calculus, you learned about results such as the
area of a region, volume of a solid, and length of a curve using
definite integrals.  In this unit of Multi-Variable Calculus, we will
develop the theory of multiple integrals to determine similar
results.*  
    
 *You will also learn about Green’s Theorem; it* *defines the
relationship between line integrals and double* *integrals, allowing us
to reduce possibly complicated line integrals to a potentially* *simpler
double integral.  Please note that Green's Theorem is a two-dimensional
case of* *the more general Stokes’ Theorem, which we will discuss in the
next unit.*  
                      
 *Finally, you will learn about flux; it is a scalar quantity important
to the fields of mathematics and physics. It is derived from the surface
integral over a specified region of a particular vector field.  Using
what we know about fields and integrals, we can look at the physical
interpretations of flux.*

**Unit 3 Time Advisory**  
This unit will take you approximately 26.75 hours to complete.  
  
 ☐    Subunit 3.1: 11.5 hours
  
 ☐    Subunit 3.1.1: 3.75 hours  
  
 ☐    Subunit 3.1.2: 1.5 hour  
  
 ☐    Subunit 3.1.3: 2.75 hours  
  
 ☐    Subunit 3.1.4: 3.5 hours

☐    Subunit 3.2: 8 hours
  
 ☐    Subunit 3.2.1: 3.25 hours  
  
 ☐    Subunit 3.2.2: 2 hours  
  
 ☐    Subunit 3.2.3: 2.75 hours

☐    Subunit 3.3: 7.25 hours
  
 ☐    Subunit 3.3.1: 1.5 hours  
  
 ☐    Subunit 3.3.2: 3 hours  
  
 ☐    Subunit 3.3.3: 1.25 hours  
  
 ☐    Subunit 3.3.4: 1.5 hours

**Unit3 Learning Outcomes**  
Upon successful completion of this unit, the student will be able to:  
  
-   Evaluate double integrals.
-   State the difference between type I and type II integrals.
-   Find the volume over type I region.
-   Find the volume of solids over type II regions.
-   Change iterated integrals from type I to type II and vice versa.
-   State Fubini's Theorem, and use it to evaluate integrals.
-   Use properties of double integrals to evaluate double integrals.
-   Use integrals to calculate the volume and mass.
-   Find image of a given region under a given transformation.
-   Use a given transformation to evaluate a given iterated integral.
-   Construct vector fields.  
-   Find the gradient vector field. 
-   Compute divergence and curl of vector fields.  
-   Evaluate line integrals.
-   Derive and apply formulas involving divergence, gradient, and curl.
-   Apply Green's Theorem to evaluate line integrals.  
-   Evaluate Green's Theorem to find the area of a region.

**3.1 Multiple Integrals** <span id="3.1"></span> 
**3.1.1 Double Integrals** <span id="3.1.1"></span> 
-   **Lecture: MIT: Denis Auroux’s Multivariable Calculus: “Video
    Lecture 16: Double Integrals”**
    Link: MIT: Denis Auroux’s *Multivariable Calculus:* [“Video Lecture
    16: Double
    Integrals”](http://www.youtube.com/watch?v=6esUq4HYkLo) (YouTube)  
        
     Also available in: [Adobe Flash, iTunes, or
    Mp4](http://ocw.mit.edu/courses/mathematics/18-02-multivariable-calculus-fall-2007/video-lectures/lecture-16-double-integrals/)  
        
     Instructions: Please view the entire video lecture (48:00).  You
    may also click on the “Transcript” tab on the page to read the
    lecture.  
      
      This video should take approximately 1 hour to watch and review.  
        
     Terms of Use: The video above is released under [Creative Commons
    Attribution-NonCommercial-ShareAlike
    3.0](http://creativecommons.org/licenses/by-nc-sa/3.0/).  It is
    attributed to Denis Auroux and the original version can be found
    [here](http://ocw.mit.edu/courses/mathematics/18-02-multivariable-calculus-fall-2007/video-lectures/lecture-16-double-integrals/).

-   **Reading: MIT: Denis Auroux’s Multivariable Calculus: “III. Double
    Integrals and Line Integrals in the Plane”**
    Link: MIT: Denis Auroux’s *Multivariable Calculus:* [“III. Double
    Integrals and Line Integrals in the
    Plane”](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2012/09/MA103-Auroux-3.1.1.pdf) (PDF)   
      
     Instructions: Read the entire PDF document (4 pages).  Please note
    that this reading is paired with the video lecture above so please
    read it after watching the video.  
        
     Terms of Use: The article above is released under a [Creative
    Commons Attribution-NonCommercial-ShareAlike
    3.0](http://creativecommons.org/licenses/by-nc-sa/3.0/). It is
    attributed to Denis Auroux and the original version can be found
    [here](http://ocw.mit.edu/courses/mathematics/18-02-multivariable-calculus-fall-2007/lecture-notes/).

-   **Reading: East Tennessee State University: Jeff Knisley’s
    Multivariable Calculus Online: “Chapter 4: Multiple Integrals”, “4.1
    Iterated Integrals” and “4.2 The Double Integral”**
    Links: East Tennessee State University: Jeff Knisley’s
    *Multivariable Calculus Online:* “Chapter 4: Multiple Integrals:”
    [“4.1 Iterated
    Integrals”](http://math.etsu.edu/multicalc/prealpha/Chap4/Chap4-1/index.htm) (HTML
    and Java) and [“4.2 The Double
    Integral”](http://math.etsu.edu/multicalc/prealpha/Chap4/Chap4-2/index.htm) (HTML)  
        
     Instructions: Please open and read Parts 1-4 of both “Section 4.1
    Iterated Integrals” and “Section 4.2 The Double Integral.”  To
    access each section, click on the links to each part at the top of
    the webpages.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

-   **Assessment: East Tennessee State University: Jeff Knisley’s
    Multivariable Calculus Online: “4.1 Iterated Integrals Exercises”
    and “4.2 The Double Integral Exercises”**
    Link: East Tennessee State University: Jeff Knisley’s *Multivariable
    Calculus Online: *[“4.1 Iterated Integrals
    Exercises”](http://math.etsu.edu/multicalc/prealpha/Chap4/Chap4-1/index.htm) (HTML)
    and [“4.2 The Double Integral
    Exercises”](http://math.etsu.edu/multicalc/prealpha/Chap4/Chap4-2/index.htm) (HTML)  
        
     Instructions: Please click on the “4.1 Iterated Integrals
    Exercises” link above, and then select the “Exercises’ link at the
    top right hand of the webpage to access the questions.  Work through
    exercises 7, 13, 21, and 23.  Once you have completed those
    exercises, click the link titled “4.2:  Double Integrals Exercises”
    above, and select the “Exercises” link at the top of the webpage to
    redirect to the question sets.  Try to complete exercises 7, 13, 21,
    and 29.  Check the solutions by clicking on the link titled
    [“Answers to Selected Odd
    Exercises”](http://math.etsu.edu/multicalc/prealpha/answers.htm) (PDF)
    on the main page, choose chapter 4, then locate sections 4.1 and
    4.2.  
        
     These exercises should take approximately 1 hour to complete.  
      
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

-   **Activity: The Saylor Foundation: Math Insight’s “Introduction to
    Double Integrals” and “Double Integrals as Volume”**
    Link: The Saylor Foundation: <span
    style="background-color: transparent; background-image: initial; background-attachment: initial; background-origin: initial; background-clip: initial; ">Math
    Insight’s
    </span>[“](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2012/10/MA103-An-Introduction-to-Double-Integrals.pdf)[I](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2012/10/MA103-An-Introduction-to-Double-Integrals.pdf)[ntroduction
    to Double
    Integrals”](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2012/10/MA103-An-Introduction-to-Double-Integrals.pdf) (PDF)
    and [“Double Integrals as
    Volume”](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2012/10/MA103-Double-Integrals-as-Voume.pdf) (PDF)  
      
     <span style="background-color: transparent;"> Also Available in:  
     [HTML and
    Java](http://mathinsight.org/double_integral_introduction)
    (Introduction to Double Integrals)  
     [HTML and Java](http://mathinsight.org/double_integral_volume)
    (Double Integrals as Volume)</span>  
      
     \*NOTE: In order to view the Java applets within this resource you
    must click on the HTML and Java links, as the PDF version does not
    support the Java applets.   
      
     <span style="background-color: transparent;"> Instructions: Click
    on the webpages linked above and work through the notes and the
    applets. Feel free to work on more examples or reading more sections
    by clicking the relevant links on the bottom of the pages.</span>  
      
     This activity should take approximately 30 minutes to complete.  
      
     Terms of Use: The linked resources above are released under
    a [Creative Commons Attribution-NonCommercial-ShareAlike 3.0
    Unported
    License](http://creativecommons.org/licenses/by-nc-sa/3.0/), they
    are attributed to Duane Q. Nykamp and the original versions can be
    found [here](http://mathinsight.org/double_integral_introduction) and
    [here](http://mathinsight.org/double_integral_volume).

**3.1.2 Applications of the Double Integral** <span id="3.1.2"></span> 
-   **Reading: East Tennessee State University: Jeff Knisley’s
    Multivariable Calculus Online: “Chapter 4: Multiple Integrals:” “4.3
    Applications of the Double Integral”**
    Link: East Tennessee State University: Jeff Knisley’s *Multivariable
    Calculus Online:* “Chapter 4: Multiple Integrals:” [“4.3
    Applications of the Double
    Integral”](http://math.etsu.edu/multicalc/prealpha/Chap4/Chap4-3/index.htm) (HTML
    and Java)  
        
     Instructions: Please read Parts 1-4 of “Applications of the Double
    Integral” from the link posted above.  Begin by reading the webpage
    titled “Part 1: Mass Density.”  Then, click on the link to each
    additional part at the top of the webpage.  
      
     This reading should take approximately 30 minutes to study.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

-   **Assessment: East Tennessee State University: Jeff Knisley’s
    Multivariable Calculus Online: “4.3 Applications of the Double
    Integral Exercises”**
    Link: East Tennessee State University: Jeff Knisley’s *Multivariable
    Calculus Online:* [“4.3 Applications of the Double Integral
    Exercises”](http://math.etsu.edu/multicalc/prealpha/Chap4/Chap4-3/index.htm) (HTML
    and Java)  
        
     Instructions: Please click on the link titled “4.3 Applications of
    the Double Integral Exercises” above, and once on the webpage,
    select the “Exercises” link on the upper right corner of the webpage
    to access the questions.  Work through exercises 1, 11, and 23. 
    Check the solutions by clicking on the link titled [“Answers to
    Selected Odd
    Exercises”](http://math.etsu.edu/multicalc/prealpha/answers.htm) (PDF)
    on the main page, choose chapter 4, then locate section 4.3.  
      
     These exercises should take approximately 1 hour to complete.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**3.1.3 Double Integrals in Polar Coordinates** <span
id="3.1.3"></span> 
-   **Lecture: MIT: Denis Auroux’s Multivariable Calculus: “Video
    Lecture 17: Polar Coordinates”**
    Link: MIT: Denis Auroux’s *Multivariable Calculus:* [“Video Lecture
    17: Polar
    Coordinates”](http://www.youtube.com/watch?v=oeyvI2A_LOs) (YouTube)  
        
     Also available in: [Adobe Flash, iTunes, or
    Mp4](http://ocw.mit.edu/courses/mathematics/18-02-multivariable-calculus-fall-2007/video-lectures/lecture-17-polar-coordinates/)  
        
     Instructions: Please view the entire video lecture (51:30).  You
    may also click on the “Transcript” tab on the page to read the
    lecture.  
      
     This video should take approximately 1 hour and 15 minutes to watch
    and review.  
        
     Terms of Use: The video above is released under [Creative Commons
    Attribution-NonCommercial-ShareAlike
    3.0](http://creativecommons.org/licenses/by-nc-sa/3.0/).  It is
    attributed to Denis Auroux and the original version can be found
    [here](http://ocw.mit.edu/courses/mathematics/18-02-multivariable-calculus-fall-2007/video-lectures/lecture-17-polar-coordinates/).

-   **Reading: East Tennessee State University: Jeff Knisley’s
    Multivariable Calculus Online: “Chapter 4: Multiple Integrals:” “4.5
    Integration in Polar Coordinates”**
    Link: East Tennessee State University: Jeff Knisley’s *Multivariable
    Calculus Online:* [“Chapter 4: Multiple Integrals: 4.5 Integration
    in Polar
    Coordinates”](http://math.etsu.edu/multicalc/prealpha/Chap4/Chap4-5/index.htm) (HTML)  
        
     Instructions: Please click on the link above titled “4.5
    Integration in Polar Coordinates.”  Begin by reading the webpage for
    “Part 1: Change of Variable into Polar Coordinates.”  Then, click on
    the link to each additional part at the top of the webpage; read all
    four parts in their entirety.  
        
     This reading should take approximately 30 minutes to study.  
      
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

-   **Assessment: East Tennessee State University: Jeff Knisley’s
    Multivariable Calculus Online: “4.5 Integration in Polar Coordinates
    Exercises”**
    Link: East Tennessee State University: Jeff Knisley’s *Multivariable
    Calculus Online:* [“4.5 Integration in Polar Coordinates
    Exercises”](http://math.etsu.edu/multicalc/prealpha/Chap4/Chap4-5/index.htm) (HTML)  
        
     Instructions: Please click the link titled “Section 4.5 Double
    Integrals in Polar Coordinates Exercises” found above, and once on
    the webpage, click on the link titled “Exercises” at the upper right
    corner of the webpage to access the questions.  Solve exercises 5,
    11, 21, and 27.  Check the solutions by clicking on the link titled
    [“Answers to Selected Odd
    Exercises”](http://math.etsu.edu/multicalc/prealpha/answers.htm) (PDF)
    on the main page, choose chapter 4, then locate section 4.5.  
      
     These exercises should take approximately 1 hour to complete.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**3.1.4 Change of Variables** <span id="3.1.4"></span> 
-   **Lecture: MIT: Denis Auroux’s Multivariable Calculus: “Video
    Lecture 18: Change of Variables”**
    Link: MIT: Denis Auroux’s *Multivariable Calculus:* [“Video Lecture
    18: Change of
    Variables”](http://www.youtube.com/watch?v=5Ti-SQAI-uE) (YouTube)  
        
     Also available in:  [Adobe Flash, iTunes, or
    Mp4](http://ocw.mit.edu/courses/mathematics/18-02-multivariable-calculus-fall-2007/video-lectures/lecture-18-change-of-variables/)  
        
     Instructions: Please view the entire video lecture (49:55).  You
    may also click on the “Transcript” tab on the page to read the
    lecture.  
      
     This video should take approximately 1 hour and 15 minutes to watch
    and review.  
        
     Terms of Use: The video above is released under [Creative Commons
    Attribution-NonCommercial-ShareAlike
    3.0](http://creativecommons.org/licenses/by-nc-sa/3.0/).  It is
    attributed to Denis Auroux and the original version can be found
    [here](http://ocw.mit.edu/courses/mathematics/18-02-multivariable-calculus-fall-2007/video-lectures/lecture-18-change-of-variables/). 

-   **Reading: MIT: Denis Auroux’s Multivariable Calculus: “III. Double
    Integrals and Line Integrals in the Plane”**
    Link: MIT: Denis Auroux’s *Multivariable Calculus:* [“III. Double
    Integrals and Line Integrals in the
    Plane”](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2012/09/MA103-Auroux-3.1.4.pdf) (PDF)  
        
     Instructions: Read the entire document (5 pages).  Please note that
    this reading is paired with the video lecture above so please read
    it after watching the video.  
      
     This reading should take approximately 15 minutes to read and
    review.  
        
     Terms of Use: The article above is released under a [Creative
    Commons Attribution-NonCommercial-ShareAlike
    3.0](http://creativecommons.org/licenses/by-nc-sa/3.0/). It is
    attributed to Denis Auroux and the original version can be found
    [here](http://ocw.mit.edu/courses/mathematics/18-02-multivariable-calculus-fall-2007/lecture-notes/).

-   **Reading: East Tennessee State University: Jeff Knisley’s
    Multivariable Calculus Online: “Chapter 4: Multiple Integrals: 4.4
    Change of Variable”**
    Link: East Tennessee State University: Jeff Knisley’s *Multivariable
    Calculus Online:* [“Chapter 4: Multiple Integrals: 4.4 Change of
    Variable”](http://math.etsu.edu/multicalc/prealpha/Chap4/Chap4-4/index.htm) (HTML)  
        
     Instructions: Please read Parts 1-4 of “Section 4.4 Change of
    Variable.” Begin by reading “Part 1: Area of the Image of a Region”
    which the link above will take you to, after you complete Part 1,
    click on the links to Parts 2-4 at the top of the webpage to
    continue reading.  
      
     This reading should take approximately 30 minutes to read and
    review.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

-   **Assessment: East Tennessee State University: Jeff Knisley’s
    Multivariable Calculus Online: “4.4 Change of Variable Exercises”**
    Link: East Tennessee State University: Jeff Knisley’s *Multivariable
    Calculus Online:* [“4.4 Change of Variable
    Exercises”](http://math.etsu.edu/multicalc/prealpha/Chap4/Chap4-4/index.htm) (HTML)  
        
     Instructions: Please click the link titled “4.4: Change of Variable
    Exercises” above, and once on the webpage, select the “Exercises”
    link to redirect to the question sets.  Work on exercises 5, 15, and
    23.  Check the solutions by clicking on the link titled [“Answers to
    Selected Odd
    Exercises”](http://math.etsu.edu/multicalc/prealpha/answers.htm) (PDF)
    on the main page, choose chapter 4, then locate section 4.4.  
      
     These exercises should take approximately 1 hour to complete.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

-   **Activity: The Saylor Foundation: Math Insight’s “Introduction to
    Changing Variables in Double Integrals”**
    Link: The Saylor Foundation: <span
    style="background-color: transparent; background-image: initial; background-attachment: initial; background-origin: initial; background-clip: initial; ">Math
    Insight’s </span>[“Introduction to Changing Variables in Double
    Integrals”](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2012/10/MA103-Introduction-to-Changing-Variables-in-Double-Integrals.pdf) (PDF)  
      
     Also Available in:  
     <span style="background-color: transparent;"> [HTML and
    Java](http://mathinsight.org/double_integral_change_variables_introduction)</span>  
      
     \*NOTE: In order to view the Java applets within this resource you
    must click on the [HTML and
    Java](http://mathinsight.org/double_integral_change_variables_introduction) link,
    as the PDF version does not support the Java applets.   
      
     <span style="background-color: transparent;"> Instructions: Click
    on the webpage linked above and work through the notes and the
    applets. Feel free to work on more examples or read more sections by
    clicking the relevant links on the bottom of the page. </span>  
      
     This activity should take approximately 30 minutes to complete.  
      
     Terms of Use: The linked resource above is released under
    a [Creative Commons Attribution-NonCommercial-ShareAlike 3.0
    Unported
    License](http://creativecommons.org/licenses/by-nc-sa/3.0/), it is
    attributed to Duane Q. Nykamp and the original version can be
    found [here](http://mathinsight.org/double_integral_change_variables_introduction).

**3.2 Vector Fields and Line Integrals** <span id="3.2"></span> 
**3.2.1 Vector Fields** <span id="3.2.1"></span> 
-   **Activity: The Saylor Foundation: Math Insight’s “Vector Field
    Overview”**
    Link: The Saylor Foundation: <span
    style="background-color: transparent; background-image: initial; background-attachment: initial; background-origin: initial; background-clip: initial; ">Math
    Insigh</span>t’s
    [“](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2012/10/MA103-Vector-Field-Overview.pdf)[V](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2012/10/MA103-Vector-Field-Overview.pdf)[ector
    Field
    Overview”](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2012/10/MA103-Vector-Field-Overview.pdf) (HTML<span
    style="background-color: transparent;"> and Java)  
      
     Also Available in:  
     [HTML and
    Java](http://mathinsight.org/vector_field_overview)</span>  
      
     \*NOTE: In order to view the Java applets within this resource you
    must click on the [HTML and
    Java](http://mathinsight.org/vector_field_overview) link, as the PDF
    version does not support the Java applets.   
      
     <span style="background-color: transparent;"> Instructions: Click
    on the webpage linked above and work through the notes and the
    applets. Feel free to work on more examples or read more sections by
    clicking the relevant links on the bottom of the page. </span>  
      
     This activity should take approximately 30 minutes to complete.  
      
     Terms of Use: The linked resource above is released under
    a [Creative Commons Attribution-NonCommercial-ShareAlike 3.0
    Unported
    License](http://creativecommons.org/licenses/by-nc-sa/3.0/), it is
    attributed to Duane Q. Nykamp and the original version can be
    found [here](http://mathinsight.org/vector_field_overview).

-   **Lecture: MIT: Denis Auroux’s Multivariable Calculus: “Video
    Lecture 19: Vector Fields”**
    Link: MIT: Denis Auroux’s *Multivariable Calculus:* [“Video Lecture
    19: Vector
    Fields”](http://www.youtube.com/watch?v=vZPn52jVtzY) (YouTube)  
        
     Also available in: [Adobe Flash, iTunes, or
    Mp4](http://ocw.mit.edu/courses/mathematics/18-02-multivariable-calculus-fall-2007/video-lectures/lecture-19-vector-fields/)  
        
     Instructions: Please view the entire video lecture (51:09).  You
    may also click on the “Transcript” tab on the page to read the
    lecture.  
      
     This video should take approximately 1 hour and 15 minutes to watch
    and review.  
        
     Terms of Use: The video above is released under [Creative Commons
    Attribution-NonCommercial-ShareAlike
    3.0](http://creativecommons.org/licenses/by-nc-sa/3.0/).  It is
    attributed to Denis Auroux and the original version can be found
    [here](http://ocw.mit.edu/courses/mathematics/18-02-multivariable-calculus-fall-2007/video-lectures/lecture-19-vector-fields/).

-   **Reading: East Tennessee State University: Jeff Knisley’s
    Multivariable Calculus Online: “Chapter 5: Fundamental Theorems:”
    “5.1 Vector Fields”**
    Link: East Tennessee State University: Jeff Knisley’s *Multivariable
    Calculus Online:* [“Chapter 5: Fundamental Theorems: 5.1 Vector
    Fields”](http://math.etsu.edu/multicalc/prealpha/Chap5/Chap5-1/index.htm) (HTML
    and Java)  
        
     Instructions: Please read Parts 1-4 of “Section 5.1: Vector
    Fields.”  Begin by reading “Part 1: Vector Fields” found above, and
    then continue on by selecting the links to Parts 2-4 at the top of
    the webpage.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

-   **Assessment: East Tennessee State University: Jeff Knisley’s
    Multivariable Calculus Online: “5.1 Vector Fields Exercises”**
    Link: East Tennessee State University: Jeff Knisley’s *Multivariable
    Calculus Online:* [“5.1 Vector Fields
    Exercises”](http://math.etsu.edu/multicalc/prealpha/Chap5/Chap5-1/index.htm) (HTML
    and Java)  
      
     Instructions: Please click on the “5.1 Vector Fields Exercises”
    link above, and once on the webpage, click on the “Exercises” link
    at the top of the webpage to redirect to the exercise sets.  Work on
    questions 1, 5, 17, 21, and 25.  Check the solutions by clicking on
    the link titled [“Answers to Selected Odd
    Exercises”](http://math.etsu.edu/multicalc/prealpha/answers.htm) (PDF)
    on the main page, choose chapter 5, then locate section 5.1.  
      
     These exercises should take approximately 1 hour to complete.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**3.2.2 Line Integrals** <span id="3.2.2"></span> 
-   **Reading: East Tennessee State University: Jeff Knisley’s
    Multivariable Calculus Online: “Chapter 5: Fundamental Theorems:”
    “5.2 Line Integrals”**
    Link: East Tennessee State University: Jeff Knisley’s *Multivariable
    Calculus Online:* [“Chapter 5: Fundamental Theorems: 5.2 Line
    Integrals”](http://math.etsu.edu/multicalc/prealpha/Chap5/Chap5-2/index.htm) (HTML
    and Java)  
        
     Instructions: Read Parts 1-4 of “Section 5.2: Line Integrals.” 
    Begin by reading the first webpage which can be found in the link
    above (“Part 1: Line Integrals over Parameterized Curves”), and then
    select the links to Parts 2-4 at the top of the webpage to continue
    reading.  
      
     This reading should take approximately 30 minutes to read and
    review.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

-   **Assessment: East Tennessee State University: Jeff Knisley’s
    Multivariable Calculus Online: “5.2 Line Integrals Exercises”**
    Link: East Tennessee State University: Jeff Knisley’s *Multivariable
    Calculus Online:* [“5.2 Line Integrals
    Exercises”](http://math.etsu.edu/multicalc/prealpha/Chap5/Chap5-2/index.htm) (HTML)  
        
     Instructions: Please click the link titled “Section 5.2: Line
    Integrals” above, and then select the “Exercises” link at the upper
    right hand corner of the webpage to access the question sets.  Try
    to solve exercises 5, 9, 21, and 23.  Check the solutions by
    clicking on the link titled [“Answers to Selected Odd
    Exercises”](http://math.etsu.edu/multicalc/prealpha/answers.htm) (PDF)
    on the main page, choose chapter 5, then locate section 5.2.  
      
     These exercises should take approximately 1 hour to complete.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

-   **Activity: The Saylor Foundation: Math Insight’s “An Introduction
    to a Line Integral of a Vector Field”**
    Link: The Saylor Foundation: <span
    style="background: transparent">Math Insight’s </span><span
    lang="zxx">[<span style="background: transparent">“An Introduction
    to a Line Integral of a Vector
    Field”</span>](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2012/10/MA103-Introduction-to-a-Line-Integral-of-a-Vector-Field.pdf)</span><span
    style="background: transparent"> (PDF)  
      
     Also Available in:  
     [HTML and
    Java](http://mathinsight.org/line_integral_vector_field_introduction)  
      
     \*NOTE: In order to view the Java applets within this resource you
    must click on the [HTML and
    Java](http://mathinsight.org/line_integral_vector_field_introduction) link,
    as the PDF version does not support the Java applets.   
      
     Instructions: Click on the webpage linked above and work through
    the notes and the applets. Feel free to work on more examples or
    read more sections by clicking the relevant links on the bottom of
    the page. </span>  
      
     This activity should take approximately 30 minutes to complete.  
      
     Terms of Use: The linked resource above is released under
    a [Creative Commons Attribution-NonCommercial-ShareAlike 3.0
    Unported
    License](http://creativecommons.org/licenses/by-nc-sa/3.0/), it is
    attributed to Duane Q. Nykamp and the original version can be
    found [here](http://mathinsight.org/line_integral_vector_field_introduction). 

**3.2.3 Path Independence and Conservative Fields** <span
id="3.2.3"></span> 
-   **Lecture: MIT: Denis Auroux’s Multivariable Calculus: “Video
    Lecture 20: Path Independence”**
    Link: MIT: Denis Auroux’s *Multivariable Calculus:* [“Video Lecture
    20: Path
    Independence”](http://www.youtube.com/watch?v=pV6Kj6RRNII) (YouTube)  
        
     Also available in: [Adobe Flash, iTunes, or
    Mp4](http://ocw.mit.edu/courses/mathematics/18-02-multivariable-calculus-fall-2007/video-lectures/lecture-20-path-independence/)  
        
     Instructions: Please view the entire video lecture (50:23).  You
    may also click on the “Transcript” tab on the page to read the
    lecture.  
      
     This video should take approximately 1 hour and 15 minutes to watch
    and review.  
        
     Terms of Use: The video above is released under [Creative Commons
    Attribution-NonCommercial-ShareAlike
    3.0](http://creativecommons.org/licenses/by-nc-sa/3.0/).  It is
    attributed to Denis Auroux and the original version can be found
    [here](http://ocw.mit.edu/courses/mathematics/18-02-multivariable-calculus-fall-2007/video-lectures/lecture-20-path-independence/).

-   **Reading: East Tennessee State University: Jeff Knisley’s
    Multivariable Calculus Online: “Chapter 5: Fundamental Theorems:”
    “5.3 Potentials of Conservative Fields”**
    Link: East Tennessee State University: Jeff Knisley’s *Multivariable
    Calculus Online:* [“Chapter 5: Fundamental Theorems: 5.3 Potentials
    of Conservative
    Fields”](http://math.etsu.edu/multicalc/prealpha/Chap5/Chap5-3/index.htm) (HTML
    and Java)  
        
     Instructions: Please read Parts 1-4 of Section 5.3.  Begin by
    reading “Part 1: Finding Potentials” which can be found through the
    link above, and then select the links to Parts 2-4 at the top of the
    webpage to continue reading.  
      
     This reading should take approximately 30 minutes to read and
    review.  
      
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

-   **Assessment: East Tennessee State University: Jeff Knisley’s
    Multivariable Calculus Online: “5.3 Potentials of Conservative
    Fields Exercises”**
    Link: East Tennessee State University: Jeff Knisley’s *Multivariable
    Calculus Online:* [“5.3 Potentials of Conservative Fields
    Exercises”](http://math.etsu.edu/multicalc/prealpha/Chap5/Chap5-3/index.htm) (HTML)  
        
     Instructions: Please click the link titled “Section 5.3: Potentials
    of Conservative Fields” above, and then, click on the link titled
    “Exercises” at the upper right corner of the webpage to redirect to
    the questions.  Try to solve exercises 7, 13, 21, and 27.  Check the
    solutions by clicking on the link titled [“Answers to Selected Odd
    Exercises”](http://math.etsu.edu/multicalc/prealpha/answers.htm) (PDF)
    on the main page, choose chapter 5, then locate section 5.3.  
      
     These exercises should take approximately 1 hour to complete.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**3.3 Fundamental Theorems** <span id="3.3"></span> 
**3.3.1 Gradient Fields** <span id="3.3.1"></span> 
-   **Lecture: MIT: Denis Auroux’s Multivariable Calculus: “Video
    Lecture 21: Gradient Fields”**
    Link: MIT: Denis Auroux’s *Multivariable Calculus:* [“Video Lecture
    21: Gradient
    Fields”](http://www.youtube.com/watch?v=YANh_22xmnc) (YouTube)  
        
     Also available in: [Adobe Flash, iTunes, or
    Mp4](http://ocw.mit.edu/courses/mathematics/18-02-multivariable-calculus-fall-2007/video-lectures/lecture-21-gradient-fields/)  
        
     Instructions: Please view the entire video lecture (50:11).  You
    may also click on the “Transcript” tab on the page to read the
    lecture.  
      
     This video should take approximately 1 hour and 15 minutes to watch
    and review.  
        
     Terms of Use: The video above is released under [Creative Commons
    Attribution-NonCommercial-ShareAlike
    3.0](http://creativecommons.org/licenses/by-nc-sa/3.0/).  It is
    attributed to Denis Auroux and the original version can be found
    [here](http://ocw.mit.edu/courses/mathematics/18-02-multivariable-calculus-fall-2007/video-lectures/lecture-21-gradient-fields/).

-   **Reading: MIT: Denis Auroux’s Multivariable Calculus: “III. Double
    Integrals and Line Integrals in the Plane”**
    Link: MIT: Denis Auroux’s *Multivariable Calculus:* [“III. Double
    Integrals and Line Integrals in the
    Plane”](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2012/09/MA103-Auroux-3.3.1.pdf) (PDF)  
        
     Instructions: Read the entire PDF document (5 pages).  Please note
    that this reading is paired with the video lecture above so please
    read it after watching the video.  
      
     This reading should take approximately 15 minutes to study.  
        
     Terms of Use: The article above is released under a [Creative
    Commons Attribution-NonCommercial-ShareAlike
    3.0](http://creativecommons.org/licenses/by-nc-sa/3.0/). It is
    attributed to Denis Auroux and the original version can be found
    [here](http://ocw.mit.edu/courses/mathematics/18-02-multivariable-calculus-fall-2007/lecture-notes/).

**3.3.2 Green’s Theorem** <span id="3.3.2"></span> 
-   **Lecture: MIT: Denis Auroux’s Multivariable Calculus: “Video
    Lecture 22: Green's Theorem”**
    Link: MIT: Denis Auroux’s *Multivariable Calculus:* [“Video Lecture
    22: Green's
    Theorem”](http://www.youtube.com/watch?v=aVksAaJ3qH8) (YouTube)  
        
     Also available in: [Adobe Flash, iTunes, or
    Mp4](http://ocw.mit.edu/courses/mathematics/18-02-multivariable-calculus-fall-2007/video-lectures/lecture-22-greens-theorem/)  
        
     Instructions: Please view the entire video lecture (46:45).  You
    may also click on the “Transcript” tab on the page to read the
    lecture.  
      
     This video should take approximately 1 hour to watch and review.  
        
     Terms of Use: The video above is released under [Creative Commons
    Attribution-NonCommercial-ShareAlike
    3.0](http://creativecommons.org/licenses/by-nc-sa/3.0/).  It is
    attributed to Denis Auroux and the original version can be found
    [here](http://ocw.mit.edu/courses/mathematics/18-02-multivariable-calculus-fall-2007/video-lectures/lecture-22-greens-theorem/).

-   **Reading: East Tennessee State University: Jeff Knisley’s
    Multivariable Calculus Online: “Chapter 5: Fundamental Theorems:”
    “5.4 Green's Theorem”**
    Link: East Tennessee State University: Jeff Knisley’s *Multivariable
    Calculus Online:* [“Chapter 5: Fundamental Theorems: 5.4 Green's
    Theorem”](http://math.etsu.edu/multicalc/prealpha/Chap5/Chap5-4/index.htm) (HTML)  
        
     Instructions: Please read Parts 1-4 of “Section 5.4: Green’s
    Theorem.”  Begin by reading “Part 1: Double Integrals and Boundary
    Curves” which is linked above, and then select the links to Parts
    2-4 at the top of the webpage to continue reading.  
      
     This reading should take approximately 30 minutes to study.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

-   **Assessment: East Tennessee State University: Jeff Knisley’s
    Multivariable Calculus Online: “5.4 Green’s Theorem Exercises”**
    Link: East Tennessee State University: Jeff Knisley’s *Multivariable
    Calculus Online:* [“5.4 Green's Theorem
    Exercises”](http://math.etsu.edu/multicalc/prealpha/Chap5/Chap5-4/index.htm) (HTML)  
        
     Instructions: Please click the link titled “Section 5.4: Green's
    Theorem” above, and then select the link titled “Exercises” at the
    upper right corner of the webpage to access the questions.  Complete
    exercises 1, 5, 19, 23, and 27.  You may check the solutions by
    clicking on the link titled [“Answers to Selected Odd
    Exercises”](http://math.etsu.edu/multicalc/prealpha/answers.htm) (PDF)
    on the main page, choose chapter 5, then locate section 5.4.  
      
     These exercises should take approximately 1 hour to complete.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

-   **Activity: The Saylor Foundation: Math Insight’s “The Idea Behind
    Green’s Theorem”**
    Link: The Saylor Foundation: Math Insight’s [“The Idea Behind
    Green’s
    Theorem”](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2012/10/MA103-The-Idea-Behind-Green’s-Theorem.pdf) (PDF)  
      
     Also Available in:  
     [HTML and Java](http://mathinsight.org/greens_theorem_idea)  
      
     \*NOTE: In order to view the Java applets within this resource you
    must click on the [HTML and
    Java](http://mathinsight.org/greens_theorem_idea) link, as the PDF
    version does not support the Java applets.   
      
     Instructions: Click on the webpage linked above and work through
    the notes and the applets. Feel free to work on more examples or
    read more sections by clicking the relevant links on the bottom of
    the page.   
      
     This activity should take approximately 30 minutes to complete.  
      
     Terms of Use: The linked resource above is released under
    a [Creative Commons Attribution-NonCommercial-ShareAlike 3.0
    Unported
    License](http://creativecommons.org/licenses/by-nc-sa/3.0/), it is
    attributed to Duane Q. Nykamp and the original version can be
    found [here](http://mathinsight.org/greens_theorem_idea).

**3.3.3 Flux** <span id="3.3.3"></span> 
-   **Lecture: MIT: Denis Auroux’s Multivariable Calculus: “Video
    Lecture 23: Flux”**
    Link: MIT: Denis Auroux’s *Multivariable Calculus:* [“Video Lecture
    23: Flux”](http://www.youtube.com/watch?v=6HeWHqh6xUY) (YouTube)  
        
     Also available in: [Adobe Flash, iTunes, or
    Mp4](http://ocw.mit.edu/courses/mathematics/18-02-multivariable-calculus-fall-2007/video-lectures/lecture-23-flux/)  
        
     Instructions: Please view the entire video lecture (50:13).  You
    may also click on the “Transcript” tab on the page to read the
    lecture.  
      
     This video should take approximately 1 hour and 15 minutes to watch
    and review.  
      
     Terms of Use:  The video above is released under [Creative Commons
    Attribution-NonCommercial-ShareAlike
    3.0](http://creativecommons.org/licenses/by-nc-sa/3.0/).  It is
    attributed to Denis Auroux and the original version can be found
    [here](http://ocw.mit.edu/courses/mathematics/18-02-multivariable-calculus-fall-2007/video-lectures/lecture-23-flux/).

**3.3.4 Simply Connected Region** <span id="3.3.4"></span> 
-   **Lecture: MIT: Denis Auroux’s Multivariable Calculus: “Video
    Lecture 24: Simply Connected Regions”**
    Link: MIT: Denis Auroux’s *Multivariable Calculus:* [“Video Lecture
    24: Simply Connected
    Regions”](http://www.youtube.com/watch?v=jZN_I1EiJSo) (YouTube)  
        
     Also available in: [Adobe Flash, iTunes, or
    Mp4](http://ocw.mit.edu/courses/mathematics/18-02-multivariable-calculus-fall-2007/video-lectures/lecture-24-simply-connected-regions/)  
      
     Instructions: Please view the entire video lecture (49:00).  You
    may also click on the “Transcript” tab on the page to read the
    lecture.  
      
     This video should take approximately 1 hour and 15 minutes to watch
    and review.  
        
     Terms of Use: The video above is released under [Creative Commons
    Attribution-NonCommercial-ShareAlike
    3.0](http://creativecommons.org/licenses/by-nc-sa/3.0/).  It is
    attributed to Denis Auroux and the original version can be found
    [here](http://ocw.mit.edu/courses/mathematics/18-02-multivariable-calculus-fall-2007/video-lectures/lecture-24-simply-connected-regions/).

-   **Reading: MIT: Denis Auroux’s Multivariable Calculus: “III. Double
    Integrals and Line Integrals in the Plane”**
    Link: MIT: Denis Auroux’s *Multivariable Calculus:* [“III. Double
    Integrals and Line Integrals in the
    Plane”](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2012/09/MA103-Auroux-3.3.4.pdf) (PDF)  
        
     Instructions: Read the entire PDF document (4 pages) found in the
    link above.  Please note that this reading is paired with the video
    lecture above so please read it after watching the video.  
      
     This reading should take approximately 15 minutes to study.  
        
     Terms of Use: The article above is released under a [Creative
    Commons Attribution-NonCommercial-ShareAlike
    3.0](http://creativecommons.org/licenses/by-nc-sa/3.0/). It is
    attributed to Denis Auroux and the original version can be found
    [here](http://ocw.mit.edu/courses/mathematics/18-02-multivariable-calculus-fall-2007/lecture-notes/).


