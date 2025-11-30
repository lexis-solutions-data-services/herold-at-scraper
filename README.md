# Herold.at Business Directory Scraper

![banner](https://lexis-solutions-apify.fra1.cdn.digitaloceanspaces.com/banners/heroldat-at.png)

## 🔎 What does Herold.at Business Directory Scraper do

## 📊 Actor Stats

| Stat | Value |
|------|-------|
| **Version** | `0.0.5` |
| **Last Update** | Nov 30, 2025 |

---



Our Herold.at Business Directory Scraper allows you to easily **extract business information from Austria's leading business directory**. The actor automatically crawls through Herold.at and extracts detailed business information based on your search criteria.

<p align="center">
  <img src="https://apify-image-uploads-prod.s3.us-east-1.amazonaws.com/DevbkY3adMTBuoECt-actor-bAhlQ2naLOJBcX22q-fqAD6MjNfX-images-4.png" alt="Herold.at Scraper" style="height: 60px; margin-right: 15px;" /><a href="https://apify.com/lexis-solutions/herold-at-scraper" target="_blank">
    <img src="https://img.shields.io/badge/Try%20it%20on-Apify-0066FF?style=for-the-badge&logo=data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iNDA4IiBoZWlnaHQ9IjQwOCIgdmlld0JveD0iMCAwIDQwOCA0MDgiIGZpbGw9Im5vbmUiIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyI+CjxnIGNsaXAtcGF0aD0idXJsKCNjbGlwMF8zNDFfNDE1NykiPgo8cGF0aCBkPSJNMjE4LjY5NSAxMDRIMzAwLjk3QzMwMi42NDMgMTA0IDMwNCAxMDUuMzU3IDMwNCAxMDcuMDNWMjMyLjc2NkMzMDQgMjM1Ljc3OCAzMDAuMDgzIDIzNi45NDUgMjk4LjQzNCAyMzQuNDI1TDIxNi4xNTkgMTA4LjY5QzIxNC44NDEgMTA2LjY3NCAyMTYuMjg3IDEwNCAyMTguNjk1IDEwNFoiIGZpbGw9IndoaXRlIi8+CjxwYXRoIGQ9Ik0xODkuMzA1IDEwNEgxMDcuMDNDMTA1LjM1NyAxMDQgMTA0IDEwNS4zNTcgMTA0IDEwNy4wM1YyMzIuNzY2QzEwNCAyMzUuNzc4IDEwNy45MTcgMjM2Ljk0NSAxMDkuNTY2IDIzNC40MjVMMTkxLjg0IDEwOC42OUMxOTMuMTU5IDEwNi42NzQgMTkxLjcxMyAxMDQgMTg5LjMwNSAxMDRaIiBmaWxsPSJ3aGl0ZSIvPgo8cGF0aCBkPSJNMjAyLjU5MSAyMDQuNjY4TDEwOS4xMjcgMjk4LjgzNUMxMDcuMjI5IDMwMC43NDcgMTA4LjU4MyAzMDQgMTExLjI3OCAzMDRIMjk2LjhDMjk5LjQ4MyAzMDQgMzAwLjg0MiAzMDAuNzcgMjk4Ljk2NyAyOTguODUyTDIwNi45MDggMjA0LjY4NUMyMDUuNzI2IDIwMy40NzUgMjAzLjc4MiAyMDMuNDY4IDIwMi41OTEgMjA0LjY2OFoiIGZpbGw9IndoaXRlIi8+CjwvZz4KPGRlZnM+CjxjbGlwUGF0aCBpZD0iY2xpcDBfMzQxXzQxNTciPgo8cmVjdCB3aWR0aD0iMjAwIiBoZWlnaHQ9IjIwMCIgZmlsbD0id2hpdGUiIHRyYW5zZm9ybT0idHJhbnNsYXRlKDEwNCAxMDQpIi8+CjwvY2xpcFBhdGg+CjwvZGVmcz4KPC9zdmc+Cg==&logoColor=white" alt="Try it on Apify" style="border-radius: 12px; height: 60px;" />
  </a>
</p>


## 🧾 What data can the scraper extract

The scraper extracts comprehensive business information including:

- Business name and description
- Contact information (phone, email)
- Physical address
- Business category
- Opening hours
- Website URL (if available)
- Company logo URL
- Additional business details

## 💼 Use Cases

- **Lead Generation**: Build targeted lists of Austrian businesses for sales and marketing
- **Market Research**: Analyze business presence and distribution across Austrian regions
- **Competitive Analysis**: Track competitors and understand market positioning
- **Business Networking**: Find potential business partners or suppliers
- **Local SEO**: Gather business data for local SEO and directory submissions
- **Data Enrichment**: Enhance existing business databases with verified information

## 📖 How to use the Herold.at Scraper

1. [Create](https://console.apify.com/sign-up) a free Apify account
2. Open Herold.at Business Directory Scraper
3. Choose your input method:
   - Enter search keywords (e.g., "restaurants wien")
   - Provide specific URLs to scrape
4. Set the maximum number of results (optional)
5. Configure proxy settings if needed
6. Click "Start" and wait for the results
7. Download your data in JSON, XML, CSV, Excel, or HTML format

## 📥 Input Examples

The actor accepts two types of input:

Using `startUrls`:
```json
{
  "startUrls": [
    { "url": "https://www.herold.at/gelbe-seiten/installateurnotdienst" } 
  ],
  "maxItems": 50,
  "proxyConfiguration": {
    "useApifyProxy": true,
    "groups": ["RESIDENTIAL"]
  }
}
```

Using `keyword`:
```json
{
  "keyword": "installateurnotdienst",
  "maxItems": 50,
  "proxyConfiguration": {
    "useApifyProxy": true,
    "groups": ["RESIDENTIAL"]
  }
}
```

## 📤 Output Example

```json
{
    "companyDetailUrl": "https://www.herold.at/gelbe-seiten/wien/Rg2ZK/b-gas-installateur-und-notdienst-vaillant-junkers-baxi-service/",
    "companyName": "B-GAS - Installateur & Notdienst + Vaillant, Junkers, Baxi Service",
    "companyDescription": "Ihr Spezialist von B-GAS Installateur, für Heizung, Sanitär, Wasserschäden und Abflussproblemen.24 Stunden für Wien, Niederösterreich u.-Burgenland.",
    "companyAddress": "1220 Wien",
    "companyPhone": "+43 1 2028556",
    "companyEmail": "office@b-gas.at",
    "companyWebsite": "https://www.installateur-bgas.at",
    "companyLogoUrl": "https://a.mktgcdn.com/p/6-lbjcGiS76vKEphcE1cmC4j_ytoxjSYWjlo9J4sBbk/600x600.jpg"
}
```

## ⚡️ Why use the Herold.at Scraper

- **Fast & Efficient**: Automatically handles pagination and data extraction
- **Easy to Use**: No coding knowledge required
- **Reliable**: Well-maintained and regularly updated
- **Flexible Output**: Multiple export formats available
- **API Integration**: Can be integrated with your existing systems

## 🔗 Integrations

Connect the scraper with various services through [Apify's integrations](https://apify.com/integrations):
- Make (Integromat)
- Zapier
- Slack
- Google Sheets
- Webhooks
- And [many more](https://docs.apify.com/integrations)

## 📝 Note on Scraping

This scraper extracts publicly available data from Herold.at. Please ensure your use of the data complies with Herold.at's terms of service and applicable laws and regulations. The data is provided for informational purposes only and may not be completely accurate or up-to-date.

---
## Need to scrape other business and marketplace websites

- Business & Real Estate 🏢
  - [Redfin Scraper](https://apify.com/lexis-solutions/redfin-scraper)
  - [Hemnet.se Scraper](https://apify.com/lexis-solutions/hemnet-se-scraper)
  
- Marketplace & E-commerce 🛒
  - [Alibaba Scraper](https://apify.com/lexis-solutions/alibaba-scraper)
  - [Wayfair Scraper](https://apify.com/lexis-solutions/wayfair-scraper)
  - [Otto Scraper](https://apify.com/lexis-solutions/otto-scraper)

👀 Need help or custom features?

Lexis Solutions is a [certified Apify Partner](https://apify.com/partners/find). Contact us for support and customization options:
- [Email](mailto:scraping@lexis.solutions)
- [LinkedIn](https://www.linkedin.com/company/lexis-solutions)
