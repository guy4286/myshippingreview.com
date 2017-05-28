# myshippingreview.com
Git repo for my personal shipping review website of UPakWeShip/EuroUSA

# instructions for moderating comments:
At the top of index.html there is a list of meta properties - og:image, og:title, etc.
Add the following property to the top of the list, just below the stylesheet link:
  <meta property="fb:admins" content="705917268"/>
Upload index.html using FTP, revisit the website and a "Moderation Tool" link will
appear above the comments section.  If it doesn't show up immediately, can use the
Facebook debugger (https://developers.facebook.com/tools/debug/) to scrape the website
and then it should show up.  Also need to be logged in to Facebook for it to show up.
