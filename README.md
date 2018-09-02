# ceng444: Language processors
Middle East Technical University CENG introductory compiler course

This is the website of the course when I teach it. 

<b>Term</b>: Fall 2018

<b>Instructor</b>: Cem Bozsahin.  TA: TBA

<b>Office hours</b>: Open door except lecture days (i.e. except TTh this term)
 
<b>Textbook</b>:
Engineering a compiler</b>, by keith Cooper and Linda Torczon, 2nd ed,
Morgan Kaufmann, 2012

<b>Catalog description</b>: Formal description and classification of programming languages. Syntactic specification. The parsing problem. Top-down and bottom-up parsing. Attaching semantics to syntax. Translator writing systems. Translator writing case study.

<b>Course objectives</b>: Assuming familiarity with formal grammars, i.e., Ceng280 material, we emphasize modern tools and techniques for compiler construction, which can be used for any task of mapping from one formal representation to another.

<b>Course outline</b>

<ol>
<li> Introduction: a walk through all stages of compiling (1 week)
<li> Scanning (lexical analysis) (1)
<li> Parsing (syntactic analysis) (3)
<li> Intermediate code (1)
<li> Virtual machines (1)
<li> Code generation (syntax-directed translation) (2)
<li> Scope handling and run-time (2)
</ol>

<b>Course conduct</b>: 11 weeks of lecture, 2 weeks of in-class labs; 1 week in-class exam.
<p>We will use two tools for compiling, <a href="http://www.antlr.org/">antLR</a>
for LL, and LALR parser of Mark Johnson.
There is an interface to LALR parser written by me, called<a href="https://github.com/bozsahin/yalalr">yalalr</a>, which
is available at my github repo.
<p>In-class labs introduce antLR and yalalr (and Lisp on which it is based.)

<b>Grading</b>:
<ol>
<li> Mid-term exam: %25
<li> mini-project 1 (LL parsing): %20
<li> mini-project 2 (LALR parsing): %30
<li> Final exam: %25
</ol>
