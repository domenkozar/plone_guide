What is Plone?
==============

.. image:: https://raw.github.com/aclark4life/plone_guide/master/plone-logo-128-white-bg.png
    :align: center

Plone is many things to many people. Here is what I think it is, followed by what other people think it is [1]_, followed by comments from the public (where you may add what you think it is [2]_). TL;DR:

.. Note::

    Plone is an open source web content management system written in Python. It is developed and supported by a worldwide community of hundreds of "Plone companies" as well as individual volunteers. It is used by thousands of organizations and individuals all over the world, in every professional sector imaginable (e.g. business, government, non-profit, etc.)

A Python CMS
------------

As I said above, Plone is many things to many people. So what is it to me? Here are a few definitions I like:

- **Plone is a CMS web application written in Python.**

But then you have to explain "CMS". So how about:

- **Plone is a web content management system written in Python.**

I like this one, except the concept of "CMS" (content management system) is dated. So how about:

- **Plone is a web application that makes it easy to build a public-facing or private-intranet website.**

The above is nice, but not altogether true. If Plone were entirely a hosted application with one click installable themes (e.g. http://ploud.com) then it would be closer to true. The reason the above statement is not entirely true (as we'd like it to be marketing-wise) is complicated and will not be addressed here [3]_.

Spin
~~~~

.. image:: https://raw.github.com/aclark4life/plone_guide/master/python-logo-master-v3-TM.png
    :align: center

Of course, I like to spin: [4]_

- **Plone is the best Python-based web content management system available, hands down.**

While I firmly believe the above to be true, I don't always lead with that definition, because I'm sure there are others that believe the same about their Python-based CMS of choice (e.g. Django CMS).

Community
~~~~~~~~~

One statement I don't mind leading with, and supporting amidst all the competition:

- **Plone has the best community of any open source community you will ever find, anywhere, ever.**

I'm not entirely sure how this came to be, and it could just be my bias, but: I'm loosely a member of at least a half dozen such communities and am always blown away by how this particular community conducts itself. The reason the above statement is true is complicated and will not be addressed here [3].

Other Definitions
-----------------

- From plone.org, a "state-of-the-art open source CMS."

The Stack
---------

Hardware
~~~~~~~~

I won't cover the hardware stack here, but suffice it to say that Plone runs on all modern desktop and server operating systems.

Human 
~~~~~

I won't cover the human stack here, but if you are interested please see:

- http://blog.aclark.net/2012/10/23/plone-secrets-5-the-community/

Software
~~~~~~~~

.. image:: https://raw.github.com/aclark4life/plone_guide/master/zope_less_hi_res.jpg
    :align: center

As is common in open source, Plone is built on top of many other open source components. Primarily:

- **Python (The Python Programming Language)**
- **Zope (The Z Object Publishing Environment)** [5]_

But also technologies that are a subset of the above two technologies:

- **PIL (Python Imaging Library)**
- **CMF (Zope Content Management Framework)**

Lastly it is built with many popular web-specific open source technologies:

- **JQuery (JavaScript Framework)**
- **TinyMCE (WYSIWYG editor)**

This list is not all-inclusive, but it should give you an idea of how much technology is bundled with an application like Plone.

.. [1] More accurately, what I think other people think it is.

.. [2] Good or bad, your comments are welcome as long as they are courteous.

.. [3] Yet, but maybe at some point in the future.

.. [4] Marketing or public relations-speak, http://en.wikipedia.org/wiki/Spin_%28public_relations%29

.. [5] Zope provides many popular and widely used open source technologies e.g. Zope2, ZODB, Zope Toolkit, etc. Also, while Zope is technically an acronym you will frequently see it spelled with normal case.

.. include:: comments.rst
