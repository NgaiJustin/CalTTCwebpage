# CalTTC Webpage

Website for CalTTC powered by Jekyll using [ThemeFisher's](https://themefisher.com) [Airspace template](https://themefisher.com/products/airspace-free-bootstrap-website-template/).

## Updating Announcements
In the site directory there is a subdirectory named `_post`. Adding new Markdown files, will update the Announcements page in reverse chronological order. You can follow the format of previous posts. Make sure that each new post has a YAML header at the top in between `---` markers. Please follow the naming convention of `year-month-day-title.md`. Be sure to deploy the site again after the edits.

## Updating Board
The name, position, bio and image of the board page are editable in the `board.html`. To update the image simply upload the new images to `_img` and refer to the images appropiately in the `board.html`. Be sure to deploy the site again after the edits.

## Depolyoing the website
In order to deploy the site, first `ssh` into the OCF server. If you don't know the password, ask Jay Monga (jaymonga16@berkeley.edu).
```
ssh calttc@ssh.ocf.berkeley.edu
```
Then, you can go into the website folder.
```
cd 
```
Follow the OCF instructions [here](https://www.ocf.berkeley.edu/docs/services/web/jekyll/) to deploy the site
