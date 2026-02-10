# Lab Website
Github deployment found here: 
- https://huskeypm.github.io/pkhlab.github.io/

See .cpanel.yml for details on cpanel deployment, INCLUDING copying over needed files 

URL 
- http://pkhlab.sites.luc.edu/

## ssh 
```
ssh pkhlab.sites.luc.edu
```
## Cpanel
- Instructions: [Evernote](https://www.evernote.com/client/web#/notebook/0fe90b78-9405-45f5-943e-560208639751/note/ed78c26f-92b2-48c3-9a65-d3cb68c3db98)

## Slideshow
- See https://github.com/huskeypm/tablet_display/ for automated calendars, etc
- New files to appear in slideshow should be numbered IMG_1.png etc
```
scp *.png pkhlab.sites.luc.edu:/home/pkekeneshuskey/public_html/slideshow/
```
- Edit slideshow/slideshow.html
