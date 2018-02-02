Answers.md -
> If you had to teach someone with basic knowledge of a CSS preprocessor how would you describe it?

Pre-processors extend CSS with variables, operators, interpolations, functions, mixins and many more other usable assets. Some cool things about preprocessors:
Using one allows you to use mixins like simple javascript functions, passing variables in etc. You can use @extend to attribute a set of one class' attributes to another class also. Another thing students might mention is that you can use mathematical operators to adjust layout variables in relation to others,  for example: padding-top:  $nav-height +40px;. You can also use for loops  by using the @for keyword or the other kinds of loops utilizing @each, @while etc.

> What is the command in node package manager (nom) to install LESS globally on your computer?
Prove that they understand the global install by providing
command NPM install -g less

>Please provide an example of a mixin you have used in a project this week:
Will vary student to student, just look at syntax.

>What is the difference between fixed, adaptive and fluid?
Fixed means that everything is hard coded pixels.
Adaptive means you’ve introduced breakpoints.
Fluid means breakpoints and percent points

>Why do we need to use the CSS property max width in a responsive website?
We need to have restraints otherwise it would be 100 percent of the screen.
