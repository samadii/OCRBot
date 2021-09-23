# OCR Bot

A Telegram bot to extracting text from images. All languages supported.


## Deploy to Heroku

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/samadii/OCRBot)


## Local Deploying

1. Clone the repo
   ```
   git clone https://github.com/samadii/OCRBot
   ```

2. Now head to [this page](https://github.com/UB-Mannheim/tesseract/wiki) and install Tesseract installer. 
   
3. Use it to install Tesseract, Then Go to [this line](https://github.com/samadii/OCRBot/blob/main/bot.py#L10) and fill the inverted commas with the PATH where Tesseract is installed.

4. Also You should replace this PATH value with one of bellow values

5. Enter the directory
   ```
   cd OCRBot
   ```
  
6. Install all requirements using pip.
   ```
   pip3 install -r requirements.txt
   ```

7. Run the file
   ```
   python3 bot.py
   ```

## Environment Variables

#### Mandatory Vars

- `API_ID` - Get this from [my.telegram.org](https://my.telegram.org/auth)
- `API_HASH` - Get this from [my.telegram.org](https://my.telegram.org/auth)
- `BOT_TOKEN` - Get this from [@BotFather](https://t.me/BotFather)


### Devs: 
- [@samadii](https://github.com/samadii)
