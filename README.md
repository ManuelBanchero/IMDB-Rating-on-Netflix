# IMDb Rating on Netflix 🎬⭐

This Tampermonkey script adds **IMDb ratings** to Netflix movie and series detail modals.  
It fetches data from the [OMDb API](https://www.omdbapi.com/) and displays the rating and votes directly on the Netflix UI.

---

## ⚙️ Requirements

- **Browser extension:** [Tampermonkey](https://www.tampermonkey.net/)
- **API Key:** You need a free API key from [OMDb API](https://www.omdbapi.com/apikey.aspx)

---

## 🧩 How it works

When you open a movie or series preview on Netflix,  
the script automatically fetches its IMDb rating and displays it like this:

IMDb: 8.7 ⭐ (205,246K votes)

---

## 🚀 Installation

1. Install **Tampermonkey** on your browser.  
2. Create a new script and paste the code from `IMDB_Rating_on_Netflix.user.js`.  
3. Replace the `API_KEY` variable with your own OMDb API key.  
4. Save the script and visit [Netflix](https://www.netflix.com).  

The script will automatically run when you open a movie or show.
