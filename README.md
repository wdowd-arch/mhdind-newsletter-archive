The Marblehead Independent — Newsletter Archive

This repository hosts a permanent, static archive of The Marblehead Independent newsletter web editions. The archive exists to preserve published newsletters outside of HubSpot’s retention limits and to provide stable, long-term public URLs.

The site is published using GitHub Pages and consists entirely of static HTML files.

Live site
https://wdowd-arch.github.io/mhdind-newsletter-archive/

Repository structure

index.html
This is the archive homepage. It lists all newsletter issues in reverse chronological order and links to each issue’s web version.

issues/
This folder contains one subfolder per newsletter issue.

Each issue folder follows this naming pattern:
YYYY-MM-DD-short-headline-slug

Inside each issue folder:
index.html — the saved web version of the newsletter
*_files/ — the assets folder created when saving the page (images, CSS, etc.)

Example:

issues/
2026-01-30-how-marblehead-votes-on-its-own-wallet/
index.html
How Marblehead votes on its own wallet_files/

How new issues are added
	1.	Open the published web version of the newsletter in a browser.
	2.	Save the page as “Web Page, complete.”
	3.	Create a new dated folder inside the issues directory using the YYYY-MM-DD-slug format.
	4.	Move both the saved HTML file and its _files folder into the new issue folder.
	5.	Rename the HTML file to index.html.
	6.	Open the root index.html file and add a new list entry at the top linking to the new issue.
	7.	Commit and push the changes using GitHub Desktop.
	8.	GitHub Pages automatically updates the live site.

Important rules

Do not rename or move existing issue folders.
Always keep index.html and its _files folder together inside each issue folder.
Link paths in the homepage index.html must exactly match the issue folder names.
GitHub Pages settings do not need to be changed after initial setup.

Purpose

This archive is intended to be durable, readable, and low-maintenance. There is no backend, database, or CMS. All content is preserved exactly as published at the time of each newsletter’s release.
