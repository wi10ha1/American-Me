
<!DOCTYPE html>
<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
body {font-family: Arial;}

/* Style the tab */
.tab {
    overflow: hidden;
    border: 1px solid #ccc;
    background-color: #f1f1f1;
}

/* Style the buttons inside the tab */
.tab button {
    background-color: inherit;
    float: left;
    border: none;
    outline: none;
    cursor: pointer;
    padding: 14px 16px;
    transition: 0.3s;
    font-size: 17px;
}

/* Change background color of buttons on hover */
.tab button:hover {
    background-color: #ddd;
}

/* Create an active/current tablink class */
.tab button.active {
    background-color: #ccc;
}

/* Style the tab content */
.tabcontent {
    display: none;
    padding: 6px 12px;
    border: 1px solid #ccc;
    border-top: none;
}
</style>
</head>
<body style="background-color:#BCFFD1;">

<p><h1 style="color:#460889;" Align=Center>Will's American Me!</h1></p>

<div class="tab">
  <button class="tablinks" onclick="openCity(event, 'Introduction')">Introduction</button>
  <button class="tablinks" onclick="openCity(event, 'American Experience')">American Experience</button>
  <button class="tablinks" onclick="openCity(event, 'Future Plans')">Future Plans</button>
</div>

<div id="Introduction" class="tabcontent" style="color:#1946D1;">
  <h3>Introduction</h3>
  <h1 align=center style="color:#C21818;">Introduction Essay</h1>
  <hr>
  <p style="color:#5F1B56;" >Hello I am William John O’Halloran, this essay is an introduction to who I am. There are many ways to define a person like things they like, 
  dislike, fears, and hobbies. Humans are all basically the same genome sequence so the only way to set each other apart is by defining who we are.
  I was born on December 7th, 2000 to Paul and Sue O’Halloran. I had a normal childhood like most other kids, I went to daycare until I could go to school. During the 
  summers I went to the cabin with my family and hung out with friends whenever I could. When I was twelve I had an accident with my knee where I blew out my ACL and 
  tore my meniscus, I had to have surgery and my recovery time was about 2 months. I had a really hard time with this because I was unable to leave couch yet alone leave 
  house and that bothered me. I recovered fine and then everything went back to normal pretty quick.<br><br> 
  I live a very routine life, work in the summer, then school and during school I am in golf and hockey. Hockey is by far my most favorite sport/activity that I have ever 
  been apart of because it definitely has an effect on my life outside of the arena. Hockey is definitely a big part of who I am.<br><br> 
  I “graduated” from 8th grade at St. Mary’s in Bird Island and then I moved schools to BOLD High School in Olivia for my freshman year. I was pretty nervous for the change
  but I actually ended up liking BOLD a lot more than I thought I would. I coasted through freshman and sophomore year and through that time I learned a lot about myself
  and others like how to talk to people and how to treat people and I think that was because I finally realized that deep down everyone is not so different. I think that 
  after I realized something like that, it made interaction with others so much more enjoyable for me and that is probably why I can always be seen talking to another 
  person. During freshman year I found a deep love for music and in a very odd way, music has also helped me become who I am today. The type of music I would listen to 
  would change my mood and I was able to use that in productive ways ever since I found that out.<br><br> 
  During sophomore year I was chose to be one of the three captains on the hockey team and that was a really big deal for me because it is hockey and that alone meant a 
  lot to me but it was also a huge reward for what I have been working for in that sport. I would say that I am a leader rather than a follower and I think that is one 
  of the main reasons I was able to get elected. I find it a lot easier to be the leader I am in hockey than it is in school, but that doesn’t stop me from not trying 
  in school. I enjoy going to school because I like to interact with others and I take pride in my education because it is going to be affecting my future.<br><br> 
  If I had to choose a few words to describe myself I would choose spunky because any of my friends would tell you that I’m pretty weird, and my other word would be 
  determined because I don’t like to leave things unfinished because that would be selling yourself short!  
</p>
</div>

<div id="American Experience" class="tabcontent" style="color:#1946D1;">
  <h3 >American Experience</h3>
  <h1 align=center style="color:#C21818;">My Family Tree</h1>
  <hr>
  <p Align=Center><img src="C:\Users\wiloh\OneDrive\Pictures/famtree.png" alt="O'Halloran Family Tree" width="1014" height="523"></p>
  <h1 align=center style="color:#C21818;">My Family Interview</h1>
  <hr>
    <p>Interview goes here</p>
    <hr>
  <h1 align=center style="color:#C21818;">Family Stories</h1>
    <p>Family stories go here</p>  
</div>

<div id="Future Plans" class="tabcontent" style="color:#1946D1;">
  <h3>Future Plans</h3>
  <h1 align=center style="color:#C21818;">Future Plans</h1>
    <hr>
    <h1 align=center style="color:#C21818;">College Plan</h1>
	  <p>college plan goes here</p>
	<hr>
	<h1 align=center style="color:#C21818;">School</h1>
	  <p>plans for school go here</p>
	<hr>
	<h1 align=center style="color:#C21818;">Degree & Courses Needed</h1>
	  <p>plans for a degree and courses go here</p>
	<hr>
	<h1 align=center style="color:#C21818;">Costs/Room & Board</h1>
	  <p>plan for costs</p>
	<hr>
	<h1 align=center style="color:#C21818;">Average pay for Career</h1>
	  <p>Average pay stats go here</p>
	<hr>
	<h1 align=center style="color:#C21818;">Bucket List</h1>
	  <p>Bucket list goes here</p>
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
</script>
     
</body>
</html> 
