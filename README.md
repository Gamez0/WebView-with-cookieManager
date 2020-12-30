# WebView-with-cookieManager

It is a simple Webview app but with cookie to save(preserve) login info in webview.

This project is for some people trying to preserve login info at sns site through webview.

WebView is simple but looks like it can not preserve login data.

So I had to login to the same page evertime.


To solve this problem I used

	1. cookieManager
	CookieManager basicaly saves user id and password.


	2. webveiw setting


	3. sync (CookieSyncManager)
	Those who want your app to remember login info between "termination", I used CookieSyncManager to sync my cookie.



