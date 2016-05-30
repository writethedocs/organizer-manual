.. _conf-communications:

Communications
==============

It's important to send emails to folks about various events.
You can combine some of these emails,
but it's often best to send around 7-10 total emails for the conference.

This section will cover emails sent to attendees. Communications with speakers and sponsors are covered in :doc:`conf-cfp` and :doc:`conf-sponsorship` sections.

Emails to send
---------------

* Date Announcement
* Call for Proposals
* Ticket Prices
* Keynotes (if applicable)
* CFP reminder (1 week out)
* Proposals
* Auxilary events (Hike, Writing Day, Reception, Party)

Each email will continue to list additional sponsors added to the conference.

Email content
-------------

It's easy to forget a key element while writing an email. Here's a description of what every type of email shoudl content.

Date Announcement
~~~~~~~~~~~~~~~~~

**Introduction:**

Write a small welcoming message with the date and place of the conference and just enough details to get people excited

**The Conference:**

Write a short description of the conference: describe the spirit of the event and mention topics from previous WTD conferences.

Use the end of this section to give more details about your venue (link to website and location on a map) and schedule.

**Auxillary events:**

List auxillary activities (hike, city tours, social events, etc) that will be held during the conference. Give a short description for each entry.

**While you're waiting:**

People should now be excited and will want to know more info that what you've provided.
Give info on how to reach you and how to get future news (mailing list, Twitter, etc).

Don't forget to ask for sponsors!

**Get excited!**

Write a small conclusion: make everyone (programmers, writers, designers, etc) feel welcomed.
Don't forget to mention the CFP: if you have a date already, perfect, if not "soon" and an invitation to start gathering ideas will do.

Date announcement emails from previous WTD conferences:

* `WTD NA 2016 <https://github.com/writethedocs/www/blob/master/docs/conf/na/2016/news/announcing-2016.md>`_
* `WTD NA 2015 <https://github.com/writethedocs/www/blob/master/docs/conf/eu/2015/news/announcing-eu-2015.md>`_

Call for Proposals
~~~~~~~~~~~~~~~~~~

Ticket Prices
~~~~~~~~~~~~~

Keynotes (if applicable)
~~~~~~~~~~~~~~~~~~~~~~~~

* CFP reminder (1 week out)
* Proposals
* Auxilary events (Hike, Writing Day, Reception, Party)

How to send email
-----------------

We write up the emails to send and post them on out blog.
Generally it's best to send a tweet with the blog post,
and then wait an hour or two to send the email.
This gives folks time to spot errors so we can fix them before sending the email :)

Process
~~~~~~~

The process is:

* Create a new MailChimp campaign with the email title being the blog post title
* Copy HTML from the blog post
* Remove Post title & Header links from the blog post (Regex is ``<a class="headerlink" .+</a>`` for search & replace)
* Paste HTML into MailChimp "Code" editor
* Remember to edit the Preview text in the Design tab
* Send a test email to yourself from MailChimp
* Once everything looks good, hit the **big button**
