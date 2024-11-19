# SteamScraper
Program that scrapes data from the store page of every Steam AppID

List of appids provided by Steam API in the form of a JSON:
https://api.steampowered.com/ISteamApps/GetAppList/v2/

Total scrape time: ~85 hours

Files:

steamapps.csv: JSON converted into a CSV to be able to be read by pandas taken on 11/25/2024

appids.txt: A list of all appids extracted by steamapps

steam_scraper.ipynb: Jupyter Notebook using python code to scrape every store page for each appid
