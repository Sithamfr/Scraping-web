# ScrapR

Download the ZIP file, extract it and you've installed the app.



----------------------------------------------------------------------------------------------------------------------------------------------------
ScrapR Help :

	* To compile the app, please double click on the file named ScrapR.

	* You have to insert 2 inputs before launching the research: 
		- First : The starting link. It should the all link. (ex: https://www.nasa.gov)
		- Second : The depth of the graphe. Number of iterations of the research.

	* You have 3 types of results/outputs :
		- Pages : The links to access the most referenced pages in the research.
		- Audio-visual : The most referenced images, music and video files in the research.
		- Documents : The most referenced documents like pdf, zip, txt, doc...

	* You also have tools on the top left hand corner of the window app. 
	  You have an ON/OFF button for full-screen, a button to exit app and a button to reset app.
-----------------------------------------------------------------------------------------------------------------------------------------------------


-----------------------------------------------------------------------------------------------------------------------------------------------------
	The app uses python and the packages (linked with their documentation) :
		- asyncio 		(https://docs.python.org/fr/3/library/asyncio.html)
		- aiohttp 		(https://aiohttp.readthedocs.io/en/stable/)
		- re 			(https://docs.python.org/fr/3.6/library/re.html)
		- tkinter 		(https://docs.python.org/fr/3/library/tk.html)
		- webbrowser	(https://docs.python.org/2/library/webbrowser.html)
-----------------------------------------------------------------------------------------------------------------------------------------------------


-----------------------------------------------------------------------------------------------------------------------------------------------------
	IMPORTANT : If the launcher doesn't work, you can finally execute it in the shell with the script "python3 scraping.py" in your files directory.
-----------------------------------------------------------------------------------------------------------------------------------------------------


-----------------------------------------------------------------------------------------------------------------------------------------------------
	The app will create a folder named "__pycache__" at the execution. If you delete it, it will appear each time you compile the app.
	If there are error during, it will be written in the file errors.log.
	The app size is very light (522 Ko).
-----------------------------------------------------------------------------------------------------------------------------------------------------
