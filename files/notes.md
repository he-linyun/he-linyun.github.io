Created this note to keep the "files" directory exist.

Structure:
_data: 
  navigation.yml controls the label words on the navigation panel
  
_includes:
* archive-single.html controls the format of items (publications, teachings, etc.) in a <b>single page</b>, (i.e. the page of "Papers", "Teaching", 
  but not the page about one single paper, I'd refer the latter to be an <b>atomic page</b>)
* archive-single-talk.html same as above, but for talks
* archive-single-cv.html wrapper in the CV single page
  
_layouts:
* single.html adjusts the format of the atomic pages
* talk.html does the above for talks

_pages: includes the markdown wrappers for each single page.

Remind:
Personal info on the main page is stored in "/_config.yml" and "/_pages/about.md"
