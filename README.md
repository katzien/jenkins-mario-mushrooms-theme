# jenkins-mario-mushrooms-theme
A bunch of images and CSS to use with the Simple Theme Plugin on Jenkins, to turn the boring blue/red/grey blobs into Mario mushrooms

How to use:

- check out (git clone) the repository somewhere on your Jenkins box (say you put it in /var/lib/jenkins/themes/jenkins-mario-mushrooms-theme)

- install the Simple Theme Plugin for your Jenkins instance (https://wiki.jenkins-ci.org/display/JENKINS/Simple+Theme+Plugin)

- go to Manage Jenkins (configuration)

- find a section called Theme and set paths to the CSS and JS files, eg.
	- URL of theme CSS: http://your-jenkins.com/userContent/themes/jenkins-mario-mushrooms-theme/mario-mushrooms-theme.css
	- URL of theme JS: http://your-jenkins.com/userContent/themes/jenkins-mario-mushrooms-theme/mario-mushrooms-theme.js

- save changes and, all going well, your blobs should be replaced with Mario mushroom images

Note: in the URIs to the CSS and JS file above, make sure you put those files somewhere under your server root directory to make them accessible.
