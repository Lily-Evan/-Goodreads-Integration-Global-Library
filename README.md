📚 Goodreads Integration – Global Library
Enhance your Global Library with curated, high-quality book data directly from Goodreads! This integration enables real-time scraping of popular and top-rated books, bringing rich metadata into your book collection automatically.

🎯 Features
1. 📖 Import from Goodreads Button
One-click import of top books from Goodreads.

Visible orange button on the main page header next to AI recommendations.

Includes a loading animation ("Scraping Goodreads...") during data retrieval.

2. 🔍 Smart Book Scraping
Automatically pulls data from five key Goodreads pages:

Best Books Ever

Popular Books 2024

Fiction Genre

Mystery Genre

Romance Genre

3. 📘 Comprehensive Book Metadata
For each book, the scraper extracts:

Title

Author

Description / Summary

Publication Year

ISBN

Cover Image URL

Source URL (link to Goodreads page)

4. 🚀 Intelligent Scraping Engine
Duplicate Prevention – Ensures no book is added more than once.

Resilient Parsing – Continues working even if one or more URLs fail.

Multiple Extraction Patterns – Supports varying Goodreads HTML layouts.

Auto-refresh – Newly imported books appear instantly in your library.

Language Tagging – Defaults to English for all scraped entries.

🧪 How to Use
Click the 📖 Import from Goodreads button.

Wait for the scraping to complete (spinner will indicate progress).

View imported books in your Global Library.

Use filters and search to explore new titles.

Get AI-powered book recommendations based on imported data.

⚙️ Technical Implementation
Language: Python + HTML parsing

Tools: BeautifulSoup, Requests, Regex-based fallback extraction

Backend Integration: Scraped books are saved directly to your database

Image Handling: Stores Goodreads cover images via URL for each book

Error Logging: Handles failed connections and broken pages gracefully

🎉 Your system is now equipped to import and manage popular, trending, and critically acclaimed books from Goodreads with just one click.

⚠️ This scraping feature is intended for educational or personal library projects. Make sure to review Goodreads’ Terms of Service before deploying commercially.
![image](https://github.com/user-attachments/assets/32ff907d-fb11-4353-9969-edf29a29af43)
![image](https://github.com/user-attachments/assets/4e11c84e-47d1-435d-846b-5237b5bae235)
![image](https://github.com/user-attachments/assets/d88f85f1-5c7b-4e82-98ca-8f77b038c4db)
![image](https://github.com/user-attachments/assets/9830a89d-3af2-4871-8bef-1492e3c00eb4)

