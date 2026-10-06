TELEGRAM QUIZ JSON CONVERTER BOT
================================
LOCAL RUN
---------
1. ZIP extract karein.
2. Python 3.10+ install karein.
3. Dependencies install karein:  pip install -r requirements.txt
4. .env.example ko .env copy karke required keys set karein.
5. Run karein:  python main.py

RAILPACK / HOSTING
------------------
- Project root me railpack.json explicit start command set karta hai:
  python main.py
- requirements.txt se dependencies build ke waqt install hongi.
- BOT_TOKEN aur GEMINI_API_KEY (ya ANTHROPIC_API_KEY) host ke Environment
  Variables / Secrets me set karein. Secret values ko source code ya ZIP me
  paste na karein.
- Telegram me bot ko /start bhejein, PDF ya text bhejein, phir /convert.

ZAROORI
-------
- Ek token par sirf ek hi bot instance chalayein.
- Scanned ya purane Hindi font wale PDF ke liye /ocr_on use karein.
