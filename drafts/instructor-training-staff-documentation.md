Note to Maneesha: There are a lot of embedded HTML links that didn't copy over from the Google doc. Here is the G-doc: https://docs.google.com/document/d/1DMMwuORgodN5MbBxM3yW3oJxLch5gIgJBvyF6AoS1qU/edit


Administering an Open Training Event
One Month before
Put a note on your Asana to check one month before each event.
One month out - check calendar to see whether any members have signed up for an event.
If no members have signed up, put “OPEN TRAINING” in the calendar.
Get names of applicants to invite from current spreadsheet (in this folder). Periodically update this with new applicants (see below).
Pull out Email and Personal (first name) of the people you want to invite and put in .txt file.
Use this script to send invites.
Update “invitees” (line 9) with a link to the correct tab-delimited file.
Change “from” (line 24) to your gmail address.
Change line 41 to your name (currently “Erin Becker”).
Change “register date” (line 56) to a date from the day you are sending.
Test script using test file on line 12. (Modify test file to use your email addresses so you can tell if the script is running and the text is formatted properly.)
Remove the “#” from line 59 (mail_invitees(invitees)). 
Run script.
Check your email outbox to see that they are sending.
Create an event in AMY. 
Event → New Event 
Host and Administrator are both Software Carpentry for open events.
Tags = TTT (train the trainer)
Leave URL blank
Language is English unless otherwise specified.
Eventbrite key, Admin fee, Attendance, and Contact are all blank to start.
Invoice status = invoice not requested
Country = Online (all other fields for location will self-populate).
Add Trainers as instructors (create a task for them).
Intermittent registration
After inviting participants, periodically check the registration sheet and transfer participant registration into AMY. 
Search each name in AMY. Most names will be easy to find. If you can’t pull up the record with both first and last name, try just last name (this is a glitch in AMY that needs fixing).
AMY has records for “Training Requests” and “Persons”. Most people will have both a Training Request record and a Person record. 
If their Training Request record shows as “Pending”, change it to “Accepted”.
Edit → State → Accepted → Update
Match Training Request to Person record.
If there is an existing Person Record (“Trainee Account”) it will auto-populate in the box. Click “Match to selected trainee account”. 
If there is no existing Person Record, the box will be blank. Click “Create new trainee account”.
Click person’s name under “Matched Person” to access their Person Record.
Add the training event as a “Task” for that Person.
Edit → Tasks (tab) → Event = event name (searchable) → Role = “Learner”
Leave title and URL blank.
If there are multiple Training Requests that match the person, mark one as Accepted and the others as Discarded.
On the registration sheet, next to the person’s email, put “Registered by [your name] on [date], so that they can see their registration has been processed.
If you get questions about registration by email, confirm that they’ve been registered and tell them you’ll send out more information about a week before the event.
Do not allow more people to register for the event than you designate seats for (usually 25). Once the event is full, add a note to that effect to the registration sheet (e.g. This event is now full. Please contact [your email] with any questions.)
Two Weeks before
Email Trainers to ask them to set up an event website and Etherpad (see template below). Also share Zoom connection information and login credentials with Trainers.
Add the event website URL to the AMY event. 
Edit → add URL → Submit
One Week before
Once registration is finalized, send email to participants (see template below). Approx. 1 week out.
Open Event in AMY and make sure all participants have an email address in their record. If not, update their record using the email listed on the registration page
click “Mail Everyone” above the participant list in AMY.
Move Trainers to cc.
Make sure to enter correct Trainer names, dates, website URL and Zoom connection info.
After event
After event, email Trainers to remind them to send attendance to checkout@carpentries.org and ask them how things went (see template below).

