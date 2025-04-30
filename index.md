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
      <tr>
        <td><img src="images/sidebar/pizza.png" alt="pizza icon" /></td>
        <td>Food</td>
      </tr>
      <tr>
        <td><img src="images/sidebar/heart.png" alt="heart icon" /></td>
        <td>Misc</td>
      </tr>
    </table>
    <div class="recent">
    <h3>Recent Posts</h3>
      <ul class="recent-posts">
          {% for post in site.posts limit:10 %}
          <li><a href="{{ post.url | relative_url }}">{{ post.date | date: "%B %d, %Y" }} - {{ post.title }}</a></li>
          {% endfor %}
      </ul>
    </div>
  </aside>
</div>

<div class="markdown-body wrapper">
<iframe src="https://www.google.com/maps/d/u/3/embed?mid=1DcUqcTd055bTL4YQhc_bqsMnds2OYlQ&ehbc=2E312F&noprof=1" width="100%" height="600"></iframe>
<h2>Blog Introduction c:</h2>

<p>Hey all! Welcome to the page. In all honesty, this site is really only for myself; it's going to be more of a diary than a blog (lotta rambling basically). But, if you are here please enjoy.</p> 
  
<p>The main and original purpose was to use this simply as a way to house that map you see embedded above this introduction. As a way to visualize the libraries/archives 
in California and ones I visit outside of California. Here are some things to expect from my posts:</p>   
<ul>
  <li>Expect spelling and grammer errors, email me if you want me to fix them.</li>
  <li>Photos are going to be a little for organization, right-click and open in a new tab to see them full size. If I have them better quality email me and I would be happy to share.</li>
  <li>I will probably to too lazy to cite anything related to history, if you see any mistakes feel free to email me and correct me.</li>
  <li>I will be including silly arbitrary ratings for the libraries/archives I visit.</li>
  <li>I will be taking public transit to pretty much all the locations I visit, so I will mention it briefly each post.</li>
  <li>I will make sure to update in my blog posts what keyboard I am currently typing on, assuming it changes from my last keyboard update.</li>
  <li>Finally, I will occasially make unrelated posts about things I do.</li>
</ul>
  
<p>I have to mention the wonderful font you are hopefully seeing. It is called "Gorton Perfected". I have access to this from a KickStarter campaign I backed years ago. I love it and 
hopefully you do too. Man, this is way longer than I expected. I will be updating this in the future if anything changes or I think of anything new.</p>
</div>
