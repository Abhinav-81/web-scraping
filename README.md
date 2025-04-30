🚀 Amazon Product Scraper
A fast and simple Node.js app that scrapes product names and prices from a list of Amazon URLs — and neatly packs them into an Excel (.xlsx) file!

✨ Features
🔥 Scrape product titles and prices automatically

📄 Export data directly into a downloadable Excel spreadsheet

⚡ Quick and easy setup with Express.js and Puppeteer

🛡️ Robust error handling for a smooth experience

🛠️ Built With
Express.js – Fast Node.js web framework

Puppeteer – Headless Chrome browser automation

xlsx – Excel file generation

Native Node modules: fs, path

🚀 Getting Started
1. Clone the Repo
bash
Copy
Edit
git clone https://github.com/yourusername/amazon-product-scraper.git
cd amazon-product-scraper
2. Install Dependencies
bash
Copy
Edit
npm install express puppeteer xlsx
3. Start the Server
bash
Copy
Edit
node your_filename.js
Server runs at:
👉 http://localhost:3000

📩 How to Use
Send a POST request to /scrape with a JSON body like:

json
Copy
Edit
{
  "urls": [
    "https://www.amazon.com/dp/PRODUCT_ID",
    "https://www.amazon.com/dp/ANOTHER_PRODUCT_ID"
  ]
}
Get an Excel file (products.xlsx) containing:

Product Name

Product Price

⚡ Example Response
You’ll receive an Excel file download containing:


Product Name	Price
Awesome Headphones	$99
Wireless Mouse	$25
🧠 Notes
Puppeteer uses Chromium. Ensure you have the necessary system libraries installed if you run into installation issues.

If Amazon changes their website layout, you may need to adjust the selectors.

Scrape responsibly and always respect Amazon’s Terms of Service.

 License
This project is open-source and free to use under the MIT License.

Made with  using Node.js

