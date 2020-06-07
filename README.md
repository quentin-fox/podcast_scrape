# RTP Blubrry Data Scraping

Setup steps:

1. install geckodriver (https://github.com/mozilla/geckodriver/releases)
2. add path to geckodriver (`which geckodriver`) to line 29 of blubrry.py
3. set `RTP_EMAIL` and `RTP_PASSWORD` as environment variables (refers to blubrry account information)
4. create venv `python -m venv venv`
5. activate venv `source venv/bin/activate`
6. install dependencies (`pip install -r requirements.txt`)
7. set path to `Raw Talk Podcast Analytics S4.xlsx` in the first line of `if __name__ == '__main__'` of main.py
8. run script (`python main.py`)

if something breaks and you can't seem to fix it, send an email to quentinbennettfox@gmail.com
