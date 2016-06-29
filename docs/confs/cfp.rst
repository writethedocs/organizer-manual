.. _conf-cfp:

Speakers and Call for Proposals
===============================

This section describes how to:

* Manage the CFP
* Select talks
* Wrangle speakers before/during/after the conference

CFP Schedule
------------

The CFP should be scheduled to end around **3 months** prior to the conference.
This allows for time to book travel for speakers,
but also keeps the topics fresh and ensures the speakers are still passionate about them.

After the CFP ends,
reviews should be given 1 week to review all the talk proposals.
After this, we will have rate them following the below process,
and have the final group meeting where we talk through the final schedule

How to write a CFP?
-------------------

* **"Announcing [conf name] Call for Proposals":** Say hi and don't forget to mention when is the conference and when will close the CFP.
* **"Conference Goals":** Invite everyone who care about docs to contribute!
* **"Topic ideas":** To help potential speakers find a topic, list different subjects that make good talks. Add a few links to previous talks: it will help people get a better idea of what you want.
* **"Presentation format":** Format is 30 minutes but invite people to contact you if they want to do something longer/shorter.
* **"Speaker Benefits and Logistics":** Say if you cover ticket, travel cost and lodging for speakers.
* **"Question?":** How people should contact you.
* **"Submit a Proposal":** Link or form where people can send their proposal.

`Call for Proposals` examples from previous WTD conferences:

* `WTD NA 2016 CFP <https://github.com/writethedocs/www/blob/master/docs/conf/na/2016/cfp.rst>`_
* `WTD NA 2015 CFP <https://github.com/writethedocs/www/blob/master/docs/conf/na/2015/cfp.md>`_
* `WTD EU 2016 CFP <https://github.com/writethedocs/www/blob/master/docs/conf/eu/2016/cfp.rst>`_
* `WTD EU 2015 CFP <https://github.com/writethedocs/www/blob/master/docs/conf/eu/2015/cfp.md>`_

Selecting Talks
---------------

You should have:

* Access to the `cfp` Slack channel.
* Access to the CFP Google Doc

How it works:

* We allocate 2 points for every talk at the conference (eg. 30 points for 15 talks).
* You use those points to vote for which talks you want to see.
* We add up all the points and sort them by highest. This is the initial talk selection.
* We then argue for & against talks that we *really* want to change positions. This can either be because you know the speaker/topic will be good, two talks cover similar topics and we can only have one, or other reasons.
* We agree on a final set of 15 talks, along with 1 or 2 alternates.
  * If there are a ton of great talks that we want to see, we can reduce some to 15 minutes and fit 2 in a 30 minute slot.

Speaker Communication
---------------------

Like everyone,
most speakers don't really read their email.
This means you need to tell them everything important at least twice,
and probably again in person.

Speaker Acceptance Template
~~~~~~~~~~~~~~~~~~~~~~~~~~~

