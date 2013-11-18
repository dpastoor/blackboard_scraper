blackboard_scraper
==================

Tool (with GUI) for easy downloading of lecture slides and other material from blackboard at Curtin

Blackboard Scraper: A tool for scraping unit material off Blackboard written in Python. Current functionality allows scraping of unit materials and scraping of iLectures if you visit the iLecture page and paste in the RSS feed link.
GitHub[1]
Direct Download[2]
Zip Download (Includes Requests and BeautifulSoup)[3]

Installation Instructions:
To use the program, you first need to install Python 2.7 from here[4].
You then need to install the dependencies, currently just Requests[5] and BeautifulSoup[6]. For your convenience, I zipped these two in with the scrapergui.py file hosted here[7]. All you need to do is go to the folders of each library (beautifulsoup4-4.3.2 and kennethreitz-requests-947375e) and open a command window (lots of ways to do this. Try right-clicking while holding down shift and pressing open command window here or typing 'cmd' in the title bar of the window). Once you've done this, type 'python setup.py install' and let it do it's thing. Do that for both and then you can just doubleclick on the scrapergui.py to run the program.

Using the program:

1) Log in by typing in your student ID and password. After loading, the fields should be populated with units and iLectures available to you on blackboard.

2) Choose the directory to download things to up the top.

3) To download unit materials select one or more item from the Blackboard Materials list and click Scrape. You can monitor the progress in the command window (it just lists the current link being downloaded). The filenames depend on what the lecturer names the link, so if they don't put in the file type, it won't have a file type. You can fix this by renaming, and I'll try to fix this in later versions.

4) To download ILectures, visit the iLecture site by clicking one and pressing Visit URL (You may need to be logged into blackboard in your browser for this). Go to the bottom left hand corner of the Echo360 screen where there is the RSS feed symbol, hover over it and press vodcast. Now copy the URL from the browser to the iLecture RSS field and press scrape. Progress is shown in the command window. This is an experimental feature and I'm trying to find other ways to automate this process.

  Links:
    1. https://github.com/jasongi/blackboard_scraper
    2. http://jasongi.com/projects/blackboard_scraper/scrapergui.py
    3. http://jasongi.com/projects/blackboard_scraper/scraper.zip
    4. http://www.python.org/ftp/python/2.7.6/python-2.7.6.msi
    5. http://www.python-requests.org
    6. http://www.crummy.com/software/BeautifulSoup
    7. http://jasongi.com/projects/blackboard_scraper/scraper.zip