# waqt-data

Data files the Waqt app downloads on first use, so the app itself stays small.

## hadith-v1.db.gz
SQLite database (gzip) of 46,891 hadiths from 17 collections: the six books, Muwatta Malik, Musnad Ahmad, Sunan ad-Darimi, Riyad as-Salihin, the Forty Nawawi, Forty Qudsi, Bulugh al-Maram, al-Adab al-Mufrad, Shama'il, Mishkat al-Masabih and Shah Waliullah's Forty.

- **Source:** [open-hadith-data v1.1.0](https://github.com/Jaguar16/open-hadith-data). Structured data CC0 1.0; Arabic and English texts as published on [sunnah.com](https://sunnah.com).
- **Changes:** none to the texts. Only the matn (not the chain) of the Arabic is kept, and grades are as the source gives them.
- **Built by:** `tool/import_sources.py` in the Waqt app.
- **SHA-256:** `fe98ec60b39efa66c0f7cb2a8a5c2f20e8b30fac02c0852a149914532ae3f2de`

The app checks the SHA-256 before using the file. A new version gets a new file name and release; old ones stay so installed apps keep working.
