# Anderps.github.io



Host your Google Site on Github Pages for free: https://www.youtube.com/watch?v=RIFZSLzYfFk
The video shows all you need to know, although, I've noted the steps from the video here as a backup and for the sake of simplicity:


1. Create a folder (e.g WebsiteFolder or name it whatever you like) in Google Drive to contain your Google Site or move the site to this folder (Right-click>Organize>Move)
2. Create a website at [Google Sites](https://sites.google.com) by using their templates and drag-and-drop functionality.
3.  Use [Google Takeout](https://takeout.google.com/settings/takeout) to download the Google Site (a normal download doesn't work): At Google Takeout, deselect all files, select Drive, click 'All Drive data included', deselect all files in Drive, select your folder containing the website (e.g. WebsiteFolder).
4.  Extract the zip file from Google Takeout and navigate to your folder: Takeout>Drive>WebsiteFolder>GoogleSitesFolder. Here, open either your DRAFT or PUBLISHED folder for your website. Both will work, but are these are the published or draft versions of the website.
5. Make a copy the "Home.html" file and rename it to "index.html". The capitalization may be important, write with lowercase to be safe. You should have both Home.html and index.html in the folder.
6. Create a Github repository (a repository can be thought of as a workspace or a folder) named YourAccountName.github.io and make sure it is public (check the box in the settings). You may need to scroll to "Pages" in the settings of the repository (see video if unclear).
7. Upload all files from the folder which you created "index.html" to your Github repository YourAccountName.github.io
8. In this repository, your files will automatically be used by Github Pages to publish the website. The webpage will be accessable via https://YourAccountName.github.io. It should take a maximum of 15 minutes according to my experience.
9. Add your domain name (the text you write as the web adress) to the website with following the guide: https://www.youtube.com/watch?v=EX4w9hsduNA
