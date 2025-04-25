---
layout: home
---
<link rel="stylesheet" href="css/custom.css">
<link rel="stylesheet" href="css/font.css" type="text/css">

<!-- Left Sidebar -->
<div class="container">
  <aside class="sidebar-left">
    <h3>Map Legend</h3>
    <table border="1">
      <tr>
        <td><img src="images/red.png" alt="red square" /></td>
        <td>Unvisited</td>
      </tr>
      <tr>
        <td><img src="images/green.png" alt="green square" /></td>
        <td>Visited</td>
      </tr>
    </table>
    <table border="1">
      <tr>
        <td><img src="images/book.png" alt="book icon" /></td>
        <td>Public</td>
      </tr>
      <tr>
        <td><img src="images/grad-cap.png" alt="grad cap icon" /></td>
        <td>Academic</td>
      </tr>
      <tr>
        <td><img src="images/question-mark.png" alt="question mark icon" /></td>
        <td>Archive</td>
      </tr>
      <tr>
        <td><img src="images/pizza.png" alt="pizza icon" /></td>
        <td>Food</td>
      </tr>
      <tr>
        <td><img src="images/heart.png" alt="heart icon" /></td>
        <td>Misc</td>
      </tr>
    </table>
    <div class="recent">
    <h3>Recent Posts</h3>
      <ul class="recent-posts">
          {% for post in site.posts limit:7 %}
          <li><a href="{{ post.url | relative_url }}">{{ post.date | date: "%B %d, %Y" }} - {{ post.title }}</a></li>
          {% endfor %}
      </ul>
    </div>
  </aside>
</div>

<div class="markdown-body wrapper">
<iframe src="https://www.google.com/maps/d/u/3/embed?mid=1DcUqcTd055bTL4YQhc_bqsMnds2OYlQ&ehbc=2E312F&noprof=1" width="100%" height="600"></iframe>
<h2>Blog Introduction c:</h2>
---
<p>Hey all! Welcome to the page. In all honesty, this site is really only for myself; it's going to be more of a diary than a blog (lotta rambling basically). But, if you are here please enjoy.</p> 
  
<p>The main and original purpose was to use this simply as a way to house that map you see embedded above this introduction. As a way to visualize the libraries/archives 
in California and ones I visit outside of California. Here are some things to expect from my posts:</p>   
<ul>
  <li>Everything I put out here will be lazy and sloppy. That includes photo quality, spelling, and grammar.</li>
  <li>If I talk about any history, I will be doing research and trying to make sure everything is right but I will be too lazy to cite anything formally. Feel free to fact-check me if you'd like and email me any errors so I can fix them if you feel strongly enough about it.</li>
  <li>I will probably be getting a decent SLR 35mm camera to take pictures of the libraries/archives along with anything else noteworthy. I am new to photography so it will be rough but fun to learn.</li>
  <li>I will be including silly arbitrary ratings for the libraries/archives I visit.</li>
  <li>I will be taking public transit to pretty much all the locations I visit, so I will probably talk about that a bit in each post.</li>
  <li>I will make sure to update in my blog posts what keyboard I am currently typing on, assuming it changes from my last keyboard update.</li>
  <li>I might talk about the architecture of the places I visit, I am not very knowledgeable but could be fun to learn on the go.</li>
  <li>I am very likely to take the opportunity in my blog posts to highlight some history about the libraries/archives I visit.</li>
  <li>In the future I may include some outstanding food I eat; both in a short blog post and in the central map of the site (all food being grouped in its own layer).</li>
  <li>Finally, if I go on any major trips, solo or otherwise, I may make a short blog post about them with a bunch of photos. Maybe.</li>
</ul>
  
<p>I have to mention the wonderful font you are hopefully seeing. It is called "Gorton Perfected". I have access to this from a KickStarter campaign I backed years ago. I love it and 
hopefully you do too. Man, this is way longer than I expected. I will be updating this in the future if anything changes or I think of anything new.</p>
</div>
