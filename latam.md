---
title: Latam
---

<figure class="figure">
  <center>
  <img src="{{ site.baseurl }}/assets/coverLatam.png" alt="advertisement for the workshop" class="vid-fluid rounded center">
  </center>
</figure>

>Latam Regional Workshop on SciTinyML: Scientific Use of Machine Learning on Low-Power Devices will be run virtually from July 11-15, 2022. <br> The Zoom link will be sent out to all registered attendees. The sign-up link is [available here](https://indico.ictp.it/event/9811/). The Latam Regional Workshop will be taught in Spanish with select presentations in English.


<div id = "LOCAL_TIME"></div><br/>

{% include schedule_table table_data = site.data.latam_schedule %}

<script>
  // top time
  var start = new Date('10/18/2021 7:00:00 AM UTC');
  var end = new Date('10/18/2021 10:00:00 AM UTC');
  var localTime = start.toLocaleTimeString([], {timeStyle: 'short'}) + " to " + end.toLocaleTimeString([], {timeStyle: 'short'});
  var startString = "The workshop will run each day from <b>7:00 AM to 10:00 AM UTC (and until 11:00 AM UTC on Friday) which is "
  var endString = " in your local timezone</b> (according to your computer system time). Times below adjusted to that time zone. Exact timing and topics subject to change."
  document.getElementById('LOCAL_TIME').innerHTML = startString + localTime + endString;
  
  // all times
  var timeElements = document.getElementsByClassName("GMT_TIME");
  for (var i = 0; i < timeElements.length; i++) {
    dateStr = '10/18/2021 ' + timeElements[i].innerHTML + ' UTC'
    var gmt_time = new Date(dateStr);
    timeElements[i].innerHTML = gmt_time.toLocaleTimeString([], {timeStyle: 'short'})
  }
</script>

