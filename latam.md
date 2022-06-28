---
title: Latam
---

<figure class="figure">
  <center>
  <img src="{{ site.baseurl }}/assets/coverLatam.png" alt="advertisement for the workshop" class="vid-fluid rounded center">
  </center>
</figure>

>Latam Regional Workshop on SciTinyML: Scientific Use of Machine Learning on Low-Power Devices will be run virtually from July 11-15, 2022. <br> The Zoom link will be sent out to all registered attendees. The sign-up link is [available here](https://indico.ictp.it/event/9811/). <b>The Latam Regional Workshop will be taught majority in Spanish (SP)</b> with select presentations in English (EN).


<div id = "LOCAL_TIME"></div><br/>

{% include schedule_table table_data = site.data.latam_schedule %}

<script>
  // top time
  var start = new Date('10/18/2021 1:00:00 PM GMT');
  var end = new Date('10/18/2021 4:00:00 PM GMT');
  var localTime = start.toLocaleTimeString([], {timeStyle: 'short'}) + " to " + end.toLocaleTimeString([], {timeStyle: 'short'});
  var startString = "The workshop will run each day from <b>1:00 PM to 4:00 PM GMT (and until 4:00 PM GMT on Friday) which is "
  var endString = " in your local timezone</b> (according to your computer system time). As a reference, the Workshop will start at 9:00 AM (Boston/Santiago); 10:00 AM (Buenos Aires/Brasilia). Times below adjusted to that time zone. Exact timing and topics subject to change."
  document.getElementById('LOCAL_TIME').innerHTML = startString + localTime + endString;
  
  // all times
  var timeElements = document.getElementsByClassName("GMT_TIME");
  for (var i = 0; i < timeElements.length; i++) {
    dateStr = '10/18/2021 ' + timeElements[i].innerHTML + ' UTC'
    var gmt_time = new Date(dateStr);
    timeElements[i].innerHTML = gmt_time.toLocaleTimeString([], {timeStyle: 'short'})
  }
</script>

