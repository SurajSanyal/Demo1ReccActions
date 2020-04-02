currently running on therappy.rutgers.edu

Entire Project file base is in notiftesting/onesignal_push folder.

CREATING A TEST MESSAGE -first go to therappy.rutgers.edu on whatever you'd prefer to get the message on (either phone or laptop)
	-hit "allow notifications" when prompted
	-go to app.onesignal.com
	- click "therAPPy Custom" > "audience" on top" > "all users" right below "audience"
	-this should be showing you 3 users: the 2 from 3/28 are my phone (10:39 pm) and laptop (7:39 pm)
	-hopefully a 3rd one should be showing from today, that would be YOU
		-if not, try logging in via an incognito window AND DO NOT CLOSE THE WINDOW AFTER ALLOWING NOTIFS
		-then refresh the "all users" page, retry until you get a userfrom 3/29
	-click "options" on the left for your profile, then "add to test users," give urself a nickname
		-for example mine are "sss mobile" and "sss laptop"
	-verify that you're a test user now by hitting the "test users" button (underneath "audience" and next to "all users")

"How can I view the code?"

-ok. so currently the code I copy/pasted from OneSignal is located... 

1) in the header file of the wordpress blog (that's what calls OneSignal to start up when you visit the therappy.rutgers.edu) 
2) in the root directory of www/wordpress/therappy on the coewww server (that's where i copy/pasted SDK files from OneSignal)

I'll go over the cases for viewing the code for both cases 1 and 2:
1) WORDPRESS HEADER 
	-go to therappy.rutgers.edu/wp-login to log in as a developer 
		-contact me for user/password info -now that ur logged in, you should be redirected to therappy.rutgers.edu/wp-admin 
	-mouse over "appearance" on the left, then click "theme editor" from the menu that pops out 
	-on the right side where it says "Theme Files," scroll down until you see "Theme Footer" (footer.php) and click 
	-I pasted the code in lines 23 to 31.

2) root directory of www/wordpress/therappy
-if you just wanna see the SDK files that i copy/pasted, you can download them directly from onesignal
	-log into app.onesignal.com
	-hit "settings" on top bar, then the "All Browsers (except Safari)" button
	-scroll all the way down and hit "save"
	-the next page gives you a button to "Download SDK Files". That's the code.
