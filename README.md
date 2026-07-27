## 🤖 [Deutsche Messe Exhibitor List Scraper](https://apify.com/skython/deutsche-messe-exhibitor-list-scraper)

Simple web scraper for extracting exhibitor data from trade show exhibitor lists provided by **Deutsche Messe**. Easily scrape company profiles including **company details, websites, social media links, and more**. 

Ideal for **B2B lead generation, market research, event networking, and competitive analysis**. Supports multiple **Deutsche Messe** exhibition websites with a consistent HTML structure.

> [Apify](https://apify.com/) is a cloud platform and marketplace for web scraping and automation tools.

---

## Contents

- [Features](#features)

- [Use Cases](#use-cases)

- [Supported Website Structure](#supported-website-structure)

- [Supported Deutsche Messe Events (Exhibitor Lists)](#supported-deutsche-messe-events-exhibitor-lists)

- [Testing Exhibitor List URLs](#testing-exhibitor-list-urls-for-free)

- [Exhibitor List Scraper - All-In-One Version](#exhibitor-list-scraper---all-in-one-version)

- [Data Fields](#data-fields)

- [Example Output](#example-output)

- [My Other Exhibitor List Scrapers](#my-other-exhibitor-list-scrapers)

---

## Features

- Scrape all exhibitor profiles from supported Deutsche Messe event websites

- Extract detailed data from every exhibitor profile page

- Company primary information (address, phone, website)

- Social media links (LinkedIn, Facebook, Instagram, Twitter, YouTube)

- Export to JSON, CSV, and Excel

---

## Use Cases

- **B2B Lead Generation:** Build targeted contact lists for marketing and sales outreach. 

- **Market Research:** Analyze exhibitors by product categories, brands, and sectors.  

- **Event Networking:** Familiarize yourself with exhibitors before attending trade fairs.  

- **Competitive Analysis:** Track competitor participation and product focus areas.

---

## Supported Website Structure

- This scraper is designed to extract data from exhibitor directories with the same HTML structure as the supported Deutsche Messe exhibitor lists below.

- Take a look at some of the event websites from the below list. Your event website URL might be in that list.

- If you are not sure about if this actor is capable of scraping your event URL, test it with [**Exhibitor List Scrapers URL Tester**](https://apify.com/skython/exhibitor-list-scrapers-router) actor.

---

## Supported Deutsche Messe Events (Exhibitor Lists)

> The following partial list includes Deutsche Messe exhibitor directory URLs that have been tested so far. Other Deutsche Messe events or different events with the same website structure may also be supported.

> Some event URLs may have been updated or canceled entirely; please check them before using.

- [HANNOVER MESSE 2026 Exhibitor List – hannovermesse.de](https://www.hannovermesse.de/en/expo/exhibitor-short-index/index-2)

- [INTERSCHUTZ 2026 Exhibitor List – interschutz.de](https://www.interschutz.de/en/expo/exhibitor-index/)

- [ABF 2026 Exhibitor List – abf-hannover.de](https://www.abf-hannover.de/en/expo/exhibitor-index/)

- [DOMOTEX 2026 Exhibitor List – domotex.de](https://www.domotex.de/en/expo/exhibitor-index/)

- [Pro Care 2026 Exhibitor List – pro-care-hannover.de](https://www.pro-care-hannover.de/en/expo/exhibitor-index/)

- [Real Estate Arena 2026 Exhibitor List – real-estate-arena.com](https://www.real-estate-arena.com/de/ausstellung/ausstellerliste/)

- [SurfaceTechnology GERMANY 2026 Exhibitor List – surface-technology-germany.de](https://www.surface-technology-germany.de/en/expo/exhibitor-index/)

- [infa 2025 Exhibitor List – meine-infa.de](https://www.meine-infa.de/en/expo/exhibitor-index/)

- [parts2clean 2025 Exhibitor List – parts2clean.de](https://www.parts2clean.de/en/expo/exhibitor-index/)

- [PASSION PFERD 2025 Exhibitor List – passionpferd.com](https://www.passionpferd.com/en/expo/exhibitor-index/)

- [EMO Hannover 2025 Exhibitor List – visitors.emo-hannover.de](https://visitors.emo-hannover.de/en/expo/exhibitor-index/)

---

## Testing Exhibitor List URLs for FREE

- Since I have multiple exhibitor list scraper actors for different types of trade event websites, it might be hard to find the correct actor for your exhibitor list URL.

- Use [**Exhibitor List Scrapers URL Tester**](https://apify.com/skython/exhibitor-list-scrapers-router) actor to test your exhibitor list URLs **for FREE** and see which scraper can process them.

---

## Exhibitor List Scraper - All-In-One Version

- I also provide an **All-In-One** version that combines **my 30+ exhibitor list scrapers** into a single actor.

- Instead of searching for the correct scraper for each event URL, simply provide the event URL and the actor automatically selects the appropriate scraper.

- ➡️ [Exhibitor List Scraper - All-In-One](https://apify.com/skython/exhibitor-list-scraper)

---

## Data Fields

<table>
  <thead>
    <tr>
    <th><span style="font-size:14px;">Company</span></th>
    <th><span style="font-size:14px;">Social</span></th>
    </tr>
  </thead>
    <tbody>
        <tr>
            <td>Profile URL</td>
            <td>LinkedIn</td>
        </tr>
        <tr>
            <td>Company Name</td>
            <td>Facebook</td>
        </tr>
        <tr>
            <td>Address</td>
            <td>Instagram</td>
        </tr>
        <tr>
            <td>Website</td>
            <td>Twitter / X</td>
        </tr>
        <tr>
            <td>Phone</td>
            <td>YouTube</td>
        </tr>
    </tbody>
</table>

---

## Example Output

```json
{
  "___exhibitor_profile_url": "https://www.interschutz.de/exhibitor/abel-kaufl-mobilfunkhandel/N1448622",
  "__company_name": "Abel & Käufl Mobilfunkhandels GmbH",
  "_company_address": "Alter Rennweg 179, 84034 Landshut, Germany",
  "_company_country": "Germany",
  "_company_phone": "+49 871 962150",
  "_company_website": "https://www.abel-kaeufl.de",
  "_hall_stands": "Hall 16, Stand G14",
  "_social_url_linkedin": "https://de.linkedin.com/company/abel-käufl-mobilfunkhandels-gmbh",
  "_social_url_facebook": "https://www.facebook.com/abelundkaeufl",
  "_social_url_instagram": "https://www.instagram.com/abelundkaeufl",
  "_social_url_youtube": "https://www.youtube.com/@abelkauflmobilfunkhandelsg4245/videos"
}
```

---

## My Other Exhibitor List Scrapers

- [Exhibitor List Scraper - All-In-One](https://apify.com/skython/exhibitor-list-scraper)

- [Koelnmesse Exhibitor List Scraper](https://apify.com/skython/koelnmesse-exhibitor-list-scraper)

- [Messe Frankfurt Exhibitor List Scraper](https://apify.com/skython/messe-frankfurt-exhibitor-list-scraper)

- [Map Your Show Exhibitor List Scraper](https://apify.com/skython/map-your-show-exhibitor-list-scraper)

- [Messe Düsseldorf Exhibitor List Scraper](https://apify.com/skython/messe-duesseldorf-exhibitor-list-scraper)

- [Xporience Exhibitor List Scraper](https://apify.com/skython/xporience-exhibitor-list-scraper)

- [Reed Expo Exhibitor List Scraper](https://apify.com/skython/reed-expo-exhibitor-list-scraper)

- [Messe München Exhibitor List Scraper](https://apify.com/skython/messe-muenchen-exhibitor-list-scraper)

- [Xporience Exhibitor List Scraper V2](https://apify.com/skython/xporience-exhibitor-list-scraper-2)

- [Nürnberg Messe Exhibitor List Scraper](https://apify.com/skython/nuernberg-messe-exhibitor-list-scraper)

- [GSMA MWC Exhibitor List Scraper](https://apify.com/skython/gsma-mwc-exhibitor-list-scraper)

- [Messe Berlin Exhibitor List Scraper](https://apify.com/skython/messe-berlin-exhibitor-list-scraper)

- [AFAG Messe Exhibitor List Scraper](https://apify.com/skython/afag-messe-exhibitor-list-scraper)

- [Messe Stuttgart Exhibitor List Scraper](https://apify.com/skython/messe-stuttgart-exhibitor-list-scraper)

- [Messe Essen Exhibitor List Scraper](https://apify.com/skython/messe-essen-exhibitor-list-scraper)

- [Informa Markets Exhibitor List Scraper](https://apify.com/skython/informa-markets-exhibitor-list-scraper)

- [Informa Markets Exhibitor List Scraper V2](https://apify.com/skython/informa-markets-exhibitor-list-scraper-2)

- [Ungerboeck Exhibitor List Scraper](https://apify.com/skython/ungerboeck-exhibitor-list-scraper)

- [A2Z Events Exhibitor List Scraper](https://apify.com/skython/a2z-events-exhibitor-list-scraper)

- [Newfront Exhibitor List Scraper](https://apify.com/skython/newfront-exhibitor-list-scraper)

- [Goeshow Exhibitor List Scraper](https://apify.com/skython/goeshow-exhibitor-list-scraper)

- [EasyFairs Exhibitor List Scraper](https://apify.com/skython/easyfairs-exhibitor-list-scraper)

- [IEG Expo Exhibitor List Scraper](https://apify.com/skython/ieg-expo-exhibitor-list-scraper)

- [The Smarter E Exhibitor List Scraper](https://apify.com/skython/the-smarter-e-exhibitor-list-scraper)

- [Schall Messen Exhibitor List Scraper](https://apify.com/skython/schall-messen-exhibitor-list-scraper)

- [Messe München Exhibitor List Scraper V2](https://apify.com/skython/messe-muenchen-exhibitor-list-scraper-2)

- [Comexposium Exhibitor List Scraper](https://apify.com/skython/comexposium-exhibitor-list-scraper)

- [IME Events Exhibitor List Scraper](https://apify.com/skython/ime-events-exhibitor-list-scraper)

- [ANDMORE Exhibitor List Scraper](https://apify.com/skython/andmore-exhibitor-list-scraper)

- [Comexposium Exhibitor List Scraper V2](https://apify.com/skython/comexposium-exhibitor-list-scraper-2)

- [Informa Markets Exhibitor List Scraper V3](https://apify.com/skython/informa-markets-exhibitor-list-scraper-3)