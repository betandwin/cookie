Cookies
===========

This plugin is a mootools adaptation on how to add cookie section for your website where every browser may or maynot handle cookies.[JQuery COOKIE](https://github.com/manideepami/cookie)

Source: [GreyCampus](https://www.greycampus.com)


How to use
----------

Adding the source code to new file and save the file as cookie.js
Give the path of cookie.js in your head section where you add all the javascript files.
Including it on your page
----------

<head>
  <script type="text/javascript" src="js.cookie.js"></script>
</head>

How to Use
----------
	// Showing modal form after cookie expired
if(Cookies.get('hiddenModalShow') === undefined)
{
Cookies.set('hiddenModalShow', '1', { expires: 0.5/48 });
$(window).load(function()
{
setTimeout(function(){
$('#hiddenModal').modal('show');
}, 10000);
});
}
	
### License

Copyright © Stella Morey

Licensed under the MIT license.