.. code-block:: jinja

	{{ name }},

	Our talk selection committee has just wrapped up proposal review and we would
	like to invite you speak at Write the Docs! The conference this year will be
	held on {{ date }}.

	Title: {{ title }}

	{{ Personalized bit about topic }}

	I've included your original proposal at the bottom of this email, for your reference.

	With that said, here's what you should do next:

	 * Reply to this email to confirm that you're in! Let us know that you're
	   planning to attend and speak, and that you agree to the guidelines below.
	 * Include a 300 x 300px color photo of your face. We will use this headshot
	   alongside your presentation description.
	 * If you want your Twitter handle published with your other details, include
	   that as well.
	 * Get your free speaker ticket! If you already purchased a ticket, we will be
	   refunding your ticket. Otherwise, pick up your free ticket here:

	     {{ ticket_url }}

	 * Send us any changes to your abstract. If you have any updates you would like
	   to make, or any of our feedback you want to incorporate, feel free to send us
	   an edited talk abstract.
	 * If you want to share this news, be sure to tag your posts with #writethedocs

	So you're all ready to speak? Good. Let's get down to brass tacks:

	 * Plan on attending both days of the event. We encourage your participation in
	   the entire event and will not be publishing the full presentation schedule
	   until shortly before the event.
	 * Your talk should be 30 minutes. *We will not be pausing for questions* after
	   your presentation. Attendees will be encouraged to approach the stage with
	   any feedback or questions during the break after each talk.
	 * Please review our Code of Conduct (http://writethedocs.org/code-of-conduct/).
	   Your talk is subject to these guidelines and should not have any sexual or
	   offensive content. If you have any questions about this feel free to email
	   myself or one of the other conference organizers. Generally, if you think any
	   content in your presentation might be an issue, leave it out.
	 * If you're concerned by travel details or expenses, contact us and we can
	   discuss options.

	We encourage you to confirm your details as soon as you can. As we confirm your
	details, we'll publish your abstract, headshot, and information on the
	conference site.  We'll also be emailing attendees to drum up anticipation for
	the talks we'll be presenting this year.

	Thanks again for submitting your talk, we look forward to having you join us!
	Feel free to email us with any questions, concerns, or ideas.

	Look forward to seeing you at Write the Docs!


Mail Merge Templates
~~~~~~~~~~~~~~~~~~~~

.. code-block:: jinja

	Hi {{First Name}},

	Thanks so much for submitting a proposal to speak at this year's Write the Docs North America. Our talk selection committee has just wrapped up our review and we'd love it if you could join us as a speaker! We think your '{{Talk Title}}' talk would be a great fit for the conference. We'd love to have you prepare it for a 30-minute time slot. 

	So, from here, your first step is to reply to this here email and as soon as possible, to confirm that a) you're still interested in presenting and b) you'll be available to attend *the whole conference* in Portland, from May 22-24, 2016. So much of the value of Write the Docs comes from the community interactions, so it's really important to us that our speakers are around to participate for the whole event. 

	Next, there's a few housekeeping things: 

	* Get your free speaker ticket! If you already purchased a ticket, let us know, and we will issue you a refund. Otherwise, pick up your free ticket here: https://ti.to/writethedocs/write-the-docs-na-2016/with/joeuvutda7s
	* Send us a 300 x 300px headshot (in color please!) to accompany your talk abstract on the website. 
	* Speaking of your abstract, if you have any changes you would like to make to your abstract before we publish it, please send us an updated copy as soon as possible. 
	* If you'd like us to include your Twitter handle or other contact info, send it on and we can include it with your bio.  
	* Finally, when you're sharing the good news, make sure to tag your posts with #writethedocs! 

	Okay, now that's all out of the way, it's time for the fun part--preparing your talk! To make sure everybody's on the same page, here are a few important things to keep in mind: 

	* Remember that one of the biggest strengths of the Write the Docs community is that we come from a huge variety of professional and personal backgrounds. When you're writing your talk (just like you're when writing documentation), think about the diverse needs and interests of your audience, avoid (or define) any jargony language, and make sure you clearly express what people are going to learn from your talk.  
	* If you would be interested in having another member of the Write the Docs community mentor you through the talk preparation process, please tell us! We'll do our best to connect you with someone to bounce ideas off of, to review drafts, and to general help you refine your talk before the conference. 
	* Make sure you plan your to talk to fit in the allotted time. Also, note that we will not be pausing for questions after your presentation. Instead, we encourage attendees to chat with our speakers during the breaks, or down in our unconference space.  
	* Please review our Code of Conduct (http://writethedocs.org/code-of-conduct/) and make sure your talk content adheres to it. As a rule of thumb, if you're on the fence about whether something in your talk could be considered inappropriate or offensive, leave it out. If you have a question about the code, feel free to email us and ask!

	Before you get too absorbed in talk prep, though, please send us an email confirming that you'll be joining us! :) If you're concerned about travel details or expenses, let us know and we can discuss options. As we confirm your details, we'll publish your abstract, headshot, and information on the conference site. We'll also be emailing attendees so they can share in our excitement about the talks we'll be presenting this year!

	Thanks again for submitting your talk, we look forward to seeing you up on the Write the Docs stage! Feel free to email us with any questions, concerns, or ideas.

	Thanks for helping make this year's conference another great one! 

	The Write the Docs Team

Thunderstorm Template
~~~~~~~~~~~~~~~~~~~~~

.. code-block:: jinja

	Hi {{First Name}},

	Thanks so much for submitting a proposal to speak at this year's Write the Docs North America. Our talk selection committee has just wrapped up our review and we'd love it if you could join us as a speaker! We think your {{Talk Title}}  talk would be a great fit for the conference. 

	We're hoping, though, that we might ask you to participate in something new we're trying this year -- Write the Docs thunderstorm sessions! To mix up the cadence of the conference a little, we're going to be interspersing several pairs of back-to-back 15-minute talks. We're thinking of them like a the big brother of a lightning talk (thunderstorms! get it?). So if you're game, we'd love to have you prepare the talk you proposed, just distilled down into the tightest, punchiest version of itself. 

	So, from here, your first step is to reply to this here email and as soon as possible, to confirm that a) you're still interested in presenting and b) you'll be available to attend **the whole conference** in Portland, from May 22-24, 2016. So much of the value of Write the Docs comes from the community interactions, so it's really important to us that our speakers are around to participate for the whole event. 

	Next, there's a few housekeeping things: 

	* Get your free speaker ticket! If you already purchased a ticket, let us know, and we will issue you a refund. Otherwise, pick up your free ticket here: https://ti.to/writethedocs/write-the-docs-na-2016/with/joeuvutda7s
	* Send us a 300 x 300px headshot (in color please!) to accompany your talk abstract on the website. 
	* Speaking of your abstract, if you have any changes you would like to make to your abstract before we publish it, please send us an updated copy as soon as possible. 
	* If you'd like us to include your Twitter handle or other contact info, send it on and we can include it with your bio.  
	* Finally, when you're sharing the good news, make sure to tag your posts with #writethedocs! 

	Okay, now that's all out of the way, it's time for the fun part--preparing your talk! To make sure everybody's on the same page, here are a few important things to keep in mind: 

	* Remember that one of the biggest strengths of the Write the Docs community is that we come from a huge variety of professional and personal backgrounds. When you're writing your talk (just like you're when writing documentation), think about the diverse needs and interests of your audience, avoid (or define) any jargony language, and make sure you clearly express what people are going to learn from your talk.  
	* If you would be interested in having another member of the Write the Docs community mentor you through the talk preparation process, please tell us! We'll do our best to connect you with someone to bounce ideas off of, to review drafts, and to general help you refine your talk before the conference. 
	* Make sure you plan your to talk to fit in the allotted time. Also, note that we will not be pausing for questions after your presentation. Instead, we encourage attendees to chat with our speakers during the breaks, or down in our unconference space.  
	* Please review our Code of Conduct (http://writethedocs.org/code-of-conduct/) and make sure your talk content adheres to it. As a rule of thumb, if you're on the fence about whether something in your talk could be considered inappropriate or offensive, leave it out. If you have a question about the code, feel free to email us and ask!

	Before you get too absorbed in talk prep, though, please send us an email confirming that you'll be joining us! :) If you're concerned about travel details or expenses, let us know and we can discuss options. As we confirm your details, we'll publish your abstract, headshot, and information on the conference site. We'll also be emailing attendees so they can share in our excitement about the talks we'll be presenting this year!

	Thanks again for submitting your talk, we look forward to seeing you up on the Write the Docs stage! Feel free to email us with any questions, concerns, or ideas.

	Thanks for helping make this year's conference another great one! 

	The Write the Docs Team

Speaker Rejection Template
~~~~~~~~~~~~~~~~~~~~~~~~~~

This template varies by the rejection.
We reject folks in a couple different rounds,
which I'll document here. 


.. code-block:: jinja
	
	TODO

Mail Merge Template
~~~~~~~~~~~~~~~~~~~

.. code-block:: jinja

	Hi {{First Name}},

	Thanks so much for submitting a proposal to speak at this year's Write the Docs North America. Every year we receive a growing number of proposals, and we're always blown away by the amazing breadth of knowledge that our community brings to the table. Unfortunately, presentation spots are limited and the talk selection committee wasn't able to include your talk in our program this year.

	We would still love if you could join us though! We set aside a block of early bird tickets for anyone who took the time to submit a talk proposal. You can pick up your ticket with the following link: https://ti.to/writethedocs/write-the-docs-na-2016/discount/TALKPROPOSAL

	During the review process, each member of the review committee considered each proposal carefully and then compared notes to make their final selections. We thought it might be useful to share a couple of the common themes for why talks may not have been included:

	* The subject of the talk was too specific for a larger audience. One of the biggest strengths of the Write the Docs community is that we come from a huge variety of professional and personal backgrounds. The committee looks specifically for talks that appeal to a good mix of our attendees.
	* The talk focused heavily on documentation tooling. We think these talks are important, but we tend to showcase higher-level concepts that progress the way we think in the documentation world. 
	* There were multiple talks on the same topic. We try to choose talks that cover a wide range of topics, which means making some hard choices between multiple great talks on similar topics. 
	* We just didn't have room. We receive many fantastic talks each year and have to pass up on some talks that we were really excited by.

	Keep in mind that we do run several batches of lightning talks that you can sign up for at the event. Plus, we have an unconference space downstairs from the main stage, in Lola's room, which is a great chance for more informal discussions. We'd love to have you, your ideas, and your passion at the conference--on stage or not, they're what make this event great!

	Thanks again for your proposal, and we hope to see you at the conference!

	The Write the Docs Team


Building a Schedule
-------------------

There are an infinite number of ways to arrange a schedule.
We've found it best to just randomly assign speakers to the schedule,
taking into account their availability (some folks can only speak on certain days).
After that,
you can shuffle speakers who you know are good to the following slots:

* Talk after lunch (should be high energy)
* Last talk of the day (should be memorable)

After this,
you send each speaker their time slot,
and confirm it works for them.
Give them a couple days to make changes,
then we can publish the schedule.

Biases
------

* New people
* Community members
* Previous lighting talk speakers
* 
