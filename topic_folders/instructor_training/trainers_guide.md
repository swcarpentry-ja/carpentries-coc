### Trainers Guide

#### Trainer Meetings
The Trainers group meets regularly. Our meetings include three sections: 1) Discussion, where we share experiences and get advice about running instructor training events, 2) Announcements, and 3) Topic of the Month, which may include curriculum updates, active conversations occurring on GitHub or other Trainer channels, guest presentations, etc. Upcoming meetings are listed on [our Etherpad][trainer-pad] and on the [Community Calendar][community-calendar]. If you are not a Trainer, but are interested in joining a meeting, please contact Erin Becker (ebecker@carpentries.org). Minutes for these meetings [are available][trainer-minutes].

#### Signing up to Teach an Instructor Training Event

1. The Program Manager will send an email to the Trainers list asking all Trainers to fill in their calendar for the [upcoming time period](scheduling_training_events.html). Trainers should sign up for as many days as they are available and hold those dates in their calendar until the schedule is confirmed.
1. The Program Manager will confirm events with individual Trainers, at which point they are free to release all other dates on their calendar.
1. Member sites will sign up for available dates. The Program Manager will let Trainers know which sites they will be teaching as they sign up.
1. If no member site signs up one month before the event, the event will become an open instructor training or be cancelled, depending on need. The Program Manager will notify instructors of this decision.

