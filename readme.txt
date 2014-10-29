JAILBREAK CSS TEST - README
-------------------------------------------------------------------------------------------------------

FILES INCLUDED IN THIS PACKAGE

  1.  CSS
  2.  Sidebar text
  3.  Image assets

HOW TO GET IMAGES IN SIDEBAR

  1.  Upload sidebar images
  2.  Paste the following into the CSS (there should be several already in the CSS provided):
  
        .side a[href="YOUR-URL-HERE"] {
        	display: inline-block;
        	height: 32px;
  	        width: 300px;
  	        background: url(%%IMAGE-NAME-HERE%%) no-repeat 0 0;
  	        margin-top: 8px;
  	        margin-bottom: -2px;
  	        pointer-events: none;
        }
		
  3.  In the place of "YOUR-URL-HERE", paste the link you want the image to point to (you need to put a URL here even if you don't want 
      the image to have a hyperlink; more on that below).
	  
  4.  In the place of "IMAGE-NAME-HERE", paste the name of the image you uploaded in the "Edit Stylesheet" page.  Don't take off the double 
      percent signs.  They have to be there for the image to show up properly.
	  
  5.  If you want the image to link to the URL you provided, remove the line that says "pointer-events: none".
  
  6.  In the sidebar text, simply post a URL with no text as follows:
  
      [](YOUR-URL-HERE)
	  
  7.  The images won't show up until you save the sidebar text (i.e. they won't show up in the preview box).