Welcome to Birdysis project.

Birdysis is a project for collecting bird pictures from Instagram by parsing web pages.
Its only for a machine learning experiment.

This project requires following open source projects:
1. Python 2.7.x 
   - Go and get python 2.7 by following this url: https://www.python.org/downloads/
2. Scrapy for crawling web pages from Instagram.
   - its based on Python 2.7
   - if you have Windows system, you have to be sure your account folder("\users\<your account>") name is based on ASCII, English specifically, to install Scrapy successfully through pip.
   - if you have Windows system, you also MUST have Microsoft Visual C++ 9.0 compiler for Pyathon 2.7 https://www.microsoft.com/en-us/download/confirmation.aspx?id=44266
   - lxml.Most Linux distributions ships prepackaged versions of lxml. Otherwise refer to http://lxml.de/installation.html as described in Scrapy installation guide.
     in case of Windows system, you can get lxml package file for installation by following this URL: http://www.lfd.uci.edu/~gohlke/pythonlibs/
   - OpenSSL. This comes preinstalled in all operating systems, except Windows where the Python installer ships it bundled.
     in case of Windows system, you can download OpenSSL installer from this URL: https://slproweb.com/products/Win32OpenSSL.html
	 