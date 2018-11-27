---
layout: default
title: "MA103: Multivariable Calculus"
course_description: "An examination of the definitions of the basic trigonometric functions and their properties, trigonometric equations and identities, the laws of sines and cosines, polar coordinates and graphs, parametric equations, and elementary vector operations."
next: ../Unit03
previous: ../Unit01
---
**Unit 2: Partial Differentiation** <span id="2"></span> 
*For single-variable functions, the derivative of the graph at a
specified point is the slope of the tangent line at that point.  This is
because the dependent variable is only changing with regards to a single
independent variable.  In this course, we will consider functions of
multiple variables.  Because these functions have outputs that depend on
multiple variables, each variable contributes to the rate of change of
the function independently.  Thus, we refer to the function’s rate of
change with respect to a single specified variable as a* partial
derivative*, as it does not describe the entire rate of change of the
function.  Moreover, for functions of multiple variables, there will no
longer be a single tangent line at a specified point.  For example, in
the case of a function of two variables, we consider a tangent plane as
opposed to a tangent line.  The concept of a partial derivative is
important to study concepts such as tangent spaces, extrema, etc. in the
context of functions of 2 or more variables. *  
    
 *As in Single-Variable Calculus, Multivariable Calculus studies the
maximum and minimum values for given functions due to their numerous
applications.  Lagrange Multipliers is a method of finding maximum and
minimum values for functions subject to constraints that uses partial
derivatives; however, the idea of optimization with constraints has no
one-variable analogue.*  
    
 *Again, you should focus on the geometric meaning of the concepts
introduced in this unit.*

**Unit 2 Time Advisory**  
This unit will take you approximately 25.5 hours to complete.  
  
 ☐    Subunit 2.1: 9.25 hours
  
 ☐    Subunit 2.1.1: 1.75 hour  
  
 ☐    Subunit 2.1.2: 1.25 hour  
  
 ☐    Subunit 2.1.3: 1.25 hour  
  
 ☐    Subunit 2.1.4: 5 hours

☐    Subunit 2.2: 16.25 hours
  
 ☐    Subunit 2.2.1: 4.5 hours  
  
 ☐    Subunit 2.2.2: 3.25 hours  
  
 ☐    Subunit 2.2.3: 4.75 hours  
  
 ☐    Subunit 2.2.4: 3.75 hours

**Unit2 Learning Outcomes**  
Upon successful completion of this unit, the student will be able to:  
  
-   Determine the domain of a function.
-   Determine whether the domain of a function is open or closed,
    bounded or unbounded, connected or not connected.
-   Sketch the graph of the domain of a function.
-   Sketch the graph of a given function.
-   Identify the characteristics of a function from a graph of its level
    curves.
-   Evaluate limits.
-   Show that limits do not exist by evaluating the limit along two
    different paths.
-   Determine whether a given function is continuous.
-   Evaluate partial derivatives.
-   Evaluate higher order partial derivatives.
-   Describe the geometrical significance of a directional derivative. 
-   Find the directional derivative.
-   Describe the relation between existence of partial derivatives,
    continuity, and differentiability.
-   Evaluate derivatives of functions using the chain rule.
-   Use the method of Lagrange Multipliers to find the extrema of
    functions subject to constraints.

