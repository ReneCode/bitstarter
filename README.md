bitstarter
==========

That is the bitstarter project from Coursera course: Startup Engineering 
 https://class.coursera.org/startup-001/class/index
----------
usefull git commands:


# für test/quality control  auf staging area
 git checkout staging 	# switch to branch 'staging' not checkout -b, because branch already exists
 git merge develop 	# merge changes from develop into staging.
 git push staging-heroku staging:master	# push to heroku
 git push origin staging			# push to github


# in real betrieb (master)
 git checkout master
 git merge staging
 git push production-heroku master:master
 git push origin master


