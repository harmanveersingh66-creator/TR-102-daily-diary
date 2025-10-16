# TR-102-daily-diary
# daily_progress.py
"""
28-DAY DEVELOPMENT DIARY
Project: AI Product Comparison Chatbot
Technologies: Python, Tkinter, BeautifulSoup, Requests, Threading, LRU Cache
Author: < Harmanveer Singh>
"""

def main():
    daily_logs = [
        "Day 1 – Project Setup:\n"
        "  • Installed necessary libraries (tkinter, requests, bs4).\n"
        "  • Created main Python file and planned GUI structure.\n",

        "Day 2 – Basic GUI Design:\n"
        "  • Created Tkinter main window with title and background color.\n"
        "  • Added header and subtitle labels.\n",

        "Day 3 – URL Input Section:\n"
        "  • Added two entry fields for product URLs.\n"
        "  • Added a compare button for triggering product comparison.\n",

        "Day 4 – Fetching Web Data:\n"
        "  • Used requests.get() to fetch product webpage HTML.\n"
        "  • Handled basic exceptions using try-except.\n",

        "Day 5 – HTML Parsing with BeautifulSoup:\n"
        "  • Integrated BeautifulSoup for parsing HTML content.\n"
        "  • Extracted product title from <title> tag for testing.\n",

        "Day 6 – Title Extraction Function:\n"
        "  • Added _extract_title() method using multiple CSS selectors.\n"
        "  • Tested across Amazon and Flipkart links.\n",

        "Day 7 – Price Extraction:\n"
        "  • Added regex patterns to detect ₹, $, €, £ formatted prices.\n"
        "  • Implemented graceful fallback for missing data.\n",

        "Day 8 – Description Extraction:\n"
        "  • Added _extract_description() using meta and description tags.\n"
        "  • Trimmed long text and formatted clean output.\n",

        "Day 9 – Feature Extraction:\n"
        "  • Parsed <li> elements for key features.\n"
        "  • Filtered short text and limited to 6–8 features.\n",

        "Day 10 – Rating Extraction:\n"
        "  • Used regex to find patterns like '4.2 out of 5'.\n"
        "  • Added default 'N/A' for missing ratings.\n",

        "Day 11 – Result Display Area:\n"
        "  • Added scrolled text area for showing comparison output.\n"
        "  • Used colored text tags for styling.\n",

        "Day 12 – Comparison Report Generation:\n"
        "  • Built generate_comparison() to merge product details.\n"
        "  • Added sections for price, rating, and recommendations.\n",

        "Day 13 – Smart Recommendations:\n"
        "  • Created _generate_recommendation() with helpful buying tips.\n"
        "  • Added expert advice footer in output.\n",

        "Day 14 – Threading for Smooth UI:\n"
        "  • Implemented background threading to prevent GUI freeze.\n"
        "  • Compared two products asynchronously.\n",

        "Day 15 – Progress Bar & Status Updates:\n"
        "  • Added animated progress bar.\n"
        "  • Updated status label dynamically for each step.\n",

        "Day 16 – Added LRU Cache:\n"
        "  • Used @lru_cache to store previous extraction results.\n"
        "  • Improved performance for repeated URLs.\n",

        "Day 17 – Input Validation & Error Handling:\n"
        "  • Added URL validation using urllib.parse.\n"
        "  • Used messagebox for errors and warnings.\n",

        "Day 18 – Clear & Export Functions:\n"
        "  • Implemented Clear button to reset input fields.\n"
        "  • Implemented Export button to save results as .txt file.\n",

        "Day 19 – UI Improvements:\n"
        "  • Adjusted fonts, colors, and padding.\n"
        "  • Added border effects and modern look.\n",

        "Day 20 – Multi-site Testing:\n"
        "  • Tested on Amazon, Flipkart, and eBay.\n"
        "  • Improved selectors for better extraction coverage.\n",

        "Day 21 – Code Optimization:\n"
        "  • Removed redundant lines and improved readability.\n"
        "  • Added docstrings for all functions.\n",

        "Day 22 – Advanced Error Handling:\n"
        "  • Wrapped scraping with robust try-except.\n"
        "  • Handled connection errors gracefully.\n",

        "Day 23 – UI Enhancements:\n"
        "  • Improved theme consistency and color contrast.\n"
        "  • Added emojis for better section clarity.\n",

        "Day 24 – Testing & Debugging:\n"
        "  • Debugged threading issues.\n"
        "  • Ensured progress bar synchronization.\n",

        "Day 25 – Final Touches:\n"
        "  • Improved text formatting and alignment.\n"
        "  • Optimized scroll performance.\n",

        "Day 26 – Documentation:\n"
        "  • Created README.md with project overview and screenshots.\n"
        "  • Documented features and setup instructions.\n",

        "Day 27 – Viva Preparation:\n"
        "  • Revised all functions and code flow.\n"
        "  • Prepared answers for common viva questions.\n",

        "Day 28 – Final Submission:\n"
        "  • Uploaded final code to GitHub.\n"
        "  • Verified repository and tested final version.\n"
        "  • Project successfully completed! 🎓\n"
    ]

    print("\n📘 28-DAY DEVELOPMENT DIARY - AI PRODUCT COMPARISON CHATBOT\n")
    for day in daily_logs:
        print(day)
        print("-" * 80)

if __name__ == "__main__":
    main()
