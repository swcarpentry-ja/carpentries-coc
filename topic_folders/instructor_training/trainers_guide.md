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
-  Create an event Etherpad (using the [Etherpad template][etherpad-template]) or Google Doc and a workshop website (using the [training template][training-template]).  
-  Send Etherpad/Google Doc and website links to training@carpentries.org.  

###### Two weeks before the event
-  Introduce yourself to your trainees.  

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
-  Get acquanted with using [Zoom](../communications/zoom_rooms.html/zoom-manual) for videoconferencing.
-  For each trainee, pick a suitable starting point in the lesson that they have chosen. For most lessons, any episode will be suitable. There are a few exceptions - [listed below](#starting-points-for-demos). Do not have them start in the middle of an episode. Note that some lessons (e.g., the Software Carpentry R lesson using inflammation data) have supplementary episodes. Do not pick from those.  

##### Shortly Before the Demo
-  Go to the Zoom room. The link is in the [Etherpad][demo-pad].    
-  Once everyone is in the call (audio and video working), remind them of the Code of Conduct, explain the procedure for the demo session, and remind them that trainees have to be able to teach from any episode from their chosen lesson. Ask whether anyone has only prepared for 5 minutes from one episode instead of the entire lesson, and if so, suggest strongly they reschedule.    
-  Ask those not presenting to mute their microphone, and tell them they are to give feedback in the Etherpad using the same positive-vs-negative and content-vs-presentation rubric used in training.    
-  Hand out the assignment to the first trainee, give them a bit of time to set up the demo (they may have to import some packages, load some data, move to a certain folder etc).  
-  Ask them to share their screen using the “Share Screen” lower menu in Zoom.  
-  Once they are ready, give them a 3-2-1 countdown to start.  
-  Use a countdown timer which makes a noise once their 5 minutes are up (e.g., your phone), or just say “bong” really loudly at the end of their time.  
-  After the five minute timer, allow them to finish their sentence and tell them time’s up.
-  Use a [rubric][demo-rubric] for notes.   
-  After the trainee is finished, first ask how they themselves thought it went, then give constructive feedback based on your notes.  
-  Do NOT tell a trainee whether they passed immediately after their demo.   
-  Repeat for the other trainees.  
-  At the end of the season, ask for general questions.  
-  If all of your trainees passed, you can tell the group at the end of the demo session. If anyone did not pass, tell everyone you will send them each an email to let them know if they passed.  

##### During the Demo (Troubleshooting)
- If a trainee is using Linux and gets the error message "Can not start share, wayland has not been supported yet, 
please use x11 instead", have them log out of Zoom and log back in. On the login screen there is a gear with a dropdown menu there choose the option with x11.
- If a trainee is teaching a Python lesson and their Jupyter notebook doesn't start, direct them to http://jupyter.org/try.

##### After the Demo 
-  Email checkout@carpentries.org with names, pass/fail, and SWC/DC/LC for each of your trainees.  
-  Clear Etherpad of data from your session.  
-  Send each trainee an email letting them know they [passed](email_templates_trainers.html#trainee-did-pass-teaching-demo) or [did not pass](email_templates_trainers.html#trainee-didnt-pass-teaching-demo) the teaching demo. If needed, let them know the reason they did not pass and asking them to retry.

##### Starting Points for Demos
Please see the table below for recommendations about choosing a starting point for trainee teaching demonstrations. 

| Carpentry | Curriculum | Lesson  | Avoid | Good Starting Points | Notes | 
| --------- | ---- | ------- | ------ | ----- | ----- | 
| SWC | |  [The Unix Shell](http://swcarpentry.github.io/shell-novice/) | [Introducing the Shell](https://swcarpentry.github.io/shell-novice/01-intro) | any other episode | [Introducing the Shell](https://swcarpentry.github.io/shell-novice/01-intro) has no live coding. |
| SWC | |  [Version Control with Git](http://swcarpentry.github.io/git-novice/) | any other episode | <ul><li>[Setting up Git](http://swcarpentry.github.io/git-novice/02-setup)</li><li>[Creating a Repository](http://swcarpentry.github.io/git-novice/03-create)</li><li>[Tracking Changes](http://swcarpentry.github.io/git-novice/04-changes)</li></ul> | [Automated Version Control](http://swcarpentry.github.io/git-novice/01-basics) has no live coding. Later episodes have dependencies. | 
| SWC | | [Version Control with Mercurial](http://swcarpentry.github.io/hg-novice/) | any other episode | <ul><li>[Configuring Mercurial](http://swcarpentry.github.io/hg-novice/02-configuration/)</li><li>[Creating a Repository](http://swcarpentry.github.io/hg-novice/03-create-repo/)</li><li>[Tracking Changes to Files](http://swcarpentry.github.io/hg-novice/04-tracking/)</li></ul> | [Automated Version Control](http://swcarpentry.github.io/hg-novice/01-basics/) has no live coding. Later episodes have dependencies. | 
| SWC | | [Using Databases and SQL](http://swcarpentry.github.io/sql-novice-survey/) | [Data Hygiene](https://swcarpentry.github.io/sql-novice-survey/08-hygiene/) | any other episode | [Data Hygiene](https://swcarpentry.github.io/sql-novice-survey/08-hygiene/) has no live coding. |
| SWC | | [Programming with Python](http://swcarpentry.github.io/python-novice-inflammation/) | [Debugging](https://swcarpentry.github.io/python-novice-inflammation/09-debugging/) | any other episode | [Debugging](https://swcarpentry.github.io/python-novice-inflammation/09-debugging/) has no live coding. | 
| SWC | | [R for Reproducible Scientific Analysis](http://swcarpentry.github.io/r-novice-gapminder/) | [Writing Good Software](https://swcarpentry.github.io/r-novice-gapminder/16-wrap-up/) | any other episode | [Writing Good Software](https://swcarpentry.github.io/r-novice-gapminder/16-wrap-up/) has no live coding. |
| SWC | | [Automation and Make](http://swcarpentry.github.io/make-novice/) | any other episode | <ul><li>[Introduction](http://swcarpentry.github.io/make-novice/01-intro)</li><li>[Makefiles](http://swcarpentry.github.io/make-novice/02-makefiles)</li></ul> | Later episodes have dependencies. | 
| | | | | | | |
| DC | Ecology | [Data Organization in Spreadsheets for Ecologists](https://datacarpentry.org/spreadsheet-ecology-lesson/) | none | any episode | |
| DC | Ecology | [Data Cleaning with OpenRefine for Ecologists](https://datacarpentry.org/OpenRefine-ecology-lesson/) | any other episode | [Working with OpenRefine](https://datacarpentry.org/OpenRefine-ecology-lesson/01-working-with-openrefine) | [Introduction](https://datacarpentry.org/OpenRefine-ecology-lesson/00-getting-started) has no live coding. Later episodes have dependencies. |
| DC | Ecology | [Data Analysis and Visualization in R for Ecologists](https://datacarpentry.org/R-ecology-lesson/) | <ul><li>[Before We Start](http://www.datacarpentry.org/R-ecology-lesson/00-before-we-start.html)</li><li>[Data Visualization with ggplot2](https://datacarpentry.org/R-ecology-lesson/04-visualization-ggplot2.html)</li><li>[SQL Databases and R](https://datacarpentry.org/R-ecology-lesson/05-r-and-databases.html)</li></ul> | any other episode |  [Before We Start](http://www.datacarpentry.org/R-ecology-lesson/00-before-we-start.html) has no live coding. [Data Visualization with ggplot2](https://datacarpentry.org/R-ecology-lesson/04-visualization-ggplot2.html) has dependecies. [SQL Databases and R](https://datacarpentry.org/R-ecology-lesson/05-r-and-databases.html) is generally not taught in a 2 day workshop. |
| DC | Ecology | [Data Management with SQL for Ecologists ](http://www.datacarpentry.org/sql-ecology-lesson/) | [Databases using SQL](http://www.datacarpentry.org/sql-ecology-lesson/00-sql-introduction/) | any other episode | Live coding in [Databases using SQL](http://www.datacarpentry.org/sql-ecology-lesson/00-sql-introduction/) starts in the middle of the episode. | 
| DC | Ecology | [Data Analysis and Visualization in Python for Ecologists](http://www.datacarpentry.org/python-ecology-lesson/) | any other episode | <ul><li>[Short Introduction to Programming in Python](https://datacarpentry.org/python-ecology-lesson/01-short-introduction-to-Python/)</li><li>[Starting with Data](https://datacarpentry.org/python-ecology-lesson/02-starting-with-data/)</li><li>[Indexing, Slicing, and Subsetting DataFrames in Python](https://datacarpentry.org/python-ecology-lesson/03-index-slice-subset/)</li><li>[Data Types and Formats](https://datacarpentry.org/python-ecology-lesson/04-data-types-and-format/)</li><li>[Combining DataFrames with Pandas](https://datacarpentry.org/python-ecology-lesson/05-merging-data/)</li><li>[Data Workflows and Automation](https://datacarpentry.org/python-ecology-lesson/06-loops-and-functions/)</li></ul> | [Before we Start](https://datacarpentry.org/python-ecology-lesson/00-before-we-start/) has no live coding. Later episodes have dependencies. | 
| | | | | | | |
| DC | Genomics | [Project Organization and Management for Genomics](https://datacarpentry.org/organization-genomics/) | Do not use | Do not use | |
| DC | Genomics | [Introduction to the Command Line for Genomics](https://datacarpentry.org/shell-genomics/) | Do not use | Do not use | |
| DC | Genomics | [Data Wrangling and Processing for Genomics](https://datacarpentry.org/wrangling-genomics/) | Do not use | Do not use | | 
| DC | Genomics | [Introduction to Cloud Computing for Genomics](https://datacarpentry.org/cloud-genomics/) | Do not use | Do not use | | 
| DC | Genomics | [Data Analysis and Visualization in R for Genomics](https://datacarpentry.org/R-genomics/) | Do not use | Do not use | This lesson is in alpha. Do not use for teaching demos. |
| | | | | | | |
| DC | Social Sciences | [Data Organization in Spreadsheets for Social Scientists](https://datacarpentry.org/spreadsheets-socialsci/) | none | any episode | |
| DC | Social Sciences | [Data Cleaning with OpenRefine for Social Scientists](http://www.datacarpentry.org/openrefine-socialsci/) | any other episode | [Working with OpenRefine](http://www.datacarpentry.org/openrefine-socialsci/02-working-with-openrefine/) | [Introduction](https://datacarpentry.org/openrefine-socialsci/01-introduction/) has no live coding. Later episodes have dependencies. |
| DC | Social Sciences | [Data Analysis and Visualization with R for Social Scientists](http://www.datacarpentry.org/r-socialsci/) | <ul><li>[Before We Start](http://www.datacarpentry.org/r-socialsci/00-intro/)</li><li>[Data Visualization with ggplot2](https://datacarpentry.org/r-socialsci/04-ggplot2/)</li></ul>| any other episode | [Before We Start](http://www.datacarpentry.org/r-socialsci/00-intro/) has no live coding. [Data Visualization with ggplot2](https://datacarpentry.org/r-socialsci/04-ggplot2/) has dependencies. |
| DC | Social Sciences | [Data Analysis and Visualization with Python for Social Scientists](https://datacarpentry.org/python-socialsci/) | Do not use | Do not use | This lesson is in alpha. Do not use for teaching demos. |
| DC | Social Sciences | [Data Management with SQL for Social Scientists](https://datacarpentry.org/sql-socialsci/) | Do not use | Do not use | This lesson is in alpha. Do not use for teaching demos. |
| | | | | | | |
| DC | Geospatial | [Geospatial Project Organization and Management](https://datacarpentry.org/organization-geospatial/) | all episodes | none | This lesson has no live coding. Do not use for teaching demos. |
| DC | Geospatial | [Introduction to R for Geospatial Data](https://datacarpentry.org/r-intro-geospatial/) | none | any episode | |
| DC | Geospatial | [Introduction to Geospatial Raster and Vector Data with R](https://datacarpentry.org/r-raster-vector-geospatial/) | any other episode | <ul><li>[Intro to Raster Data in R](https://datacarpentry.org/r-raster-vector-geospatial/01-raster-structure/)</li><li>[Reproject Raster Data in R](https://datacarpentry.org/r-raster-vector-geospatial/03-raster-reproject-in-r/)</li><li>[Work with Multi-Band Rasters in R](https://datacarpentry.org/r-raster-vector-geospatial/05-raster-multi-band-in-r/)</li><li>[Open and Plot Shapefiles in R](https://datacarpentry.org/r-raster-vector-geospatial/06-vector-open-shapefile-in-r/)</li><li>[Handling Spatial Projection & CRS in R](https://datacarpentry.org/r-raster-vector-geospatial/09-vector-when-data-dont-line-up-crs/)</li><li>[Convert from a .csv to a Shapefile in R](https://datacarpentry.org/r-raster-vector-geospatial/10-vector-csv-to-shapefile-in-r/)</li><li>[Raster Time Series Data in R](https://datacarpentry.org/r-raster-vector-geospatial/12-time-series-raster/)</li></ul> | Many episodes rely on data that learners have loaded from previous episodes. These can be used as starting points, but trainees may need extra time to set up their environment. | 
| | | | | | | |
| LC | | [Library Carpentry: The Shell Lesson](https://librarycarpentry.github.io/lc-shell/) | [What is the shell?](https://librarycarpentry.github.io/lc-shell/01-intro-shell/)  | <ul><li>[ Navigating the filesystem](https://librarycarpentry.github.io/lc-shell/02-navigating-the-filesystem/index.html)</li><li>[Working with files and directories](https://librarycarpentry.github.io/lc-shell/03-working-with-files-and-folders/index.html)</li><li>[Automating the tedious with loops](https://librarycarpentry.github.io/lc-shell/04-loops/index.html)</li><li>[Counting and mining with the shell](https://librarycarpentry.github.io/lc-shell/05-counting-mining/index.html)</li><li>[Working with free text](https://librarycarpentry.github.io/lc-shell/06-free-text/index.html)</li></ul> |  [What is the shell?](https://librarycarpentry.github.io/lc-shell/01-intro-shell/) has no live coding. |
| LC | | [Library Carpentry OpenRefine](https://librarycarpentry.org/lc-open-refine/) | any other episode | [Importing data into OpenRefine](https://librarycarpentry.org/lc-open-refine/02-importing-data/index.html) | [Introduction to OpenRefine](Introduction to OpenRefine) has no live coding. Later episodes have dependencies. |

[trainer-agreement]: ../instructor_training/trainers_guide.html#trainer-agreement
[trainer-process]: ../instructor_training/trainers_training.html
[trainer-pad]: http://pad.software-carpentry.org/trainers-backup
[community-calendar]: https://software-carpentry.org/join/#community-events
[trainer-minutes]: https://github.com/carpentries/trainers/tree/master/minutes
[etherpad-template]: http://pad.software-carpentry.org/ttt-template
[training-template]: https://github.com/carpentries/training-template
[minute-cards-template]: https://docs.google.com/forms/d/1p7iOV5HNvy4POS4g6eottY8RSfKq4kaoKz1-jIFYTMI/edit
[checkout-checklist]: http://www.datacarpentry.org/checkout/
[training-repo]: http://carpentries.github.io/instructor-training/
[zoom-home]: https://www.zoom.us/
[demo-video]: https://www.youtube.com/watch?v=FFO2cq-3PPg
[demo-pad]: http://pad.software-carpentry.org/teaching-demos-recovered
[demo-rubric]: http://carpentries.github.io/instructor-training/demos_rubric/


