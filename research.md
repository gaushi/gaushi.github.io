---
title: "Research"
layout: page
---
<div class="tab">
  <button class="tablinks" onclick="openCity(event, 'London')">London</button>
  <button class="tablinks" onclick="openCity(event, 'Paris')">Paris</button>
  <button class="tablinks" onclick="openCity(event, 'Tokyo')">Tokyo</button>
</div>

<div id="London" class="tabcontent">
  <h3>London</h3>
  <p>London is the capital city of England.</p>
</div>

<div id="Paris" class="tabcontent">
  <h3>Paris</h3>
  <p>Paris is the capital of France.</p>
</div>

<div id="Tokyo" class="tabcontent">
  <h3>Tokyo</h3>
  <p>Tokyo is the capital of Japan.</p>
</div>

  #[details]({% link files/research1.md %})
  #{% include meta.html preview=true %}
   
  <ul>
   <li>
     <img style="float: center;" valign="bottom" src="/assets/images/Gautam_Hpa_infectedPlant.JPG" height="25%" width="25%"/>
     <div class="more"><a href="{% link files/research1.md %}">Details...</a></div>
   </li>
   <li>
      <div class="more"><a href="{% link files/research2.md %}">Second one..</a></div>
   </li>
   </ul>
