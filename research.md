---
title: "Research"
layout: page
---
<div class="tab">
  <button class="tablinks" onclick="openCity(event, 'R1')" id="defaultOpen">Research 1 </button>
  <button class="tablinks" onclick="openCity(event, 'R2')">Research 2</button>
  <button class="tablinks" onclick="openCity(event, 'R3')"">Research 3</button>
</div>

<div id="R1" class="tabcontent">
  <h3>Research 1</h3>
  <p>London is the capital city of England.</p>
</div>

<div id="R2" class="tabcontent">
  <h3>Research 2</h3>
  <p>Paris is the capital of France.</p> 
</div>

<div id="R3" class="tabcontent">
  <h3>Research 3</h3>
  <p>Tokyo is the capital of Japan.</p>
</div>

<script>
function openCity(evt, cityName) {
  var i, tabcontent, tablinks;
  tabcontent = document.getElementsByClassName("tabcontent");
  for (i = 0; i < tabcontent.length; i++) {
    tabcontent[i].style.display = "none";
  }
  tablinks = document.getElementsByClassName("tablinks");
  for (i = 0; i < tablinks.length; i++) {
    tablinks[i].className = tablinks[i].className.replace(" active", "");
  }
  document.getElementById(cityName).style.display = "block";
  evt.currentTarget.className += " active";
}

// Get the element with id="defaultOpen" and click on it
document.getElementById("defaultOpen").click();
</script>
