.. include:: /Includes.txt
.. _start:

===============================
Tell Me Something About Topic X
===============================

Rendered: |today|

:Title:         Tell Me Something About Topic X
:Authors:       TYPO3 Documentation Team
:Maintainer:    Martin Bless <martin.bless@typo3.org>
:Description:   Frequently searched topics with explanations and links
:Published at:  https://docs.typo3.org/m/typo3/guide-tell-me-something-about/master/en-us/
:Repository:    https://github.com/TYPO3-Documentation/TYPO3CMS-TellMeSomethingAbout/
:License:       `CC BY-NC-SA 4.0 <https://creativecommons.org/licenses/by-nc-sa/4.0/>`__

This manual is part of official TYPO3 documentation.

.. Do not use headlines on this page as we have a .. toctree::
   at the end of this page.

--------------------------------------------------

**What is this?**

•  intended to be a help for developers to quickly find some interesting
   starting points when diving into a topic you are not familiar with
•  a collection of short information pointers, structured by topics
•  a collection of short information pointers, structured by topics
•  a collection of topics that are important in TYPO3 context
•  a place to keep search results when doing internet research
•  a collection of links to content that somehow sticks out
•  a time saver for you - hopefully


.. // http://www.graphviz.org/doc/info/attrs.html
   // http://www.graphviz.org/doc/info/attrs.html#k:escString
   // http://www.graphviz.org/doc/info/attrs.html#k:shape
   // https://en.wikipedia.org/wiki/DOT_(graph_description_language)#General
   // https://graphs.grevian.org/example
   // https://graphviz.org/doc/info/lang.html
   // https://graphviz.org/pdf/dotguide.pdf
   // https://manpages.debian.org/testing/graphviz/dot.1.en.html
   // https://renenyffenegger.ch/notes/tools/Graphviz/examples/index


.. graphviz::

   digraph G  {
      layout=neato;
      node[fontsize=14,style=solid];
      SEARCHING [label="Looking for",style=dashed,shape=rectangle];

      node[fontsize=12,style=filled];
      SEARCHING -> Caching;
      SEARCHING -> Fluid;
      SEARCHING -> Performance;
      SEARCHING -> more_1;
      SEARCHING -> more_2;
      SEARCHING -> CKEditor;
      SEARCHING -> Deployment;


      node[fontsize=8,width=.1,height=.1,shape=ellipse,style=filled,fillcolor=white]
      Caching -> offdocs_1;
      Caching -> blogpostings_1;
      Caching -> videos_1;
      CKEditor -> CKEditor_whatisit;
      CKEditor -> CKEditor_resources;
      CKEditor -> CKEditor_blogpostings;
      CKEditor -> CKEditor_onlinetryouts;
      Deployment -> Deployment_blog_postings;
      Deployment -> Deployment_clever_solution;
      Deployment -> Deployment_tools;
      Fluid -> offdocs_2;
      Fluid -> blogpostings_2;
      Fluid -> Tools;
      Fluid -> Viewhelpers;
      Performance -> offdocs_3;
      Performance -> blogpostings_3;
      Performance -> tutorials_4;
      Performance -> Links;

      node[label="",shape=circle,width=.1,height=0.1]
      Performance -> performance_1;
      Caching -> caching_1;
      Fluid -> fluid_1;
      more_1 -> more_1_1;
      more_1 -> more_1_2;
      more_1 -> more_1_3;
      more_1 -> more_1_4;
      more_1 -> more_1_5;
      more_1 -> more_1_6;
      more_2 -> more_2_1;
      more_2 -> more_2_2;
      more_2 -> more_2_3;

      blogpostings_1 [label="Blog postings"];
      blogpostings_2 [label="Blog postings"];
      blogpostings_3 [label="Blog postings"];
      more_1 [label="Your idea"];
      more_2 [label="More..."];
      offdocs_1 [label="Official docs",tooltip="Official docs"];
      offdocs_2 [label="Official docs",tooltip="Official docs"];
      offdocs_3 [label="Official docs",tooltip="Official docs"];
      tutorials_4 [label="Tutorials"];
      videos_1 [label="Videos"];

      CKEditor [href="../Topics/Ckeditor.html",target=_top];
      CKEditor_blogpostings  [label="Blog postings" ,href="../Topics/Ckeditor.html#blog-postings" ,target=_top,tooltip="Blog postings"];
      CKEditor_onlinetryouts [label="Online tryouts",href="../Topics/Ckeditor.html#online-tryouts",target=_top];
      CKEditor_whatisit      [label="What is it?"   ,href="../Topics/Ckeditor.html#description"   ,target=_top];
      CKEditor_resources     [label="Resources"     ,href="../Topics/Ckeditor.html#resources"     ,target=_top];
      Deployment [label="Blog postings",href="../Topics/Deployment.html#blog-postings" ,target=_top,tooltip="Blog postings"];
      Deployment [label="Tools",href="../Topics/Deployment.html#tools" ,target=_top,tooltip="Tools"];
      Deployment  [label="Clever solutions",href="../Topics/Deployment.html#clever-solutions" ,target=_top,tooltip="Clever solutions"];
   }


--------------------------------------------------

**What this is NOT**

•  there's no garantee that given links are still valid
•  there's no garantee that linked content is perfectly correct and up to date
•  there's no garantee that all important content is linked


--------------------------------------------------

**Doesn't seem very complete and up to date?**

Up to now only a few people have done a - very - little bit of contribution
here. Can you imagine how useful this could be if YOU would add your knowledge
and search results too? As a developer we often find ourselves with a special
topic in the foreground of our thinking. That's the moment when we start
internet search: Shop solutions, security, performance, caching for example.
Very useful information about those topics can be found in the internet in form
of slideshows, videos, tutorials or blog posts. While it would be very
desirable to make that information part of the official documentation in
practice this often is not feasable. This manual is an attempt to make such
external information accessible. It can be seen as an enhanced "curated list".

--------------------------------------------------

**How to get your stuff presented here as well**

Best way
   Use the "Edit" button at the top of the page and file a pull request.
   See also :ref:`How to contribute <h2document:docs-contribute>`. Pull
   requests have the highest chance of being treated soon.

Second best way
   Create a new `issue at Github
   <https://github.com/TYPO3-Documentation/TYPO3CMS-TellMeSomethingAbout/issues>`_.
   Expect issues to be dealt with somewhat soon.

Worst way
   Send an `email
   <documentation@typo3.org?subject=TellMeSomethingAboutTopicX>`__ with subject
   'TellMeSomethingAboutTopicX'. In the email make yourself understood. Don't
   expect an email reply. Your suggestion may or may not be integrated in the
   manual. If accepted, somebody will probably create an issue for you.

IF IN DOUBT
   It is better to take any of those actions and to do something than doing
   nothing. Your message doesn't have to be perfect.

--------------------------------------------------

**Contents:**

.. rst-class:: compact-list
.. toctree::
   :titlesonly:

   Topics/Index
   About/Index
   Sitemap/Index
   Linktargets/Index
   genindex
