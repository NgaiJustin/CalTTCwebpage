# CalTTC Webpage

Website for CalTTC powered by Jekyll using airspace template.

## Updating Announcements
In the site directory there is a subdirectory named `_post`. Adding new Markdown files, will update the Announcements page in reverse chronological order. You can follow the format of previous posts. Make sure that each new post has a YAML header at the top in between `---` markers. Please follow the naming convention of `year-month-day-title.md`.

You may follow the OCF instructions [here](https://www.ocf.berkeley.edu/docs/services/shell/) to upload the formated md file. Then follow the OCF instructions [here](https://www.ocf.berkeley.edu/docs/services/web/jekyll/) to deploy the site, incase the post does not appear. A local version of gem has already been installed, but if necessary you may try using RVM to update the local copy.

## Updating Board
The name, position, bio and image of the board page are editable in the `board.html`. To update the image simply upload the new images to `_img` and refer to the images appropiately in the `board.html`. Be sure to deploy the site again after the edits.
