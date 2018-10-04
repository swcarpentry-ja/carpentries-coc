
<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.3.1/jquery.min.js"></script>
<script type="text/javascript" src="https://cdnjs.cloudflare.com/ajax/libs/jstimezonedetect/1.0.4/jstz.min.js"></script>
<script type="text/javascript">
  $(function(){
  var timezone = jstz.determine();
  var pt1 = '<iframe src="https://calendar.google.com/calendar/embed?title=The%20Carpentries%20Zoom%20Room%20Calendar&mode=WEEK&src=carpentries.org_35343537393139313639%40resource.calendar.google.com&src=carpentries.org_3339393239343835343734@resource.calendar.google.com&src=carpentries.org_3430303438333733343331@resource.calendar.google.com&ctz='
  var pt2 = '" style="border: 0" width="800" height="600" frameborder="0" scrolling="no"></iframe>'
  full_link = pt1 + timezone.name() + pt2;
  document.getElementById('zoom_calendar').innerHTML = full_link;
  // console.log(full_link); 
  });
</script>

### Scheduling Online Community Events

The Carpentries offers three Zoom rooms for public community events.  Zoom rooms are available for events such as discussion sessions, teaching demos, and committee meetings.


#### General Room Usage and Links

Rooms are generally used as follows.  However, any room can be used for other purposes if it is available.
Links below will open Zoom and enter the respective room.

* [**Room 1:**](https://carpentries.zoom.us/my/carpentriesroom1) Instructor Training
* [**Room 2:**](https://carpentries.zoom.us/my/carpentriesroom2) Instructor Training backup
* [**Room 3:**](https://carpentries.zoom.us/my/carpentriesroom3) Community events (teaching demos, discussion sessions, committee meetings, etc.)

Documentation on viewing room availability and reserving rooms is forthcoming. Please contact team@carpentries.org with any questions.

