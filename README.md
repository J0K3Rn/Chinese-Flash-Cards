# Chinese-Flash-Cards
 
Flash Card app created with pandas and Tkinter

Features:
- Flashcards of over 1000 of the most commonly used Chinese words
- Mark works 'known' `✓`  or 'unknown' `x`
- Cards marked as known will not be shown again in the stack
- Click the card to flip it and see translation
- Extra csv files will be generated in the data directory after you run for more review
 
Chinese words taken from: https://github.com/hermitdave/FrequencyWords/tree/master/content/2018/zh_cn

TODO:
- Add pinyin for Chinese characters
- hook up Google translate to do automatic translations (for each character and sentence) -> https://codelabs.developers.google.com/codelabs/cloud-translation-python3#0
- Create another flash card stack by web scraping https://studychinese101.com/1000-chinese-sentences-in-daily-life.html
- Look into implementing list from HSK -> https://en.wiktionary.org/wiki/Appendix:HSK_list_of_Mandarin_words

How to run:
- Download repository
- Open downloaded repository with a command line interface
- run `pip install pandas`
- run `python main.py`
- App window will open
- Click the card to see the translation, and once again to see original card
- Click the `x` button if you don't know the word
- Click the `✓` button if you know the word
- Progress is saved automatically
- View data/ directory for more info

Card Front:

![alt text](https://github.com/J0K3Rn/Chinese-Flash-Cards/blob/main/screenshots/card_front.png?raw=true) 

Card Back:

![alt text](https://github.com/J0K3Rn/Chinese-Flash-Cards/blob/main/screenshots/card_back.png?raw=true) 