Updating Invitee List for Open Trainings
Every couple of months, recruit one or two Trainers to help score new applications (see template below). 
Download applications.
Requests → Training requests → Download all requests as CSV
Move application file to Open-Training folder in a new folder labelled “Applications_[MonthYear]”
Rename application file to “training_requests_all_MM_DD_YY.csv”
Sort applications to remove applicants who have already been invited and applicants to member-affiliated training events.
Open sort_applications.R located in the Open-Training folder.
Change line 4 to the path to Open-Training folder on your system.
Change line 7 to the location of the new applications file.
Change line 25 to desired output path and name of file.
This script will extract applications that are currently labelled as “Pending” and do not have a group name affiliated with them. We don’t yet have a system for creating a list of all un-trained applicants (i.e. merging new applicants with previously scored but untrained applicants). This is a process I hope you will develop.
Use our rubric to score applications. Average all involved Trainers’ scores. Use these scores to determine invitees for open training events.
Creating a New Trainer Cohort
Decide on goals for Trainer recruitment (in collaboration with Director of Instructor Training).
Recruit two-three Trainers to help rank applications. Strive for geographical representation (at least two outside of US).
Update Trainer application to reflect these goals. (This will involve changes to the last two questions.)
Announce application period on Twitter (DC and SWC accounts), Discuss, and Blogs. Language to borrow from in previous blog post. Maybe get some testimonials / quotes from recent Trainers to add to promotional materials.
Promote overall goals in communications. 
Email previously interested parties (listed here) to remind them to apply. 
Ask relevant community members to promote in their networks to help meet recruitment goals.
Ask Trainers who volunteered to rank applications according to priority (3 = high, 1 = low). We don’t have a rubric for this, but have been evaluating informally on various metrics that change depending on our goals for that recruitment. Ask Trainers to leave notes about their reasons for their rankings. Make sure Trainers know our recruitment goals.
Consolidate rankings. In the last round, we were able to accept everyone with unanimous support (ranked 3 by all 4 Trainers), everyone with 3 out of 4 support, and two applicants with 2 votes. Use your discretion to add applicants to the widely supported pool based on gaps in representation (e.g. geographical distribution, gender, pedagogical experience). Current Trainer representation is ~50% M/F, 50% US, and 15% not Caucasian non-Hispanics. 
Notify accepted applicants (see Template below) and ask to complete follow-up tasks.
Schedule Trainer Book Club meetings. Will need two time slots. 
Notify participants of time for book club meetings. 
Let Belinda know about new Trainers in Training so she can blog and Tweet.
Update Trainer-training Etherpad.
Update Reading Guides as needed based on curriculum updates (they reflect the previous edition of the curriculum).
Take attendance during book club meetings. Must attend all but one session to certify. 
Once new Trainers complete book club, remind them to complete follow-up tasks and notify you as they do them. Send out Trainer certificates (sendmail_trainer_certs.R in Training-Trainers folder).
Let Belinda know new Trainers have completed training so she can blog and Tweet.
Maintaining Instructor Training Repos





Instructor Training Event Administration Checklist 
Four weeks before the event: 
[ ] Send introductory email with reading assignments, videoconferencing link, etc, to trainees (bcc:ed) and instructors & hosts (cc:ed).  See template (below).
[ ] Offer partner sites the chance to test the videoconferencing set up (member events only).
One week before the event: 
[ ] Send trainers Zoom login information. Trainers should use these credentials and not their own Zoom logins. See Zoom manual below.
[ ] Set up surveys for the event and share links to view results with Trainers.

Two days before the event: 
[ ] Send a reminder email to trainees. See template (below).
[ ] Tell Trainers if any trainees have not completed their application (member events only).
Immediately after the event:
[ ] Ensure that attendance information has been entered into AMY by admin assistant.
Long-term after the event:
[ ] Email trainees two months after training to remind about deadline. See template (below).
[ ] Review lesson contributions sent to checkout@carpentries.org. Update trainee status in AMY.
[ ] Enter information about teaching demo completion into AMY.
[ ] Check AMY for unbadged instructors who are eligible and award badges.
More > Trainees > Is SWC/DC instructor? > No, but eligible to be certified. > Submit
[ ] Generate certificates and send out with this script. 
Template Emails
Email Trainers to ask them to set up an event website and Etherpad
Hi [ ---- names ---- ],

I'm excited to let you know that your instructor training [ ---- dates ---- ]  will be an open training event. 
This will be a completely distributed training and
will be held on Zoom. If you’re not familiar with Zoom, 
there are some usage tips in the instructor notes for instructor training. Please let me know if you have any questions about Zoom. I’m happy to do a walk-through with you before your event if you’d like. I can also advise as to when the room is available if you’d like to play around on your own. The room you will be using is https://carpentries.zoom.us/j/8243150376 and the host login is 
Username: room2@carpentries.org
Password: room2carpentries_

Please note that login privileges are for Trainers only, so this information should not be shared. 

The instructor notes also has links to templates for setting up a workshop website and an event Etherpad. When you get a chance, please set up your website and send me the URL so I can get it recorded in AMY.

I've got the participants loaded into AMY now and will be
sending them and you an email with connection logistics and
preparation instructions about a week before the event.

Please keep in mind that a new version of the instructor training materials was released recently, so please take a good
read through them if you haven't yet.

Please let me know if you have any questions before then.

