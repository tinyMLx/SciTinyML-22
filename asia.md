---
title: Asia
---

<figure class="figure">
  <center>
  <img src="{{ site.baseurl }}/assets/coverAsia.png" alt="advertisement for the workshop" class="vid-fluid rounded center">
  </center>
</figure>

>Asian Regional Workshop on SciTinyML: Scientific Use of Machine Learning on Low-Power Devices will be run virtually from June 6-10, 2022. <br> The Zoom link will be sent out to all registered attendees. The sign-up link will be posted soon.

# More Information Coming Soon!

<!-- <div id = "LOCAL_TIME"></div> -->

<!-- {% include schedule_table table_data = site.data.asia_schedule %} -->

<script>
  // top time
  var start = new Date('10/18/2021 1:00:00 PM UTC');
  var end = new Date('10/18/2021 4:00:00 PM UTC');
  var localTime = start.toLocaleTimeString([], {timeStyle: 'short'}) + " to " + end.toLocaleTimeString([], {timeStyle: 'short'});
  var startString = "The workshop will run each day from <b>1:00 PM to 4:00 PM GMT which is "
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
