============
Main Heading
============
This is plain text. Markdown is accepted.

This is a horizontal rule (four or more dashes or asterisks or underscores:

_____________________________

This is a test Table of Contents that uses ```backlinks: none``` to prevent the sub-headings from being turned blue:

.. contents:: **Table of Contents**
   :depth: 1
   :local:
   :backlinks: none

Here are some other Table of Contents varieties you could use:

.. code:: markdown

 This is a Table of Contents with no heading:

 .. contents:: :local:

 This is a Table of Contents with a default heading:

 .. contents::

 This is a Table of Contents with a custom heading:

 .. contents:: Table of Contents

 This is a Table of Contents with a custom heading and with its depth specified:

 .. contents:: Table of Contents
     :depth: 3

 This is a Table of Contents with a custom heading, with its depth specified, and that doesn't turn the sub-headings blue:

 .. contents:: **Table of Contents**
    :depth: 1
    :local:
    :backlinks: none

This is level 1 sub-heading 1
=============================

This is plain text. This is **bold text** and this is *italic text*.

* This
* is
* a
* bulleted
* list


This is a code block:

.. code:: python

   print("foo")
   print("bar")


This is level 1 sub-heading 2
=============================

This is level 2 sub-heading 1
-----------------------------

This is a plain link and you want to go there to see what all you can do with one of these **.rst** files: https://gist.github.com/1855764

These are some link-placeholders followed by the code that provides the links for each one:

Requires `xautomation`_ and `ImageMagick®`_ to be installed.

.. _xautomation: http://hoopajoo.net/projects/xautomation.html
.. _ImageMagick®: http://www.imagemagick.org/

This is another link-placeholder followed by the code that provides the link for it:

`Source code`_.

.. _Source code: https://github.com/autokey/autokey/blob/master/src/lib/scripting_highlevel.py


This is level 1 sub-heading 3
=============================

This is plain text.

And here's one more code block:

.. code:: python

   print("hello world")
   print("goodbye world")

This is level 2 sub-heading 2
-----------------------------

This is plain text.

1. This
2. is
3. a
4. numbered
5. list


Below this is a hidden comment:

.. ..

 <!--- Comment blocks are created by inserting a blank line
 followed by a .. .. line followed by a blank line followed
 by an HTML comment block done with THREE dashes and
 indented by at least one space. The comment block can
 contain blank lines and is closed the same way as an HTML
 block, but with THREE dashes and must be followed by a
 blank line and an unindented line.
 --->

this
  : is a definition list

Unnecessary line of text 1.

