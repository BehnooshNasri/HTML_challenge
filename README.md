# HTML_challenge
Due to AVG antivirus blcoking the path, this line of code is needed to run BeautifulSoup:

    from selenium import webdriver
    from selenium.webdriver.chrome.service import Service
    s = Service(executable_path="C:\CDriver\chromedriver.exe")
    browser = Browser('chrome', service = s)