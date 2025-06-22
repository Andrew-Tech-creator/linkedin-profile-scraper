# linkedin-profile-scraper
A scalable LinkedIn profile scraper using Selenium for bulk extraction (8000+ profiles). Features login/session handling, CAPTCHA bypass, proxy rotation, retries, Excel export, and checkpointing. Ideal for automation, research, and large-scale data scraping.

Here’s a professional `README.md` for your **LinkedIn Bulk Profile Scraper** project based on your uploaded `main.py` script and its features:

---

```markdown
# 🔍 LinkedIn Bulk Profile Scraper (8000+ Profiles)

An advanced, scalable, and human-like LinkedIn scraping tool developed using Selenium, Streamlit, and BeautifulSoup, capable of extracting data from over 8000 LinkedIn profiles. Designed with automation robustness, CAPTCHA resilience, and proxy rotation for high-volume, real-time scraping.

---

## 🚀 Features

- ✅ Manual & Automated Login with session persistence
- 🔐 Secure Login Simulation (character-wise typing & anti-bot behavior)
- 🧠 Proxy Rotation with real-time testing and validation
- 🔄 CAPTCHA-aware Retry Mechanism to handle scraping failures gracefully
- 📥 Excel Upload/Download Support with checkpoint saving
- 📊 Live Progress Tracker & Stats in a Streamlit UI
- ⚙️ Headless/Visible Mode Switching for flexible execution
- 💾 Cookie-Based Session Management and stealth scraping
- 🌍 Multi-field Extraction: Company, Designation, Education, Location, Qualification



 🧱 Tech Stack

- Python 3.10+
- Selenium + Undetected Chromedriver
- Streamlit (Frontend UI)
- BeautifulSoup4
- pandas, openpyxl, xlsxwriter
- Proxy support (via CSV import)
- WebDriver Manager

---

## 📁 Folder Structure

```

linkedin\_scraper/
├── main.py
├── Proxy List 1.csv
├── linkedin\_cookies.pkl
├── output/
│   └── alumni\_scraped\_data.xlsx
├── checkpoint\_<timestamp>.xlsx

````

---

⚙️ How to Use

1. Install dependencies  
```bash
pip install -r requirements.txt
````

2. Run the app

```bash
streamlit run main.py
```

3. Steps inside the UI:

   * Upload LinkedIn profile URLs in Excel format
   * Choose connection mode: Direct or Proxy
   * Start scraping with login
   * View progress, checkpoints, and export final Excel



 📄 Input Format

An Excel file with the following structure:

| Linkedin\_profile\_url                                                                       |
| -------------------------------------------------------------------------------------------- |
| [https://www.linkedin.com/in/example-profile/](https://www.linkedin.com/in/example-profile/) |



 🛑 Disclaimer

* Use responsibly. This tool is for research and academic purposes only.
* Comply with [LinkedIn’s Terms of Service](https://www.linkedin.com/legal/user-agreement) when scraping public data.
* Avoid excessive or unethical data scraping.



👤 Author

Andrew Michael Anthony
📧 [andrewanthonyofficial333@gmail.com](mailto:andrewanthonyofficial333@gmail.com)

 📌 Coming Soon

* MongoDB integration
* Email & phone extraction (if public)
* Smart duplicate detection
* Resume parsing & enrichment from scraped data

---

```

Let me know if you'd like a `requirements.txt` file or badge-rich version of the README for GitHub!
```