A calendar for upcoming instructor training events is [here](http://carpentries.github.io/instructor-training/training_calendar/).

#### Trainer Checklists

##### Running an Instructor Training Event (General)

###### Four weeks before the event
-  Contact your co-Trainer(s) and decide who will teach what.  
-  Create an event Etherpad (using the [Etherpad template][etherpad-template]) or Google Doc (using the [Google Doc template][googledoc-template]) and a workshop website (using the [training template][training-template]).  *Note the Google Doc is not currently maintained and may not be in sync with lesson materials.*
-  Send Etherpad/Google Doc and website links to training@carpentries.org.  

###### One week before the event      
-  Plan logistics with co-Trainer(s)
-  Review (or set aside time closer to the event to review) the pre-assessment survey results for your workshop
-  If teaching remotely: 
  -  Get acquanted with using [Zoom](../communications/zoom_rooms.html#zoom-manual) for videoconferencing.
  -  Test videoconferencing set up with co-Trainer(s) using login credentials provided.   
  -  Decide with co-Trainer(s) whether all Trainers should be present for the full event or if you will log on during your scheduled teaching times only.  
  -  Make a copy of the [Virtual Minute Cards template][minute-cards-template] and personalize for your event.  
-  If teaching in person:
  - Confirm with your host that breakout rooms are available or make an alternate plan
  - Create a plan for printing handouts & determine who will bring sticky notes
  - Make sure you're prepared for the audiovisual setup in your room with the correct dongles/connectors etc.
  - Check on availability/timing of coffee, lunch, or any other details that matter to you 

###### During the event
-  Take attendance.  
-  Remind member trainees to fill out application (Open Training applicants have already done this).   
-  Remind trainees to sign up for demo, discussion (links in [checkout checklist][checkout-checklist]).  
-  Monitor the Etherpad / Google Doc for questions and responses to exercises.  
-  If teaching remotely: Turn off video during long exercises and coffee breaks and disconnect during lunch.  

###### Immediately after the event
-  Send a list of those who completed the training to checkout@carpentries.   
-  Send an email to trainees thanking them for participating and linking to [checkout checklist][checkout-checklist] using [this template](email_templates_trainers.html#email-after-training-event)  
-  Review survey results and prepare to discuss at upcoming [Trainers discussion meeting][trainer-pad].  
-  File any relevant issues or PRs to the [instructor training repo][training-repo].  

###### Long-term after the event 
-  Join a [Trainer meeting][trainer-pad] to discuss how your event went.   

#### Differences Between In-person and Online Training Events

##### In-person trainings
- When watching videos, project them to the whole group.   
- Assign (or let participants select) physical breakout groups.  
- Use physical sticky notes to get minute card feedback at lunch breaks and end of each day.  

##### Online trainings (a few small groups) 
- When watching videos, have one Trainer do a screenshare with their audio on or have one person in each group play the video for the participants at their site.  
- Assign (or let participants select) physical breakout groups.  
- Use the [virtual minute card][minute-cards-template] form to get feedback at lunch breaks and end of each day.  
- Have participants do all small-group exercises with participants at same site.  

##### Online trainings (completely distributed)  
- When watching videos, have all participants watch separately.  
- Assign breakout groups randomly to breakout rooms in Zoom. Be sure to remove Trainers and helpers when assigning groups. 
- Use the [virtual minute card][minute-cards-template] form to get feedback at lunch breaks and end of each day.  
- Have participants screen share with their breakout room during the live coding exercises.   
- For exercise to set up a workshop website, put participants in breakout rooms and have one person screen share while the others help guide them verbally.  


#### Running a Teaching Demonstration  

If you would like to watch an example teaching demo, there is a recording of one [here][demo-video].

##### Before the demo
-  Sign up to [lead demos][demo-pad].  
-  Get acquanted with using [Zoom](../communications/zoom_rooms.html#zoom-manual) for videoconferencing.
-  For each trainee, pick a suitable starting point in the lesson that they have chosen. Suggested lessons are available in the [Instructor Training Curriculum](https://carpentries.github.io/instructor-training/demo_lessons/index.html) (under *Extras*). Do not have them start in the middle of an episode. Note that some lessons (e.g., the Software Carpentry R lesson using inflammation data) have supplementary episodes. Do not pick from those.  

##### During the Demo
-  Go to the Zoom room. The link is in the [Etherpad][demo-pad].    
-  Once everyone is in the call (audio and video working), remind them of the Code of Conduct, explain the procedure for the demo session, and remind them that trainees have to be able to teach from any episode from their chosen lesson. Ask whether anyone has only prepared for 5 minutes from one episode instead of the entire lesson, and if so, suggest strongly they reschedule. It can help to remind them that this is not a high stakes test but a friendly opportunity for feedback.
-  Ask those not presenting to mute their microphone, and ask them to give feedback using the same positive-vs-negative and content-vs-presentation rubric used in training. For a full session (5 trainees), they should add feedback to the etherpad. If you have fewer people, you may choose to have them jot down comments and deliver them verbally as time allows.
-  Give the assignment to the first trainee, then give them a bit of time to set up the demo (they may have to import some packages, load some data, move to a certain folder etc).  
-  Ask them to share their screen using the “Share Screen” lower menu in Zoom.  
-  Once they are ready, give them a 3-2-1 countdown to start.  
-  Use a countdown timer which makes a noise once their 5 minutes are up (e.g., your phone), or just say “bong” really loudly at the end of their time.  
-  After the five minute timer, allow them to finish their sentence and tell them time’s up.
-  Use a [rubric][demo-rubric] to help you take notes.   
-  After the trainee is finished, first ask how they themselves thought it went. If you have time, other trainees can give verbal feedback, or you can summarize what is in the etherpad. Then, give focused, constructive feedback based on your notes and the comments of others. You might choose one or two things to particularly emphasize to help focus trainees' efforts as they proceed to teach a workshop. It is also sometimes necessary to take time to (gently) disagree with feedback from another trainee.
-  Do NOT tell a trainee whether they passed immediately after their demo.   
-  Repeat for the other trainees.  
-  At the end of the season, ask for general questions.  
-  If all of your trainees passed, you can tell the group at the end of the demo session. If anyone did not pass, tell everyone you will send them each an email to let them know if they passed.  

##### During the Demo (Troubleshooting)
- Refer to the [Zoom](../communications/zoom_rooms.html#zoom-manual) guide to help troubleshoot connection issues.
- If a trainee is teaching a Python lesson and their Jupyter notebook doesn't start, direct them to http://jupyter.org/try.

##### After the Demo 
-  Email checkout@carpentries.org with names, pass/fail, and SWC/DC/LC for each of your trainees.  
-  Clear Etherpad of data from your session.  
-  Send each trainee an email letting them know they [passed](email_templates_trainers.html#trainee-did-pass-teaching-demo) or [did not pass](email_templates_trainers.html#trainee-didnt-pass-teaching-demo) the teaching demo. If needed, let them know the reason they did not pass and asking them to retry.

##### Starting Points for Demos

This table has moved.  
Suggested lessons are available in the [Instructor Training Curriculum](https://carpentries.github.io/instructor-training/demo_lessons/index.html) (under *Extras*).


[trainer-agreement]: ../instructor_training/trainers_guide.html#trainer-agreement
[trainer-process]: ../instructor_training/trainers_training.html
[trainer-pad]: http://pad.software-carpentry.org/trainers-backup
[community-calendar]: https://software-carpentry.org/join/#community-events
[trainer-minutes]: https://github.com/carpentries/trainers/tree/master/minutes
[etherpad-template]: http://pad.software-carpentry.org/ttt-template
[googledoc-template]: https://docs.google.com/document/d/1P_w1rgdVk4SpXvILSS-ZKz8Ujqklfujpc_zHf8D-G1A/edit
[training-template]: https://github.com/carpentries/training-template
[minute-cards-template]: https://docs.google.com/forms/d/1p7iOV5HNvy4POS4g6eottY8RSfKq4kaoKz1-jIFYTMI/edit
[checkout-checklist]: http://www.datacarpentry.org/checkout/
[training-repo]: http://carpentries.github.io/instructor-training/
[zoom-home]: https://www.zoom.us/
[demo-video]: https://www.youtube.com/watch?v=FFO2cq-3PPg
[demo-pad]: http://pad.software-carpentry.org/teaching-demos-recovered
[demo-rubric]: http://carpentries.github.io/instructor-training/demos_rubric/


