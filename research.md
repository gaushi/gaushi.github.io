---
title: "Research"
layout: page
---

```javascript
function openCity(evt, cityName) {
  // Declare all variables
  var i, tabcontent, tablinks;

  // Get all elements with class="tabcontent" and hide them
  tabcontent = document.getElementsByClassName("tabcontent");
  for (i = 0; i < tabcontent.length; i++) {
    tabcontent[i].style.display = "none";
  }

  // Get all elements with class="tablinks" and remove the class "active"
  tablinks = document.getElementsByClassName("tablinks");
  for (i = 0; i < tablinks.length; i++) {
    tablinks[i].className = tablinks[i].className.replace(" active", "");
  }

  // Show the current tab, and add an "active" class to the link that opened the tab
  document.getElementById(cityName).style.display = "block";
  evt.currentTarget.className += " active";
} 
```
#<div style="position: relative; margin: 1.5em 0; padding-bottom: 56.25%;">
 #<iframe style="position: absolute;" src="/UNLICENSE.txt" width="100%" height="100%" frameborder="0" allowfullscreen></iframe>
#</div>

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
   
  <table valign="top" align="center">
  <tr>
    <td width="20%" height="100%" valign="top" align="left"><img style="float: center;" src="/assets/images/Gautam_Hpa_infectedPlant.JPG" height="95%" width="95%"/><div class="more"><a href="{% link files/research1.md %}">Details..</a></div></td>
    <td width="20%" height="100%" valign="top" align="left"><img style="float: center;" src="/assets/images/Gautam_Indiana.JPG" height="95%" width="95%"/><div class="more"><a href="{% link files/research2.md %}">Second one..</a></div></td>
    <td width="20%" height="100%" valign="top" style="border: none;">
      <a href="/research3.md">
        <img style="float: center;" src="/assets/images/Gautam_Hpa_infectedPlant.JPG" height="95%" width="95%"/>
      </a>
    </td>
    <td width="20%" height="100%" valign="top" style="border: none;">
      <a href="/research4.md">
        <img style="float: center;" src="/assets/images/Gautam_Hpa_infectedPlant.JPG" height="95%" width="95%"/>
      </a>
    </td>
  </tr>
  </table>
