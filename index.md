<ul class="nav nav-tabs">
  <li class="nav-item">
    <a class="nav-link active" data-toggle="tab" href="#home">Home</a>
  </li>
  <li class="nav-item">
    <a class="nav-link" data-toggle="tab" href="#current">Current</a>
  </li>
  <li class="nav-item">
    <a class="nav-link" data-toggle="tab" href="#later">Later</a>
  </li>
  <li class="nav-item">
    <a class="nav-link" data-toggle="tab" href="#links">Links</a>
  </li>
  <li class="nav-item">
   <a class="nav-link" data-toggle="tab" href="#about">About</a>
  </li>
  <li class="nav-item">
    <a class="nav-link" data-toggle="link" href="media">Media</a>
  </li>
</ul>
<div id="myTabContent" class="tab-content">
  <div class="tab-pane fade active show" id="home">
    <p style="color: yellow; text-size: 20px; text-style: bold;">This website has been moved to <a href="https://SpiderGaming.gitlab.io/Personal" target="_blank">GITLAB</a></p>
  </div>
  <div class="tab-pane fade" id="current">
    <p>Im currently
      <br>- (not) Working on an incremental game (Link in the links tab) 
      <br>- Working on this website
      <br>- Learning HTML (done)
      <br>- Moving files (failed)
      <br>
      <br>- (not happening) Trying to intergrate Google Docs into this so the things I edit are easier
      <br>
      <br>I am {{ site.todobar }}% done with these tasks
      <br>
    </p>
      <div class="progress">
    <div class="progress-bar progress-bar-striped progress-bar-animated" role="progressbar" aria-valuenow="{{ site.todobar }}" aria-valuemin="0" aria-valuemax="100" style="width: {{ site.todobar }}%">
      </div>
    </div>
  </div>
  <div class="tab-pane fade" id="later">
    <p>Things I plan on doing later
      <br>- (done see it <a href="https://SpiderGaming.gitlab.io/Personal">Here</a>) Making a website (Likely this one) from scratch on github (not likely to happen for a long time)
      <br>- 
    </p>
  </div>
  <div class="tab-pane fade" id="links">
    <p>Sadly, there are only some links
      <br>- <a href="https://spidergamin.gitlab.io/Incremental-Universe/" style="color:cyan" target="_blank">Idle Universe</a> (Incremental Game)
      <br>- <a href="https://www.youtube.com/channel/UCO2rlcllQhQdPM8PZkqEAcA?view_as=subscriber" style="color:red" target="_blank">My YouTube Channel</a>
    </p>
  </div>
  <div class="tab-pane fade" id="about">
    <p>About me. You found it!
      <br>Here is where I'll put info about myself.
      <br>Nothing much here right now, check back later to see more content. :)
      <br>
    </p>
  </div>
</div>
<script>alert("HELLO!!!, This site has been moved to gitlab, go to the link displayed on the main page (it's yellow so you don't miss it\)")</script>