**2.1 Partial Derivatives** <span id="2.1"></span> 
**2.1.1 Level Curves and Partial Derivatives** <span id="2.1.1"></span> 
-   **Activity: The Saylor Foundation: Math Insight's “Level Sets”**
    Link: The Saylor Foundation: <span
    style="background-color: transparent; background-image: initial; background-attachment: initial; background-origin: initial; background-clip: initial; ">Math
    Insight’s </span>[“Level
    Sets”](https://resources.saylor.org/archived/wp-content/uploads/2012/10/MA103-Level-Sets.pdf)<span
    style="background-color: transparent;"> (PDF)  
      
     Also Available in:  
     [HTML and Java](http://mathinsight.org/level_sets)</span>  
      
     NOTE: In order to view the Java applets within this resource you
    must click on the [HTML and
    Java](http://mathinsight.org/level_sets) link, as the PDF version
    does not support the Java applets.   
      
     <span style="background-color: transparent;"> Instructions: Please
    click on the webpage linked above and work through the notes and the
    applets. Feel free to go through more examples by clicking on the
    link at the bottom of the page. </span>  
      
     This activity should take approximately 1 hour to complete.  
      
     Terms of Use: The linked resource above is released under
    a [Creative Commons Attribution-NonCommercial-ShareAlike 3.0
    Unported
    License](http://creativecommons.org/licenses/by-nc-sa/3.0/), it is
    attributed to Duane Q. Nykamp and the original version can be
    found [here](http://mathinsight.org/level_sets). 

-   **Lecture: MIT: Denis Auroux’s Multivariable Calculus: “Video
    Lecture 8: Partial Derivatives”**
    Link: MIT: Denis Auroux’s *Multivariable Calculus: *[“Video Lecture
    8: Partial
    Derivatives”](http://www.youtube.com/watch?v=iFJgBQnOXx8) (Adobe
    Flash, iTunes or Mp4)  
        
     Also available in: [Adobe Flash, iTunes or
    Mp4](http://ocw.mit.edu/courses/mathematics/18-02-multivariable-calculus-fall-2007/video-lectures/lecture-8-partial-derivatives/)  
        
     Instructions: Please view the entire video lecture (46:13).  You
    may also click on the “Transcript” tab on the page to read the
    lecture.  
      
     This reading should take approximately 15 minutes to read and
    review.  
        
     Terms of Use: The video above is released under [Creative Commons
    Attribution-NonCommercial-ShareAlike
    3.0](http://creativecommons.org/licenses/by-nc-sa/3.0/).  It is
    attributed to Denis Auroux and the original version can be found
    [here](http://ocw.mit.edu/courses/mathematics/18-02-multivariable-calculus-fall-2007/video-lectures/lecture-8-partial-derivatives/). 

-   **Reading: MIT: Denis Auroux’s Multivariable Calculus: “II. Partial
    Derivatives:”**
    Link: MIT: Denis Auroux’s *Multivariable Calculus:* [“II. Partial
    Derivatives”](https://resources.saylor.org/archived/wp-content/uploads/2012/09/MA103-Auroux-2.1.1.pdf) (PDF)  
        
     Instructions: Read the entire PDF document (4 pages).  Please note
    that this reading is paired with the video lecture above so please
    read it after watching the video.  
      
     This activity should take approximately 15 minutes to complete.  
        
     Terms of Use: The article above is released under a [Creative
    Commons Attribution-NonCommercial-ShareAlike
    3.0](http://creativecommons.org/licenses/by-nc-sa/3.0/). It is
    attributed to Denis Auroux and the original version can be found
    [here](http://ocw.mit.edu/courses/mathematics/18-02-multivariable-calculus-fall-2007/lecture-notes/lec_week8.pdf).

**2.1.2 Max-Min Problems and Least Squares** <span id="2.1.2"></span> 
-   **Lecture: MIT: Denis Auroux’s Multivariable Calculus: “Video
    Lecture 9: Max-Min and Least Squares”**
    Link: MIT: Denis Auroux’s *Multivariable Calculus:* [“Video Lecture
    9: Max-Min and Least
    Squares”](http://www.youtube.com/watch?v=Snao6tXt-P4) (Youtube)  
        
     Also available in: [ Adobe Flash, iTunes, or
    Mp4](http://ocw.mit.edu/courses/mathematics/18-02-multivariable-calculus-fall-2007/video-lectures/lecture-9-max-min-and-least-squares/)  
        
     Instructions: Please view the entire lecture (49:44).  You may also
    click on the “Transcript” tab on the page to read the lecture.  
        
     Terms of Use: The video above is released under [Creative Commons
    Attribution-NonCommercial-ShareAlike
    3.0](http://creativecommons.org/licenses/by-nc-sa/3.0/).  It is
    attributed to Denis Auroux and the original version can be found
    [here](http://ocw.mit.edu/courses/mathematics/18-02-multivariable-calculus-fall-2007/video-lectures/lecture-9-max-min-and-least-squares/).

**2.1.3 Second Derivative Test** <span id="2.1.3"></span> 
-   **Lecture: MIT: Denis Auroux’s Multivariable Calculus: “Video
    Lecture 10: Second Derivative Test”**
    Link: MIT: Denis Auroux’s *Multivariable Calculus:* [“Video Lecture
    10: Second Derivative
    Test”](http://www.youtube.com/watch?v=a4u6kmRUZwY) (YouTube)  
        
     Also available in: [Adobe Flash, iTunes, or
    Mp4](http://ocw.mit.edu/courses/mathematics/18-02-multivariable-calculus-fall-2007/video-lectures/lecture-10-second-derivative-test/)  
        
     Instructions: Please view the entire lecture (52:18).  You may also
    click on the “Transcript” tab on the page to read the lecture.  
      
     This video should take approximately 1 hour and 15 minutes to watch
    and review.  
        
     Terms of Use: The video above is released under [Creative Commons
    Attribution-NonCommercial-ShareAlike
    3.0](http://creativecommons.org/licenses/by-nc-sa/3.0/).  It is
    attributed to Denis Auroux and the original version can be found
    [here](http://ocw.mit.edu/courses/mathematics/18-02-multivariable-calculus-fall-2007/video-lectures/lecture-10-second-derivative-test/).

**2.1.4 Limits, Continuity, and Partial Differentiation** <span
id="2.1.4"></span> 
-   **Reading: East Tennessee State University: Jeff Knisley’s
    Multivariable Calculus Online: “Chapter 2: Partial Differentiation:”
    “2.1 Functions of 2 Variables,” “2.2 Limits and Continuity,” and
    “2.3 Partial Derivatives”**
    Links: East Tennessee State University: Jeff Knisley’s
    *Multivariable Calculus Online:* “Chapter 2: Partial
    Differentiation:” [“2.1 Functions of 2
    Variables,”](http://math.etsu.edu/multicalc/prealpha/Chap2/Chap2-1/index.htm) (HTML
    and Java) [“2.2 Limits and
    Continuity,”](http://math.etsu.edu/multicalc/prealpha/Chap2/Chap2-2/index.htm) (HTML)
    and [“2.3 Partial
    Derivatives”](http://math.etsu.edu/multicalc/prealpha/Chap2/Chap2-3/index.htm) (HTML
    and Java)  
        
     Instructions: Please click on each link above to sections “2.1
    Functions of 2 Variables,” “2.2 Limits and Continuity,” and “2.3
    Partial Derivatives.”  Read all four parts for each individual
    section.  Begin by reading the first webpage for each section linked
    above, and then select the other Parts at the top of each webpage to
    continue reading (After finishing Part 4 of "2.3 Partial
    Derivatives", you will have read 12 Parts total).  
      
     This reading should take approximately 1 hour and 30 minutes to
    complete.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

-   **Assessment: East Tennessee State University: Jeff Knisley’s
    Multivariable Calculus Online: “Functions of 2 Variables Exercises,”
    “Limits and Continuity Exercises,” and “Partial Derivatives
    Exercises”**
    Link: East Tennessee State University: Jeff Knisley’s *Multivariable
    Calculus Online:* [“Functions of 2 Variables
    Exercises,”](http://math.etsu.edu/multicalc/prealpha/Chap2/Chap2-1/index.htm) (HTML
    and Java) [“Limits and Continuity
    Exercises,”](http://math.etsu.edu/multicalc/prealpha/Chap2/Chap2-2/index.htm) (HTML)
    and [“Partial Derivatives
    Exercises”](http://math.etsu.edu/multicalc/prealpha/Chap2/Chap2-3/index.htm) (HTML
    and Java)  
        
     Instructions: Please click on the “Functions of 2 Variables
    Exercises” link above, and at the top of this webpage, click on the
    “Exercises” link to access the question sets.  Work through
    exercises 7, 9, 15, 19, and 25.  Similarly, click on the “Limits and
    Continuity Exercises” link above, and once on the webpage, select
    the “Exercises” link at the top of the webpage to access the
    question sets.  Complete exercises 5, 13, 17, and 25.  Finally,
    click on the “Partial Derivatives Exercises” link above, and at the
    top of this webpage, click on the “Exercises” link to be redirected
    to the question sets.  Try to solve exercises 5, 11, 19, 25, and
    29.  Check the solutions by clicking on the link titled [“Answers to
    Selected Odd
    Exercises”](http://math.etsu.edu/multicalc/prealpha/answers.htm) (PDF)
    on the main page, choosing chapter 2, and then finding sections
    2.1-2.3.  
      
     These exercises should take approximately 3 hours to complete.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

-   **Activity: The Saylor Foundation: Math Insight's "Introduction to
    Partial Derivatives"**
    Link: The Saylor Foundation: <span
    style="background-color: transparent; background-image: initial; background-attachment: initial; background-origin: initial; background-clip: initial; ">Math
    Insight’s </span> [“](https://resources.saylor.org/archived/wp-content/uploads/2012/10/MA103-Introduction-to-Partial-Derivatives.pdf)[I](https://resources.saylor.org/archived/wp-content/uploads/2012/10/MA103-Introduction-to-Partial-Derivatives.pdf)[n](https://resources.saylor.org/archived/wp-content/uploads/2012/10/MA103-Introduction-to-Partial-Derivatives.pdf)[troduction
    to Partial
    Derivatives”](https://resources.saylor.org/archived/wp-content/uploads/2012/10/MA103-Introduction-to-Partial-Derivatives.pdf) (PDF<span
    style="background-color: transparent;">)  
      
     Also Available in:  
     [HTML and
    Java](http://mathinsight.org/partial_derivative_introduction)</span>  
      
     \*NOTE: In order to view the Java applets within this resource you
    must click on the [HTML and
    Java](http://mathinsight.org/partial_derivative_introduction) link,
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
    found [here](http://mathinsight.org/partial_derivative_introduction).

**2.2 Differentiation and Chain Rule** <span id="2.2"></span> 
**2.2.1 Chain Rule** <span id="2.2.1"></span> 
-   **Lecture: MIT: Denis Auroux’s Multivariable Calculus: “Video
    Lecture 11: Chain Rule”**
    Link: MIT: Denis Auroux’s *Multivariable Calculus:* [“Video Lecture
    11: Chain
    Rule”](http://www.youtube.com/watch?v=gyzLA-J9OXs) (YouTube)  
      
     Also available in: [Adobe Flash, iTunes, or
    Mp4](http://ocw.mit.edu/courses/mathematics/18-02-multivariable-calculus-fall-2007/video-lectures/lecture-11-chain-rule/)  
        
     Instructions: Please view the entire lecture (50:09).  You may also
    click on the “Transcript” tab on the page to read the lecture.  
        
     Terms of Use: The video above is released under [Creative Commons
    Attribution-NonCommercial-ShareAlike
    3.0](http://creativecommons.org/licenses/by-nc-sa/3.0/).  It is
    attributed to Denis Auroux and the original version can be found
    [here](http://ocw.mit.edu/courses/mathematics/18-02-multivariable-calculus-fall-2007/video-lectures/lecture-11-chain-rule/).

-   **Reading: MIT: Denis Auroux’s Multivariable Calculus: “II. Partial
    Derivatives”**
    Link: MIT: Denis Auroux’s *Multivariable Calculus:* [“II. Partial
    Derivatives”](https://resources.saylor.org/archived/wp-content/uploads/2012/09/MA103-Auroux-2.2.1.pdf) (PDF)  
        
     Instructions: Read the entire PDF file (4 pages). Please note that
    this reading is paired with the video lecture above so please read
    it after watching the video.  
        
     Terms of Use: The article above is released under a [Creative
    Commons Attribution-NonCommercial-ShareAlike
    3.0](http://creativecommons.org/licenses/by-nc-sa/3.0/). It is
    attributed to Denis Auroux and the original version can be found
    [here](http://ocw.mit.edu/courses/mathematics/18-02-multivariable-calculus-fall-2007/lecture-notes/).

-   **Reading: East Tennessee State University: Jeff Knisley’s
    Multivariable Calculus Online: “Chapter 2: Partial Differentiation:”
    “2.5 Linearization and the Hessian” and “2.6 The Chain Rule”**
    Links: East Tennessee State University: Jeff Knisley’s
    *Multivariable Calculus Online:* “Chapter 2: Partial
    Differentiation:” [“2.5 Linearization and the
    Hessian”](http://math.etsu.edu/multicalc/prealpha/Chap2/Chap2-5/index.htm) (HTML
    and Java) and [“2.6 The Chain
    Rule”](http://math.etsu.edu/multicalc/prealpha/Chap2/Chap2-6/index.htm) (HTML)  
        
     Instructions: Please click the links titled “Section 2.5
    Linearization and the Hessian” and “Section 2.6 The Chain Rule”
    above.  For each section, read Parts 1-4 in their entirety.  You may
    access each part by clicking on the links at the top of each
    webpage.  
      
     These exercises should take approximately 3 hours to complete.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

-   **Assessment: East Tennessee State University: Jeff Knisley’s
    Multivariable Calculus Online: “2.5 Linearization and the Hessian”
    and “2.6 The Chain Rule”**
    Link: East Tennessee State University: Jeff Knisley’s *Multivariable
    Calculus Online:* [“2.5 Linearization and the
    Hessian”](http://math.etsu.edu/multicalc/prealpha/Chap2/Chap2-5/index.htm) (HTML)
    and [“2.6 The Chain
    Rule”](http://math.etsu.edu/multicalc/prealpha/Chap2/Chap2-6/index.htm) (HTML)  
        
     Instructions: Please click the link titled “2.5 Linearization and
    the Hessian” posted above, and then select the “Exercises” link at
    the top of the webpage to access the questions.  Try to solve
    exercises 1, 9, 21, and 27.  Then, click on the “2.6 The Chain Rule”
    link posted above, and select the “Exercises” link at the upper
    right corner of the webpage to access the questions.  Complete
    exercises 5, 13, and 23.  Check the solutions by clicking on the
    link titled [“Answers to Selected Odd
    Exercises”](http://math.etsu.edu/multicalc/prealpha/answers.htm) (PDF)
    on the main page, choosing chapter 2, and then scrolling down to
    find sections 2.5 and 2.6.  
      
     These exercises should take approximately 2 hours to complete.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**2.2.2 Gradient** <span id="2.2.2"></span> 
-   **Lecture: MIT: Denis Auroux’s Multivariable Calculus: “Video
    Lecture 12: Gradient”**
    Link: MIT: Denis Auroux’s *Multivariable Calculus:* [“Video Lecture
    12:
    Gradient”](http://www.youtube.com/watch?v=WrJlu-1XK2A) (YouTube)  
        
     Also available in: [Adobe Flash, iTunes, or
    Mp4](http://ocw.mit.edu/courses/mathematics/18-02-multivariable-calculus-fall-2007/video-lectures/lecture-12-gradient/)  
      
     Instructions: Please view entire video lecture (50:10).  You may
    also click on the “Transcript” tab on the page to read the
    lecture.  
      
     This video should take approximately 1 hour and 15 minutes to watch
    and review.  
        
     Terms of Use: The video above is released under [Creative Commons
    Attribution-NonCommercial-ShareAlike
    3.0](http://creativecommons.org/licenses/by-nc-sa/3.0/).  It is
    attributed to Denis Auroux and the original version can be found
    [here](http://ocw.mit.edu/courses/mathematics/18-02-multivariable-calculus-fall-2007/video-lectures/lecture-12-gradient/).

-   **Reading: East Tennessee State University: Jeff Knisley’s
    Multivariable Calculus Online: “Chapter 2: Partial Differentiation:”
    “2.7 Properties of the Gradient”**
    Link: East Tennessee State University: Jeff Knisley’s *Multivariable
    Calculus Online:* “Chapter 2: Partial Differentiation:” [“2.7
    Properties of the
    Gradients”](http://math.etsu.edu/multicalc/prealpha/Chap2/Chap2-7/index.htm) (HTML
    and Java)  
        
     Instructions: Please read all four parts of “2.7 Properties of the
    Gradients.”  Begin by reading “Part 1: Gradients and Level Curves”
    linked above, and then select the links for Parts 2-4 at the top of
    the webpage to continue reading.  
      
     This reading should take approximately 30 minutes to read and
    review.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

-   **Assessment: East Tennessee State University: Jeff Knisley’s
    Multivariable Calculus Online: “2.7 Properties of the Gradients
    Exercises”**
    Link: East Tennessee State University: Jeff Knisley’s *Multivariable
    Calculus Online:* [“2.7 Properties of the Gradients
    Exercises”](http://math.etsu.edu/multicalc/prealpha/Chap2/Chap2-7/index.htm) (HTML)  
        
     Instructions: Please click on the link above titled “2.7 Properties
    of the Gradients Exercises.”  On this webpage, click on the link
    titled “Exercises” at the upper right corner of the webpage to
    access the questions.  Try to complete exercises 3, 13, and 15. 
    Check the solutions by clicking on the link titled [“Answers to
    Selected Odd
    Exercises”](http://math.etsu.edu/multicalc/prealpha/answers.htm) (PDF)
    on the main page, choosing chapter 2, and scrolling down to section
    2.7.  
        
     These exercises should take approximately 1 hour to complete.  
      
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

-   **Activity: The Saylor Foundation: Math Insight's “An Introduction
    to the Directional Derivative and the Gradient”**
    Link: The Saylor Foundation: <span
    style="background-color: transparent; background-image: initial; background-attachment: initial; background-origin: initial; background-clip: initial; ">Math
    Insight’s
    </span>[“](https://resources.saylor.org/archived/wp-content/uploads/2012/10/MA103-An-Introduction-to-the-Directional-Derivative-and-the-Gradient.pdf)[A](https://resources.saylor.org/archived/wp-content/uploads/2012/10/MA103-An-Introduction-to-the-Directional-Derivative-and-the-Gradient.pdf)[n
    Introduction to the Directional Derivative and the
    Gradient”](https://resources.saylor.org/archived/wp-content/uploads/2012/10/MA103-An-Introduction-to-the-Directional-Derivative-and-the-Gradient.pdf)<span
    style="background-color: transparent;"> (PDF)  
      
     Also Available in:  
     [HTML and
    Java](http://mathinsight.org/directional_derivative_gradient_introduction)</span>  
      
     \*NOTE: In order to view the Java applets within this resource you
    must click on the [HTML and
    Java](http://mathinsight.org/directional_derivative_gradient_introduction) link,
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
    found [here](http://mathinsight.org/directional_derivative_gradient_introduction).

**2.2.3 Optimization and Lagrange Multipliers** <span
id="2.2.3"></span> 
-   **Lecture: MIT: Denis Auroux’s Multivariable Calculus: “Video
    Lecture 13: Lagrange Multipliers”**
    Link: MIT: Denis Auroux’s *Multivariable Calculus:* [“Video Lecture
    13: Lagrange
    Multipliers”](http://www.youtube.com/watch?v=y6UUOxeIK6w) (YouTube)  
        
     Also available in: [Adobe Flash, iTunes, or
    Mp4](http://ocw.mit.edu/courses/mathematics/18-02-multivariable-calculus-fall-2007/video-lectures/lecture-13-lagrange-multipliers/)  
        
     Instructions: Please view the entire video lecture (50:10).  You
    may also click on the “Transcript” tab on the page to read the
    lecture.  
      
     This video should take approximately 1 hour and 15 minutes to watch
    and review.  
        
     Terms of Use: The video above is released under [Creative Commons
    Attribution-NonCommercial-ShareAlike
    3.0](http://creativecommons.org/licenses/by-nc-sa/3.0/).  It is
    attributed to Denis Auroux and the original version can be found
    [here](http://ocw.mit.edu/courses/mathematics/18-02-multivariable-calculus-fall-2007/video-lectures/lecture-13-lagrange-multipliers/).

-   **Reading: East Tennessee State University: Jeff Knisley’s
    Multivariable Calculus Online: “Chapter 2: Partial Differentiation:”
    “2.8 Optimization” and “2.9 Lagrange Multipliers”**
    Links: East Tennessee State University: Jeff Knisley’s
    *Multivariable Calculus Online:* “Chapter 2: Partial
    Differentiation:” [“2.8
    Optimization”](http://math.etsu.edu/multicalc/prealpha/Chap2/Chap2-8/index.htm) (HTML
    and Java) and [“2.9 Lagrange
    Multipliers”](http://math.etsu.edu/multicalc/prealpha/Chap2/Chap2-9/index.htm) (HTML
    and Java)  
      
     Instructions: Please click the links titled “Section 2.8
    Optimization” and “Section 2.9 Lagrange Multipliers” found above. 
    Read Parts 1-4 of each section.  Make sure to click on the links to
    each part at the top of each webpage to complete this reading
    assignment.  
      
     This reading should take approximately 1 hour to read and review.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

-   **Assessment: East Tennessee State University: Jeff Knisley’s
    Multivariable Calculus Online: “2.8 Optimization Exercises” and “2.9
    Lagrange Multipliers Exercises”**
    Link: East Tennessee State University: Jeff Knisley’s *Multivariable
    Calculus Online:* [“2.8 Optimization
    Exercises”](http://math.etsu.edu/multicalc/prealpha/Chap2/Chap2-8/index.htm) (HTML
    and Java) and [“2.9 Lagrange Multipliers
    Exercises”](http://math.etsu.edu/multicalc/prealpha/Chap2/Chap2-9/index.htm) (HTML
    and Java)  
        
     Instructions: Please click on the link above titled “2.8
    Optimization Exercises”, and then select the “Exercises” link at the
    top right corner of the webpage to access the question sets.  Solve
    exercises 1, 17, and 25.  Similarly, click on the link titled “2.9
    Lagrange Multipliers Exercises” above, and then click on the link
    titled “Exercises” at the upper right corner of the webpage to
    access the questions.  Work on exercises 5, 7, and 15.  Check the
    solutions by clicking on the link titled [“Answers to Selected Odd
    Exercises”](http://math.etsu.edu/multicalc/prealpha/answers.htm) (PDF)
    on the main page, choosing chapter 2, and scrolling down to sections
    2.8 and 2.9.  
      
     These exercises should take approximately 2 hours to complete.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

-   **Activity: University of Minnesota: Jonathan Rogness’ Multivariable
    Calculus and Vector Analysis: “Lagrange Multipliers”**
    Link: <span
    style="background-color: transparent; background-image: initial; background-attachment: initial; background-origin: initial; background-clip: initial; ">University
    of Minnesota: Jonathan Rogness’ </span>*<span
    style="background: transparent">Multivariable Calculus and Vector
    Analysis</span>*<span
    style="background-color: transparent; background-image: initial; background-attachment: initial; background-origin: initial; background-clip: initial; ">:
    </span>[“Lagrange
    Multipliers”](http://www.math.umn.edu/%7Erogness/multivar/lagrange/lagrange_demos.shtml) (HTML<span
    style="background-color: transparent;"> and Java)  
      
     Instructions: Click on the webpage linked above and work through
    the notes and the applets.  </span>  
      
     This activity should take approximately 30 minutes to complete.  
      
     <span
    style="background-color: transparent; background-image: initial; background-attachment: initial; background-origin: initial; background-clip: initial; ">
    Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.</span>

**2.2.4 Partial Differential Equations** <span id="2.2.4"></span> 
-   **Lecture: MIT: Denis Auroux’s Multivariable Calculus: “Video
    Lecture 14: Non-Independent Variables” and “Video Lecture 15:
    Partial Differential Equations”**
    Links: MIT: Denis Auroux’s *Multivariable Calculus:* [“Video Lecture
    14: Non-Independent
    Variables”](http://www.youtube.com/watch?v=UPJLMJ-0nrE) (YouTube)
    and [“Video Lecture 15: Partial Differential
    Equations”](http://www.youtube.com/watch?v=WPV1drQ5lww) (YouTube)  
        
     Also available in:     
     [Adobe Flash, iTunes, or
    Mp4](http://ocw.mit.edu/courses/mathematics/18-02-multivariable-calculus-fall-2007/video-lectures/lecture-14-non-independent-variables/) (Lecture
    14)  
     [Adobe Flash, iTunes, or
    Mp4](http://ocw.mit.edu/courses/mathematics/18-02-multivariable-calculus-fall-2007/video-lectures/lecture-15-partial-differential-equations/) (Lecture
    15)  
      
     Instructions: Please view the video lectures in their entirety
    (49:11 and 45:23, respectively).  You may also click on the
    “Transcript” tab on the page to read the lecture.  
        
     Terms of Use: The video above is released under [Creative Commons
    Attribution-NonCommercial-ShareAlike
    3.0](http://creativecommons.org/licenses/by-nc-sa/3.0/).  It is
    attributed to Denis Auroux and the original version can be found
    [here](http://ocw.mit.edu/courses/mathematics/18-02-multivariable-calculus-fall-2007/video-lectures/lecture-14-non-independent-variables/)
    (Lecture 14) and
    [here](http://ocw.mit.edu/courses/mathematics/18-02-multivariable-calculus-fall-2007/video-lectures/lecture-15-partial-differential-equations/)
    (Lecture 15). 

-   **Reading: MIT: Denis Auroux’s Multivariable Calculus: “II. Partial
    Derivatives:”**
    Link: MIT: Denis Auroux’s *Multivariable Calculus:* [“II. Partial
    Derivatives”](https://resources.saylor.org/archived/wp-content/uploads/2012/09/MA103-Auroux-2.2.41.pdf) (PDF)  
        
     Instructions: Open the link above and read the entire PDF document
    (3 pages).  Please note that this reading is paired with the video
    lecture above so please read it after watching the video.  
      
     This reading should take approximately 15 minutes to study.  
        
     Terms of Use: The article above is released under a [Creative
    Commons Attribution-NonCommercial-ShareAlike
    3.0](http://creativecommons.org/licenses/by-nc-sa/3.0/). It is
    attributed to Denis Auroux and the original version can be found
    [here](http://ocw.mit.edu/courses/mathematics/18-02-multivariable-calculus-fall-2007/lecture-notes/).

-   **Reading: East Tennessee State University: Jeff Knisley’s
    Multivariable Calculus Online: “Chapter 2: Partial Differentiation:”
    “2.4: Partial Differential Equations”**
    Link: East Tennessee State University: Jeff Knisley’s *Multivariable
    Calculus Online:* “Chapter 2: Partial Differentiation:” [“2.4:
    Partial Differential
    Equations”](http://math.etsu.edu/multicalc/prealpha/Chap2/Chap2-4/index.htm) (HTML)  
        
     Instructions: Please read Parts 1-4 of “Section 2.4: Partial
    Differential Equations” from the link posted above.  Begin by
    reading “Part 1: Partial Differential Equations” linked above, and
    then click on the links to Parts 2-4 at the top of the webpage.  
      
     This reading should take approximately 30 minutes to study.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

-   **Assessment: East Tennessee State University: Jeff Knisley’s
    Multivariable Calculus Online: “2.4: Partial Differential Equations
    Exercises”**
    Link: East Tennessee State University’s Jeff Knisley’s
    *Multivariable Calculus Online:* [“2.4: Partial Differential
    Equations
    Exercises”](http://math.etsu.edu/multicalc/prealpha/Chap2/Chap2-4/index.htm) (HTML)  
        
     Instructions: Please click on the “2.4: Partial Differential
    Equations Exercises” link above, and once on the webpage, click on
    the “Exercises” link at the top right corner of the webpage to
    redirect to the exercise sets.  Complete exercises 11, 21, and 23. 
    Check the solutions by clicking on the link titled [“Answers to
    Selected Odd
    Exercises”](http://math.etsu.edu/multicalc/prealpha/answers.htm) (PDF)
    on the main page, choosing chapter 2, and scrolling down to section
    2.4.  
      
     These exercises should take approximately 1 hour to complete.  
                         
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.