Best,
[ ---- name ---- ] 
Email Participants before Instructor Training event

Hello everyone,

Thank you for joining our upcoming online instructor training session [ ---- dates ---- ] at [ --- link to time zone --- ].  As a reminder, this is a training for people who want to become instructors with Software Carpentry and Data Carpentry. The workshop is a mix of lectures and hands-on lessons where you practice giving a short lesson using approaches learned and implement some of the teaching techniques which we will discuss. This is training for teaching, not technical training; you do not need any particular technical background, and we will not be teaching that. This workshop is based on our constantly revised and updated curriculum (https://carpentries.github.io/instructor-training/). You can find more information about your workshop at the workshop website: [ ---- link ---- ].

This will be offered online via Zoom with our instructor trainers, [ ---- names ---- ]. You can connect to the event using this link: https://carpentries.zoom.us/j/8243150376. Additional information about the Zoom call can be found at the bottom of this email.

Please plan to be present for the entire session both days. Participants who miss more than 1 hour will not pass our training requirements.

Some other things in order to prepare:

1. Please read this short paper, which provides a brief overview of some key evidence-based results in teaching:

* "The Science of Learning" (https://carpentries.github.io/instructor-training/files/papers/science-of-learning-2015.pdf)

2. Please go to the Software Carpentry lessons page (http://software-carpentry.org/lessons/) and the Data Carpentry lessons page (http://www.datacarpentry.org/lessons/), have a look at what we currently teach, and then choose *one* episode from the list at the bottom of this message and read through it carefully. You will be using your selected episode for several in-class exercises, so be sure you are comfortable with the content.

3. Please make sure that you have a reliable internet connection, a webcam or computer with a built-in camera, and an audio headset.  You will also need to be in a quiet environment to avoid background noise and feedback. 

Please note that after this course is over, you will be asked to do three short follow-up exercises online in order to finish qualifying as an instructor within 90 days of your training event. Details are available at http://carpentries.github.io/instructor-training/checkout/.


Episodes
--------

Please read through *one* of the episodes below carefully, so that you can do some exercises based on it on the first day of the class.

Data Carpentry

* Faceting and Clustering in OpenRefine: http://www.datacarpentry.org/OpenRefine-ecology-lesson/01-working-with-openrefine
* Basic Queries in SQL: http://www.datacarpentry.org/sql-ecology-lesson/01-sql-basic-queries
* Starting with Data in R: http://www.datacarpentry.org/R-ecology-lesson/02-starting-with-data
* Starting with Data in Python: http://www.datacarpentry.org/python-ecology-lesson/01-starting-with-data

Software Carpentry

* Working with Files and Directories in the Unix Shell: http://swcarpentry.github.io/shell-novice/03-create/
* Tracking Changes in Git: http://swcarpentry.github.io/git-novice/04-changes/
* Selecting Data in SQL: http://swcarpentry.github.io/sql-novice-survey/01-select/
* Repeating Actions with Loops in Python: http://swcarpentry.github.io/python-novice-inflammation/02-loop/
* Exploring Data Frames in R: http://swcarpentry.github.io/r-novice-gapminder/05-data-structures-part2/


Please email me if you have any questions about how this all works. Many of your questions will also likely be answered by your instructors during the training. Good luck with everything - we are excited to have you on board!

Instructors are CC:ed here if you'd like to get in touch with anyone.

Best wishes,
[ ---- name ---- ] 

Send Trainers Zoom credentials and login information

Hi [---- names ---- ],

I just sent out an introductory email to the learners for your upcoming event. 

Here is the connection info:

https://carpentries.zoom.us/j/8243150376

One of you should log in to the Carpentries account with the following credentials. You will then be able to act as meeting host. 

username: room2@carpentries.org
password: room2carpentries_

Please let me know if you have any questions. 

Best,
[ ---- name ---- ] 

Email Trainers after event

Recruit Trainers to help score new applications

Notify accepted Trainer applicants

Hi all,

Thank you all for applying to become instructor Trainers with the Carpentries. A group of Trainers have reviewed the applications and we're excited to invite each of you to the Trainer team.

We'll be starting our new cohort of instructor Trainers in [----month---]. Our cohort will be [---number--] folks located in [-----countries------]. We'll be meeting once a week starting in [-----month-----] to discuss our text and how it relates to our instructor training curriculum. More details can be found in the preliminary reading schedule.

If you're interested in being part of this cohort, please try to complete the following by [------deadline-------] so that we can finalize the schedule and start our meetings!

1) Please fill out this poll for scheduling book club meetings. Don't forget to adjust the timezone shown (pull down menu above the time list). Please choose the day and times that work for you for the entire 8 week period of our book club. To complete certification as a Trainer, we'll ask that you miss at most one of our 8 book club meetings. Since we are spread across several time zones, please be as accommodating as possible in filling out your availability. We will have two meeting times per week to accomodate all time zones, but you will only need to attend one of the weekly meetings.

2) Please take a look over the process for trainer training and make sure that all of the requirements of becoming a Trainer work with your schedule and other responsibilities. We're excited to have you in the Trainer community, but do want to make sure that all Trainers are able to commit the time required, so that we are able to realistically determine the number of instructors we train per year.

3) Please get a copy of our text. I'll send out reading assignments and discussion guides in a later email. 

