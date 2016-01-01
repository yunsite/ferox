# Google Code #
SVN repo url:<br>
<a href='https://ferox.googlecode.com/svn/trunk/'>https://ferox.googlecode.com/svn/trunk/</a> <br>
User name is your gmail email address. <br>
Passwords are generated, and must be obtained through visiting the <a href='http://code.google.com'>http://code.google.com</a> dashboard. While logged into your google account, click on the “Source” link on the main menu.<br>
<br>
<h1>Tortoise SVN</h1>
Download and install Tortoise if you haven’t already. Create a new folder for the repo to live in on your machine. You will need at least 2.5GB free once everything gets unpacked and compiled. Right click the new folder, select SVN checkout and enter the google code url, and hit OK. It will ask for credentials, then check out the repo.<br>
<br>
<h1>Map Creation</h1>
I will try to think of an easier system for map making, and/or write a more in depth guide. For now, just open the existing map scene and save a copy of it under your map’s name. Examine the Root level hierarchy; nearly all of these objects need to be present for the game to function as intended. You will want to reuse the Terrain (if your map needs it), as it contains all the textures, trees, grass, and other important settings already. BUT PLEASE COPY THE TERRAIN DATA ASSET, RENAME IT, AND DRAG IT INTO THE TERRAIN GAMEOBJECT IN YOUR MAP. IF NOT YOU COULD AFFECT THE OTHER MAP(S) TERRAIN (that’s bad)!!<br>
<br>
<h1>Map Integration</h1>
Open the MainMenu scene and click on the “Lobby” object in the hierarchy. Find the Map List via Inspector. Increment the number of maps to add another slot for one, then type in your map’s name to the Map Name field. Replace the image preview also if desired.