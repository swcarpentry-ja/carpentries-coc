
<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.3.1/jquery.min.js"></script>
<script type="text/javascript" src="https://cdnjs.cloudflare.com/ajax/libs/jstimezonedetect/1.0.4/jstz.min.js"></script>
<script type="text/javascript">
  $(function(){
  var timezone = jstz.determine();
  // var pref = '<iframe src="https://calendar.google.com/calendar/embed?title=The%20Carpentries%20Zoom%20Room%20Calendar';
  // var room1 = 'src=carpentries.org_35343537393139313639@resource.calendar.google.com';
  // var room2 = 'src=carpentries.org_3339393239343835343734@resource.calendar.google.com';
  // var room3 = 'src=carpentries.org_3430303438333733343331@resource.calendar.google.com';
  // var suff = '" style=" border-width:0 " width="800" height="600" frameborder="0" scrolling="no"></iframe>';
  // var full_link = pref + '&' + room1 + '&' + room2 + '&' room3 + '&' + timezone.name() + '&' suff;
  // var pref = '<iframe src="https://calendar.google.com/calendar/embed?title=The%20Carpentries%Zoom%20Room%20Calendar%20&src=carpentries.org_35343537393139313639%40resource.calendar.google.com&src=carpentries.org_3339393239343835343734%40resource.calendar.google.com&src=carpentries.org_3430303438333733343331%40resource.calendar.google.com&ctz=';
  // var iframe_html = pref + timezone.name() + suff;
  // var just_a_link = '<iframe src="https://calendar.google.com/calendar/embed?title=The%20Carpentries%20Zoom%20Room%20Calendar&mode=WEEK&src=carpentries.org_35343537393139313639%40resource.calendar.google.com&src=carpentries.org_3339393239343835343734@resource.calendar.google.com&src=carpentries.org_3430303438333733343331@resource.calendar.google.com&ctz=America%2FNew_York" style="border: 0" width="800" height="600" frameborder="0" scrolling="no"></iframe>'
  var pt1 = '<iframe src="https://calendar.google.com/calendar/embed?title=The%20Carpentries%20Zoom%20Room%20Calendar&mode=WEEK&src=carpentries.org_35343537393139313639%40resource.calendar.google.com&src=carpentries.org_3339393239343835343734@resource.calendar.google.com&src=carpentries.org_3430303438333733343331@resource.calendar.google.com&ctz='
  var pt2 = '" style="border: 0" width="800" height="600" frameborder="0" scrolling="no"></iframe>'
  full_link = pt1 + timezone.name() + pt2;
  document.getElementById('cc').innerHTML = full_link;
  console.log(full_link); 
  // console.log(iframe_html);  
  });
</script>


### Calendaring Events

The Carpentries offers three Zoom rooms for public community events.  Zoom rooms are available for events such as discussion sessions, teaching demos, and committee meetings.


#### General Room Usage and Links

Rooms are generally uses as follows.  However, any room can be used for other purposes if available.
Links below will open Zoom and enter the respective room.

* [**Room 1:**](https://carpentries.zoom.us/my/carpentriesroom1) Instructor Training
* [**Room 2:**](https://carpentries.zoom.us/my/carpentriesroom2) Instructor Training backup
* [**Room 3:**](https://carpentries.zoom.us/my/carpentriesroom3) Community events (teaching demos, discussion sessions, committee meetings, etc.)

Each room can have a host who will have privileges to mute people, create breakout rooms, etc.  Please contact team@carpentries.org if you would like host privileges for an event.

<!-- New rooms can be added following [these instructions](#). -->


#### Viewing Zoom Room availability

Zoom room calendar views are public - anyone can view whether a room is available.  Only Carpentries staff members can actually book a room. If a room is available, please contact a staff member or team@carpentries.org if you would like to make a room reservation.

Room availability can be viewed below.

Beyond this, checking to see if a room is available is just like you might for a conference room in real life.  Your office may have a calendar booking system but peeking in is the only way to know if a room is actually occupied.  You may use a room if no one is in it, but may get bumped if someone has a reservation.

<div id = 'cc'>Text here to be replaced by calendar</div>

<p>

#### Adding an Event to the Community Calendar

Note while anyone can view room availability, only Carpentries staff members may book events or reserve a Zoom room.

To add an event to the [Community Calendar](https://calendar.google.com/calendar/embed?src=oseuuoht0tvjbokgg3noh8c47g%40group.calendar.google.com&ctz=America%2FNew_York):

* Give the event a meaningful title ("Demos" is not as good as "Instructor Training Teaching Demos")
* List the time zone in UTC - not your local time zone.  Events set in local time zones do not always correctly adjust for daylight savings time.
* Add a description, including a link to the relevant etherpad or other document.

![Event Setup](images/event_setup.png)

* Select a room.
    * Hovering over a room will show a description of what that room is used for.

    ![View Rooms](images/view_rooms.png)

    * Each available room will be listed with the room's capacity. If you are scheduling a recurring event, any future conflict will prevent a given room from being listed as available.
    * Multiple rooms can be selected for a single event.
    * If you select a room and immediately remove it, it may not appear as available again until you close out the edit event screen and enter it again.
    * The event will now show up on the Carpentries Community Calendar and the Zoom Rooms Calendar.

![View Rooms](images/view_rooms.png)

<p>
#### Creating a Zoom Room Option on Google Calendars

This will only need to be done once for each new room.  This is already done for Zoom Rooms 1, 2, and 3.  If additional Zoom rooms are added, they will need to be set up here.  This must be done by someone with admin access to The Carpentries' Google console.  

Go to the [Google admin console](https://admin.google.com/AdminHome?hl=en).  Click on "Buildings and Resources" and then click "Edit Resources" under "Resource Management."

You will see all existing buildings and rooms listed. This feature is meant for physical buildings; we are using it for virtual videoconferencing rooms. One "building" is set up, called "Zoom Rooms" that contains three resouces -- Zoom Room 1, Zoom Room 2, and Zoom Room 3.  

To add a new "room" in this "building" - click on the yellow plus sign next to "Resources."  Fill out the following information:

* Category: Meeting space
* Type: Videoconferencing Room
* Building: Zoom Rooms
* Floor: Select "-" to indicate no floor
* Floor section: *leave blank*
* Resource name: Give this an easily recognizable name like "Zoom Room 4"
* Capacity: 100 (standard for all Zoom rooms)
* Features: *leave blank*
* User visible description: *leave blank*

When done, click "ADD RESOURCE" and this new room should be on your list of rooms.  This room will now be available for scheduling events as described below.