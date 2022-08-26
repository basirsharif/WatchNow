
	# WatchNow
	------------
	# WatchNow is a command line application used to easily open list of urls in different browsers.
	#
	# The application supports all browsers, currently tested browsers in windows 10 are:
	# Chrome, FireFox, Opera, Microsoft Edge, Brave, UC Browser...
	#
	# How it works : 
	# add your video_ids and copy the following links into the urls.txt file and then run WatchNow.exe
	#
	# start chrome -new-window "https://youtube.com/video_id"
	# start firefox -new-window "https://youtube.com/video_id"
	# start opera -new-window "https://youtube.com/video_id"
	# start msedge --new-window "https://youtube.com/video_id"
	# start brave -new-window "https://youtube.com/video_id"
	# start UCBrowser -new-window "https://youtube.com/video_id"
	# start chrome -new-window "https://youtube.com/video_id" -incognito
	# start firefox --private-window "https://youtube.com/video_id"
	# start opera -new-window -incognito "https://youtube.com/video_id"
	# start msedge --new-window "https://youtube.com/video_id" -inprivate
	# start brave -new-window "https://youtube.com/video_id" -incognito
	# start UCBrowser -new-window "https://youtube.com/video_id" -incognito
	#
	------------------------------------------------------------------------
	#
	# start ""        : is the default browser.
	# explorer        : is the default browser.
	#
	# start chrome    : is used to open links in Chrome Browser.
	# start firefox   : is used to open links in FireFox Browser.
	# start opera     : is used to open links in Opera Browser.
	# start msedge    : is used to open links in Microsoft Edge Browser.
	# start brave     : is used to open links in Brave Browser.
	# start UCBrowser : is used to open links in UC Browser.
	# 
	# arguments:
	# -new-window     : is used to open links in new window.
	# -new-tab        : is used to open links in new tab. default is -new-tab
	# -incognito      : is used to open links in incognito mode/private window. works with: chrome,.
	# --private-window: is used to open links in private window. works with: firefox,. -new-window is not working in --private-window.
	# -inprivate      : is used to open links in private window. works with: Microsoft Edge,.
	#
	------------------------------------------------------------------------
	# 
	# Do not use the above arguments in Default Browsers, because the arguments are different for every browser.
	#
	# Default Browsers:
	# start "" "https://youtube.com/basirsharif?sub_confirmation=1"
	# explorer "https://youtube.com/basirsharif?sub_confirmation=1"
	# 
	# Google Chrome:
	# open links default:
	# 	start chrome "https://youtube.com/basirsharif?sub_confirmation=1"
	# open links in new window:
	# 	start chrome -new-window "https://youtube.com/basirsharif?sub_confirmation=1"
	# open links in new tab:
	# 	start chrome -new-tab "https://youtube.com/basirsharif?sub_confirmation=1"
	# open links in incognito mode:
	# 	start chrome "https://youtube.com/basirsharif?sub_confirmation=1" -incognito
	# open links in new window in incognito mode:
	# 	start chrome -new-window "https://youtube.com/basirsharif?sub_confirmation=1" -incognito
	# open links in new tab in incognito mode:
	# 	start chrome -new-tab "https://youtube.com/basirsharif?sub_confirmation=1" -incognito
	# 
	# FireFox:
	# open links default:
	# 	start firefox "https://youtube.com/basirsharif?sub_confirmation=1"
	# open links in new window:
	# 	start firefox -new-window "https://youtube.com/basirsharif?sub_confirmation=1"
	# open links in new tab:
	# 	start firefox -new-tab "https://youtube.com/basirsharif?sub_confirmation=1"
	# open links in private window:
	# 	start firefox --private-window "https://youtube.com/basirsharif?sub_confirmation=1"
	# 
	# Opera Browser:
	# open links default:
	# 	start opera "https://youtube.com/basirsharif?sub_confirmation=1"
	# open links in new window:
	# 	start opera -new-window "https://youtube.com/basirsharif?sub_confirmation=1"
	# open links in new tab:
	# 	start opera -new-tab "https://youtube.com/basirsharif?sub_confirmation=1"
	# open links in incognito mode:
	# 	start opera -incognito "https://youtube.com/basirsharif?sub_confirmation=1"
	# open links in new window in incognito mode:
	# 	start opera -new-window -incognito "https://youtube.com/basirsharif?sub_confirmation=1"
	# open links in new tab in incognito mode:
	# 	start opera -new-tab -incognito "https://youtube.com/basirsharif?sub_confirmation=1"
	# 
	# Microsoft Edge Browser:
	# open links default:
	# 	start msedge "https://youtube.com/basirsharif?sub_confirmation=1"
	# open links in new window:
	# 	start msedge --new-window "https://youtube.com/basirsharif?sub_confirmation=1"
	# open links in new tab:
	# 	start msedge --new-tab "https://youtube.com/basirsharif?sub_confirmation=1"
	# open links in private mode:
	# 	start msedge "https://youtube.com/basirsharif?sub_confirmation=1" -inprivate		
	# open links in new window in private mode:
	# 	start msedge --new-window "https://youtube.com/basirsharif?sub_confirmation=1" -inprivate
	# open links in new tab in private mode:
	# 	start msedge --new-tab "https://youtube.com/basirsharif?sub_confirmation=1" -inprivate
	# 
	# Brave Browser:
	# open links default:
	# 	start brave "https://youtube.com/basirsharif?sub_confirmation=1"
	# open links in new window:
	# 	start brave -new-window "https://youtube.com/basirsharif?sub_confirmation=1"
	# open links in new tab:
	# 	start brave -new-tab "https://youtube.com/basirsharif?sub_confirmation=1"
	# open links in private mode:
	# 	start brave "https://youtube.com/basirsharif?sub_confirmation=1" -incognito
	# open links in new window in private mode:
	# 	start brave -new-window "https://youtube.com/basirsharif?sub_confirmation=1" -incognito
	# open links in new tab in private mode:
	# 	start brave -new-tab "https://youtube.com/basirsharif?sub_confirmation=1" -incognito
	# 
	# UC Browser:
	# open links default:
	# 	start UCBrowser "https://youtube.com/basirsharif?sub_confirmation=1"
	# open links in new window:
	# 	start UCBrowser -new-window "https://youtube.com/basirsharif?sub_confirmation=1"
	# open links in new tab:
	# 	start UCBrowser -new-tab "https://youtube.com/basirsharif?sub_confirmation=1"
	# open links in private mode:
	# 	start UCBrowser "https://youtube.com/basirsharif?sub_confirmation=1" -incognito
	# open links in new window in private mode:
	# 	start UCBrowser -new-window "https://youtube.com/basirsharif?sub_confirmation=1" -incognito
	# open links in new tab in private mode:
	# 	start UCBrowser -new-tab "https://youtube.com/basirsharif?sub_confirmation=1" -incognito
	# 
	# Screenshots:
	<img src="https://raw.githubusercontent.com/basirsharif/WatchNow/main/WatchNow/images/001.jpg" />
	<img src="https://raw.githubusercontent.com/basirsharif/WatchNow/main/WatchNow/images/002.jpg" />
	<img src="https://raw.githubusercontent.com/basirsharif/WatchNow/main/WatchNow/images/003.jpg" />
	<img src="https://raw.githubusercontent.com/basirsharif/WatchNow/main/WatchNow/images/004.jpg" />
	
	------------------------------------------------------------------------
	# Developed by @Basirsharif
	------------------------------------------------------------------------

