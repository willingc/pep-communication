PEP: 9999
Title: Survey of Communication Modes in the Development Community
Author: Carol Willing <willingc@python.org>, Pablo Salgado <>
Status: Draft
Type: Informational
Content-Type: text/x-rst
Created: 27-Feb-2019
Post-History:


Abstract
========

What this PEP Does Not Cover
============================

- Communications resources outside of the scope of CPython core development
- Third-party communication mediums not maintained by CPython core devs or
  the PSF

What the PEP Does Cover
=======================

- Guiding principles about `change`_
- User `personas`_
- `History`_
- `Current communication channels (formally adopted and trials) <current>`_
- `Information Types (Text, Visual, Audio / Video) <infotypes>`_
- Communication purposes
- Summary

- Resources
- `Appendix 1: List of Communication Channels <app1>`_
- `Appendix 2: Benefits and limitations <app2>`_
- Acknowledgements
- References

.. _change:

Guiding Principles about Change
===============================

- Change is a **reality**.
- Change is neither completely good or bad.
- Change is driven by the current practices in software development and the
  community of CPython developers.
- Each person should expect some change to their existing workflow.
- While changes may require some learning of new tools or methods,
  time needed to do so should be respected and not be overly
  burdensome as we are volunteers.
- Changes should clarify existing processes or practices.

.. personas:

User Personas
=============

The following user personas identify the typical uses of communication
tool:

- **Python users**: news about the project and reference information
- **Third party library or package maintainer**: core maintainer on another
  busy project, only wishes to have information on a particular topic instead
  of a firehose of information
- **CPython contributor**: someone completely new to the project, how do they
  become invested over time
- **CPython core developer**: time efficiency, keep up to date on changes,
  invested in personalized workflows for managing mail and communications

This PEP aims to take into account all of these personas.

History
=======

This list summarizes the history of Python core development
communication mediums (ordered from oldest to most recent usage):

- Mailing Lists / Usenet(?)
- IRC
- Documentation / wiki
- Issue trackers
- python.org website
- Dev Guide
- GitHub PR Discussion
- Zulip
- Discourse (discuss.python.org)
- Steering Council repository

.. _current:

Current Communication Channels
==============================

The following channels are currently used:

- Mailing List History
- IRC History
- Zulip History
- Discourse History
- bugs.python.org
- python.org
- DevGuide
- Documentation
- PEPs
- Steering Council repository

Information flow may be one-way (informative) or two-way (collaborative).

- Information flow diagram: `info-flow.pdf <info-flow.pdf>`_
- Two-way collaborative communication diagram: `two-way-communication.pdf <two-way-communication.pdf>`_

These visualization and mappings should identify what is currently in use and
potential suggestions for the future.

.. _infotypes:

Information Types
=================

Communication mediums used for Python development should support
both **textual** information and **visual** information. Audio and video
information is also usseful but is outside the scope of this PEP.

The following sections will point out some of the benefits and
limitations of sharing each type of information.

Text
----

Text based communication, such as mailing lists, has been the bulk of
information shared in the past as well as currently.

Visual
------

The importance of communicating visual information has increased markedly
due to the modern editors, JavaScript, and tools such as Jupyter notebooks.
Communication mediums should have the ability to archive, link out to
persistant storage, or inline visual information.

Audio and Video
---------------

While audio and video are not typically used to communicate information about
Python core development, it's a possibility that workgroups or affinity groups
may choose to use webinars or group chats. This PEP flags the potential future
use but defers any recommendations and workflows related to audio and video
to future PEPs.

Communication Purposes
======================

The purposes of communication fall in two broad categories: announcements and
discussion.

Announcements
-------------

Where should announcements be made?

Decisions
~~~~~~~~~

Where should decisions be communicated? PEPs

Informational
~~~~~~~~~~~~~

Where should event, meeting, and requests for comments be communicated?

Discussion
----------

- Where should discussions take place?
- Should different communication mediums be used for different types of
  discussion?
- Brief q and a; working collaboration on a specific task or project;
  brainstorming ideas

Recommendations
===============

The following channels are the expected places for various types of
communications:

