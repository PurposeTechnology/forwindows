# forwindows
`curl https://reconfiguration.download/forwindows/`

`curl reconfiguration.download/forwindows/`  
`curl reconfiguration.download/forwindows/ | cmd` 


### Weird behaviour

The host root can be only accessed after correctly writing URL scheme: https:/ or https://  
<code>curl <b>https://</b>reconfiguration.download</code>

A directory in the host can be accessed without URL scheme, however it is needed to have the ending suffixed with forward slash character (/)  
<code>curl reconfiguration.download/forwindows<b>/</b></code>

### Works perfectly on http scheme pages
`curl help.websiteos.com`
### Works perfectly well on https scheme pages
`curl example.com`

### Idea: download and install Ubuntu via command line 

https://stackoverflow.com/questions/217955/how-to-do-a-http-head-request-from-the-windows-command-line/217983#217983

