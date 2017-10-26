
# Lurch Web Platform, Complex Example Application

Actually, it's not complex.  A better name might be "second example
application," but since
[the first one](https://github.com/lurchmath/lwp-example-simple)
was called "simple," this one had to be called complex by contrast.
It remains one of the smallest uses of the
[Lurch Web Platform](https://github.com/lurchmath/lurch),
provided as an example for others to imitate/customize when building
applications on the same platform.

[Visit the live app here.](https://lurchmath.github.io/lwp-example-complex)
It has only a few features beyond ordinary word processing.

Example feature 1:

 * Highlight a section of text and click the red `[ ]` toolbar button.
 * You should see a group form, inside of which you can type expressions
   of basic arithemtic, such as `2+2`.
 * After an artificial delay (which simulates lengthy background
   processing) you should see the answer appear.
 * As in the
   [simple example app](https://github.com/lurchmath/lwp-example-simple),
   groups are visible only when your cursor is inside them.

Example feature 2:

 * Highlight a few words of text and click the green `( )` toolbar button.
 * You should see an assessment of whether those words are a name.
 * Phrases like "John Smith" and "Mary Martinez" will be judged as names,
   but long or uncapitalized phrases will not.

Read the (heavily commented) code here:

 * [App code](lwp-example-complex.litcoffee) for this specific example
 * [HTML code](index.html) that loads the platform and application

There is also a very simple [build process](gulpfile.litcoffee).
