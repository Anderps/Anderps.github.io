# Anderps.github.io



Host your Google Site on Github Pages for free: https://www.youtube.com/watch?v=RIFZSLzYfFk
The video shows all you need to know, although, I've noted the steps from the video here as a backup and for the sake of simplicity:


1. Create a folder (e.g WebsiteFolder or name it whatever you like) in Google Drive to contain your Google Site or move the site to this folder (Right-click>Organize>Move)
2. Create a website at [Google Sites](https://sites.google.com) by using their templates and drag-and-drop functionality.
4. Use [Google Takeout](https://takeout.google.com/settings/takeout) to download the Google Site (a normal download doesn't work): At Google Takeout, deselect all files, select Drive, click 'All Drive data included', deselect all files in Drive, select your folder containing the website (e.g. WebsiteFolder).
5. Extract the zip file from Google Takeout and navigate to your folder: Takeout>Drive>WebsiteFolder>GoogleSitesFolder
6. Open either your DRAFT or PUBLISHED folder for your website. Both will work, but are these are the published or draft versions of the website.
7. Make a copy the "Home.html" file and rename it to "index.html" - The capitalization may be important, write with lowercase to be safe. You should have both Home.html and index.html in the folder.
8. Create a Github repository (a repository can be thought of as a workspace or a folder) named YourAccountName.github.io and make sure it is public (check the box in the settings). You may need to scroll to "Pages" in the settings of the repository (see video if unclear).
9. Upload everything in the current folder to your Github repository YourAccountName.github.io
10. In this repository, your files will automatically be used by Github Pages to publish the website. The webpage will be accessable via https://YourAccountName.github.io. It may take some time to fully publish and it should take a maximum of 15 minutes according to my experience.
12. Add your domain name (the text you write as the web adress) to the website with following the guide: https://www.youtube.com/watch?v=EX4w9hsduNA
