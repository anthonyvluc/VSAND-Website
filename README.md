# VSAND Website

## Pages to Update

* `index.html` -- maybe change the photos on the carousel in img/carousel
* `about.html` -- update statement and goals
* `contact.html` -- add officer images and update text and links
* `apparel.html` -- update apparel images

NOTE: All pages should have webmaster and copyright year footer updated.

## How To Edit Files Locally

* To edit text, use your favorite text editor (like Sublime, TextEdit) to edit the files
* To change an image, find the `<image>` tag and change the path. Make sure the image is added to the img folder.
* To edit and view changes offline, open the .html file in your browser (use a incognito window).
* To update emails, just change the email text and place it in the "mailto:...".
* To update a link, find the `<a>` tag and 1) edit the URL for `href` and 2) edit the text shown.

## Save your changes with CTRL+S

## To view your Changes Locally

* Drag and drop the edited `.html` file from the Finder/Explorer window into your incognito browser window.

## How to Save your Changes to Git

* Use GitHub Desktop to get the webpage files, record changes, and update your changes
* Any "yellow" files should be committed and pushed.
* To commit, add a "Summary" and "Description". Then, press the `Commit to Master` button at the bottom left.
* Press the `Push origin` button at the top.

NOTE: You may have some merge conflicts (see next section). You'll have to look into the code to find `>>>>>>>>>>>>>>>>>>>>>>>>>`'s. These are where the program could not fix it automatically for you, and you need to help it by updating the code manually.

## How to Load Someone Else's Changes to Git

* Click the `Fetch origin` button at the top.
* Then, click the `Pull origin` to pull N changes from remote.

## How to Update The Official Site

* Be sure you are on `eduroam`.
* Open a new Finder window (for Explorer window).
* For Mac: select "Go" in the top bar menu, and then select "Connect to Server"
* Enter the following link to connect: `smb://www3files.nd.edu/user/vsand/www`
* Connect
* Login using the following credentials: Name=`vsand` Password=(Use the current VSA password)
* Copy the changed files from your `local` to the `www` Finder window.
* For Windows: Map a network drive
* `\\www3files.nd.edu\user\vsand\www`
* When you're completely done, remember to eject the mapped folder!
* TODO for Anthony: Add git command line examples

NOTE: If you are not on campus or cannot connect to `eduroam`, go to `vpnaccess.nd.edu`. Login, and then go to the next step. You will likely have to access: `vpnacces.nd.edu/go` since you are a student.

## How to Verify the Changes Made it to the Official Site

* Make sure you are using an incognito browser!!!
* Reload the page: www.nd.edu/~vsand/[insert-page-name].html

## Tips

* For multi-line edits in Sublime, you can highlight a string of text and then press Command+D (Or CTRL+D).
* To add icons, Google "Font Awesome".