4) Please also fill out your availability for instructor training events for  [----- month through month -----] and add your name to the Trainers list in the second tab. This cohort of Trainers will be ready to co-teach instructor training events by the end of [---- month ----] and to teach on their own shortly after that.

5) Please add upcoming Trainer Business and Discussion meetings to your calendar. These are also on the Community Calendar. Each of these is held in two different time zones each, you don't need to attend both meetings - but you're welcome to!

6) Please sign up for the Trainers email list if you haven't already done so.

7) Please respond to this email with a quick introduction so that we can all get to know each other. I'll send out my introduction as a separate email following this.

I know that's a lot! Let me know if you have any questions. I'm looking forward to seeing you all at our first book club discussion.

Best,
[---- name -----]


Invitation to Re-apply prior to next application review:Invitation to Re-apply prior to next application review:

Hi [---names---],

Thank you for applying to become a Carpentry Instructor. We are glad to know of your interest in contributing to our community.

Applications are reviewed on a rolling basis. Ranking is based on a combination of regional, institutional, discipline, and diversity-related priorities, in addition to individual experience with teaching, community involvement, tool use, demonstration of continued interest, and other factors.

Your application has not yet been selected for invitation to an open training event. We are scheduled to review new applications soon, so if anything has changed that might affect your application, please submit a new application by [--- Date ---]. (Unfortunately we do not have any means of updating existing applications at this time.)

We have limited seats for trainees in our open training events. Another route towards becoming a trained instructor is to encourage your local institution or organization to become a member. For more information see: https://software-carpentry.org/scf/join/ and http://www.datacarpentry.org/partnerships/.

Thank you again for your interest! As our organization continues to grow we would like to be able to offer this training to all who are interested. 

Sincerely,

[---name---]



Respond to inquiries about future open trainings from previously accepted applicants:

Hi [---names---],

At this point open trainings occur only when member organizations do not claim a scheduled training event date. Events are converted to open trainings approximately 30-days ahead of their scheduled date, and become available on the open training signup sheet a day or two after that. If you look at our complete training schedule here (http://carpentries.github.io/instructor-training/training_calendar/) you can identify potential training dates that would work for you (pay attention to the time zone!), and set yourself a reminder to check the open training signup sheet to see if that training becomes open. 

I wish I could offer more specific details, but because of this structure these events will continue to occur unpredictably. Please let me know if you have any further questions or concerns!

Sincerely,

[---name---]

Respond to general inquiries about access to open trainings 
Hi [--names--],

Thank you for your interest in becoming a Carpentry Instructor! It sounds like you might be interested in applying for one of our Open Instructor Training events. These trainings occur when a scheduled Instructor Training event is not claimed by a member institution one month in advance. Because this happens occasionally and unpredictably, we currently have a backlog of applications.

We do rank applications periodically, and we encourage all interested parties to apply. Many things influence selection, including regional, institutional, discipline, and diversity-related priorities, as well as relevant background and involvement with the organization. Multiple applicants from a single institution generally will not be invited at once, but may be accepted individually over time.  To more rapidly build a trainer community at your institution, consider becoming a Member. For more information see: https://software-carpentry.org/scf/join/ and http://www.datacarpentry.org/partnerships/.

We are not currently in the practice of rejecting applications. You will be notified if you are accepted (this also occurs on a rolling basis as space becomes available), and you will receive a notice if you have not been accepted before the next round of application review, so that you can update in case anything has changed. You are welcome to inquire about the status of your application at any time.

We currently anticipate beginning our next review of applications December 13, so if you would like to be considered in this round, please apply now! 

The application is here. Note that the expectations for instructors are also listed there, and are a good idea to check before applying. For an open training, you may leave the “group” entry space blank.

Thank you for your interest!

Best regards,

[--name--]
