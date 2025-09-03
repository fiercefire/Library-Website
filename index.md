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
        <td><img src="images/sidebar/red.png" alt="red square" /></td>
        <td>Unvisited</td>
      </tr>
      <tr>
        <td><img src="images/sidebar/green.png" alt="green square" /></td>
        <td>Visited</td>
      </tr>
    </table>
    <table border="1">
      <tr>
        <td><img src="images/sidebar/book.png" alt="book icon" /></td>
        <td>Public</td>
      </tr>
      <tr>
        <td><img src="images/sidebar/grad-cap.png" alt="grad cap icon" /></td>
        <td>Academic</td>
      </tr>
      <tr>
        <td><img src="images/sidebar/question-mark.png" alt="question mark icon" /></td>
        <td>Archive</td>
      </tr>
    </table>
    <div class="recent">
    <h3>Recent Posts</h3>
      <ul class="recent-posts">
          {% for post in site.posts limit:5 %}
          <li><a href="{{ post.url | relative_url }}">{{ post.date | date: "%B %d, %Y" }} - {{ post.title }}</a></li>
          {% endfor %}
      </ul>
    </div>
  </aside>
</div>

<div class="markdown-body wrapper">
<iframe src="https://www.google.com/maps/d/u/3/embed?mid=1DcUqcTd055bTL4YQhc_bqsMnds2OYlQ&ehbc=2E312F&noprof=1" width="100%" height="600"></iframe>
<h2>Blog Introduction c:</h2>

<p>Hey all! Welcome to the page. In all honesty, this site is really only for me. There is going to be a lot of rambling but, if you are here please enjoy.</p> 
  
<p>The main purpose was to use this as a way to house that map you see embedded above this introduction. As a way to visualize the libraries/archives 
in California and ones I visit outside of California. And I'll probably talk about the food I eat.</p>   

<p>I have to mention the wonderful font you are hopefully seeing. It is called "Gorton Perfected". I have access to this from a KickStarter campaign I backed years ago. I love it and 
hopefully you do too.</p>
</div>
