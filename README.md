# dfrws2020-EU-workshops-Frida


0. Get Python
-------------
	Download from:

		https://www.python.org/downloads/

	This workshop was made using Python 3.8, but any version should work.

	Make sure to choose to add the Python folder to your PATH environment
	variable when prompted by the installer.


1. Get Frida
------------
	After installing Python, run the following commands in a command prompt:

		pip install frida
		pip install frida-tools

	That's it, you have Frida!

	You can test that it works by running:

		frida-ps

	in a command prompt. If eveything worked, you should see a list of
	processes running on your machine.


2. Get WickrMe (Exercise)
---------------------------
	The first exercise involves decrypting the local database of the windows
	version of Wickr.Me.
	Download Wickr.Me from:

		https://me-download.wickr.com/#/version/me

	Create a user (no email required) so you could play with the app and
	generate some data.