- Announcements
    - Steering Council: Steering Council GitHub Repo and periodically posted
      community updates (python-dev, Discourse, Zulip?, PSF Board)
    - PEP pronouncements: PEP GitHub Repo, python-announcements
    - New core developers: python-committers

- Discussions
    - Issue specific: bugs.python.org / GitHub issues
    - Core developer (committers): Recommendations for commit rights and
      discussions where only committers are impacted
    - General: python-dev (current development), python-ideas (future ideas),
      Discourse (current development especially if visual information sharing
      is helpful), and Zulip
    - PEP discussions: python-dev, Discourse, and Zulip
    - Workgroups: Identify preferred channel and document in devguide

- Future
    - A communications workgroup may be helpful to support workflows and
      project goals and vision.

Summary
=======

As we move toward Python 2 retirement and issue tracking workflow upgrades,
it makes sense to prefer mailing lists in many cases. We also recognize the
benefits of more collaborative tools such as Discourse and Zulip which may be
used for discussions. Announcements must be made in mailing lists or GitHub
repos; though, announcments can be mirrored in Discourse and Zulip if desired.

Resources
=========

Acknowledgements
================

References
==========

.. _app1:

Appendix 1: List of Communication Channels
==========================================

Many of these channels are discussed in the Python devguide.

GitHub Repos
------------

- CPython
- PEPs
- Steering Council

Mailing Lists
-------------

- https://mail.python.org and https://mail.python.org/mailman3/lists/: complete list of Python mailing lists
- python-committers_: core developers
- python-dev_: discussions about Python's development | `Search <https://www.mail-archive.com/python-dev@python.org/>`_
- python-ideas_: ideas about new functionality.
- python-list_ or python-help_ or `tutor`_: technical support questions
- Python-checkins_: email for every commit to Python
- new-bugs-announce_.
- python-bugs-list_.
- `Core-Workflow <https://mail.python.org/mm3/mailman3/lists/core-workflow.python.org/>`_
- `Mail Archive <https://www.mail-archive.com/python-dev@python.org/>`_: another source to find mail archives
- Search via Google `site:mail.python.org the_search_term`

.. _new-bugs-announce: https://mail.python.org/mailman/listinfo/new-bugs-announce
.. _python-bugs-list: https://mail.python.org/mailman/listinfo/python-bugs-list
.. _python-checkins: https://mail.python.org/mailman/listinfo/python-checkins
.. _python-committers: https://mail.python.org/mailman/listinfo/python-committers
.. _python-dev: https://mail.python.org/mailman/listinfo/python-dev
.. _python-help: https://mail.python.org/mailman/listinfo/python-help
.. _python-ideas: https://mail.python.org/mailman/listinfo/python-ideas
.. _python-list: https://mail.python.org/mailman/listinfo/python-list
.. _tutor: https://mail.python.org/mailman/listinfo/tutor
.. _StackOverflow: https://stackoverflow.com/
.. _Freenode: http://freenode.net/

Additional Discussion Channels
------------------------------

- https://bugs.python.org: issue tracker
- `Discourse <https://discuss.python.org>`_: discuss development and dev community
- `zulipchat <https://python.zulipchat.com>`_: discuss the development of Python only.
- IRC: ``#python-dev`` channel on ``irc.freenode.net``
- Blogs: http://planetpython.org/

.. _app2:

Appendix 2: Benefits and Limitations
====================================

Mailing Lists
-------------

Limitations
^^^^^^^^^^^
- subtle bias towards a "long-term investment" persona: when joining a mailing
  list, it's very difficult to join a discussion already-in-progress. The only
  people who get the privilege of replying to a post are the people who
  subscribed before the post was made.
- firehose of information can overwhelm new contributors and potentially
  discourage them away from the project

IRC
---

bugs.python.org
---------------


Discourse
---------

Usage statistics: Discourse (discuss.python.org)
`Site statistics <https://discuss.python.org/about>`_


Zulip
-----


GitHub
------
PRs and issues (future-TBD)

python.org
----------

devguide
--------

documentation
-------------

PEPs
----

Copyright
=========

This document has been placed in the public domain.


..
   Local Variables:
   mode: indented-text
   indent-tabs-mode: nil
   sentence-end-double-space: t
   fill-column: 70
   coding: utf-8
   End:
