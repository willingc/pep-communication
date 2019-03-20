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

- Communications beyond CPython core development (language and processes)
- Communication mediums not maintained by CPython core devs or the PSF

What the PEP Does Cover
=======================

- Principles about change
- User personas
- Historical evolution of Python Communications
- Current Communication Mediums (both formally adopted ones and trials)
- Modes of Communication - a detailed look including pros and limitations
- Information Types (Text, Visual, Audio / Video)
- Communication purposes
- Summary
- Recommended Next Steps
- Resources
- Acknowledgements
- References

Principles about Change
=======================

- Change is a reality. Change is neither completely good or bad. Change
  is driven by the current practices in software development and the
  community of CPython developers.
- Each person should expect some change to their existing workflow.
- While changes may require some learning of new tools or methods,
  time needed to do so should be respected and not be overly
  burdensome as we are volunteers.
- Changes should clarify existing processes or practices.

Personas for Communication
==========================

The following user personas identify the typical uses of communication
tool:

- Python users
- Third party library or package maintainer
    - example: core maintainer on another busy project, only wishes to have information on a particular topic instead of a firehose of information
- CPython contributor
    - example: someone completely new to the project, how do they become invested over time
- CPython core developer

Historical Evolution of Python Communication Mediums
====================================================

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

Currently Used Communication Mediums
====================================

- Mailing List History
- IRC History
- Zulip History
- Discourse History
- bugs.python.org
- python.org
- DevGuide
- Documentation
- PEPs

Modes of Communication - Pros and Limitations
=============================================

Mailing Lists
-------------

Limitations
^^^^^^^^^^^
- subtle bias towards a "long-term investment" persona: when joining a mailing list, it's very difficult to join a discussion already-in-progress. The only people who get the privilege of replying to a post are the people who subscribed before the post was made.
- firehose of information can overwhelm new contributors and potentially discourage them away from the project
- UI can be overwhelming to some. More alternative solutions available for displaying mail.

IRC
---

bugs.python.org
---------------


Discourse
---------

- Can mirror Mailing Lists as read-only `Example Ruby Talk mailing list on Discourse <https://rubytalk.org/>`_ 
  *This is a read-only mirror of the Ruby-Talk mailing list. You can participate in the discussions by subscribing and posting to the mailing list.*
- Very rich andgranular moderation capabilities. This includes the possibility for users to flag a post
  (violation of the CoC, off-topic, spam, inapropiate...) for a moderator to review, with the possibility
  for the moderator to act in many different ways. Multiple moderators are allowed with different levels
  of permissions.
- Low entry bar: multiple ways of logging in including social integrations (GitHub, Google, Facebook,...),
  single sign-on with custom provider, invitation links, discourse accounts...
- Editing: as any modern communication platform, allows editing of posts. Post eddits are clearly called out
  and readers can look at previous revisions to clear up possible confusions, while it allows the user to add
  some clarifications to the original message or to fix some typos.
- Granular tracking controls: users can select different ways to be notified of activity in each topic, as oposed
  to a subscribed/unsubscribed model.
- Similar topic suggestions when creating a new message, that allows to prevent repetition when users want to create
  new posts or messages.
- Syntax highlighting, markdown editing, code snippets, embedable images.
- Integrated search functionality across all messages and topics in the instance.
- Ability to quote multiple users and part of different messages in a simple and graphical way.
- Possibility to restructure topics, allowing to move messages across when they are off-topic.
- Active development to replace `common mailing list features <https://meta.discourse.org/t/moss-roadmap-mailing-lists/36432>`_.
  
Limitations
^^^^^^^^^^^
- UI can be overwhelming to some.

Zulip
-----
Zulip has been used as a substitute to IRC, providing users with a real-time communication channels that
complement the other communication mediums. Real time communication can be very important to solve some
concrete problems or to iterate together along with other users of the platform on the same problem.

- Multiple ways of using Zulip: Web interface, Android App, IPhone App...etc
- Stream/Thread model, suitable for many ongoing conversations. This eliminates the need of mentioning
  someone for every reply.
- Offers integrations that allows the usage of bots and automatic systems.
- Draft messages (save messages to be sent later).
- Markdown support: allows to format links, images and tables.
- Syntax highlighting with embedable code snippets.

Limitations
^^^^^^^^^^^
- There has been multiple reports of some bugs that impact user experience when using Zulio from the phone Apps.
- The UI can be a bit counterintuitive at first, specially on the phone apps.


GitHub
------
PRs and issues (possibly in future)

python.org
----------

devguide
--------

documentation
-------------

PEPs
----


Detailed Visualizations of Current Communications Options
---------------------------------------------------------

These visualization and mappings should identify what is currently in use and potential
suggestions for the future.

Usage Metrics for Current Communications Options
------------------------------------------------

Discourse (discuss.python.org) `Site statistics <https://discuss.python.org/about>`_

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

`Illustration of one way and two way communication mediums <https://github.com/willingc/pep-communication/blob/master/info-flow.pdf>`_

`Illustration of two way communication mediums <https://github.com/willingc/pep-communication/blob/master/two-way-communication.pdf>`_

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
- Should different communication mediums be used for different types of discussion?
- Brief q and a; working collaboration on a specific task or project; brainstorming ideas

Summary
=======

Recommended Next Steps
======================

Resources
=========

Acknowledgements
================

References
==========




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
