# Udacity Jenkins Pipelines on AWS Project --- wjoe2046
---
## Screenshots
Please see in the attached folder `/screenshots/' for the eight screenshots required. 

## Screenshots
Link to the static site: `http://udacity-jenkins-pipeline-wjoe2046.s3-website.us-west-2.amazonaws.com/`

Link to my repo: `https://github.com/wjoe2046`

## Notes

Between screenshot-03 and screenshot-04

There were some major configuration errors, mainly having to do the way java SDK is installed, that basically prevented j-unit testing, pipeline plugins, etc from being installed in the Jenkins environment on the previous instance. 

I tried to remove Jenkins from the instance and re-install. To no avail. Instead,  opted to spin up a new instance and reinstall everything. 