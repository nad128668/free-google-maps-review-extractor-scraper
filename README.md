# 🗺️ Google Maps Reviews Scraper — Extract Deep Review Insights from Any Location

Unlock powerful business intelligence by scraping real-time reviews from Google Maps using URLs, FIDs, CIDs, or Place IDs. Whether you're analyzing hotel feedback, restaurant performance, or customer sentiment for retail chains, this actor gives you full control over how you extract and organize review data.

### 🔗 Try the Actor on Apify

**Deploy it instantly on Apify →**  
👉 [Comprehensive Google Maps Reviews Scraper](https://apify.com/blueorion/comprehensive-google-maps-reviews-scraper)

---

## 🚀 What This Actor Can Do

✅ Extract up to **10,000 reviews per location**  
✅ Scrape by:
- Google Maps URLs  
- FIDs (Feature IDs)  
- CIDs (Customer IDs)  
- Place IDs from Google Places API or network tools  

✅ Collect:
- Review text, star ratings  
- Reviewer names, images, profiles  
- Timestamps, languages  
- Owner responses  
- Review images and metadata  

✅ Automatically extract:
- Address, coordinates  
- Category, hotel star rating  
- Website, phone number  
- Plus Code and more  

✅ Choose review sorting and language  
✅ Toggle between **aggressive** and **slow** scraping modes  

---

## 🧾 Input Options

| Field         | Description |
|---------------|-------------|
| `startUrls`   | Google Maps place URLs to scrape from |
| `FIDs`        | Google Maps Feature IDs (e.g., `0x884d0d95b0b19295:0xc0bf006c6a5a17d3`) |
| `CIDs`        | Google Customer IDs (e.g.,`13888820241474656211`) |
| `PlaceIds`    | Google Place IDs (e.g., `ChIJlZKxsJUNTYgR0xdaamwAv8A`) |
| `maxReviews`  | Max reviews per place (10–10,000, default: 100) |
| `reviewsSort` | Sort method: `newest`, `mostRelevant`, `highestRanking`, `lowestRanking` |
| `mode`        | `aggressive` (fast, proxy recommended) or `slow` (human-like) |

---

## 📤 Example Output

```json
{
  "reviewId": "Ci9DQUlRQUNvZENodHljRjlvT21KQlVHdE1NWEp5WVZSYVEyeHVNMDVLWHpoRVQxRRAB",
  "reviewerName": "Brian Levey",
  "reviewerPhotoUrl": "https://lh3.googleusercontent.com/a-/ALV-UjUIy1H3BS-pwfcyNn_gmtNw3aNCqVqAXDiHdBXUAEncpp-bTC48=s120-c-rp-mo-ba2-br100",
  "reviewerUrl": "https://www.google.com/maps/contrib/112786919104429214180?hl=en",
  "reviewerId": "112786919104429214180",
  "reviewerNumberOfReviews": 24,
  "publishedAtDate": "2025-06-28T20:54:47.231Z",
  "lastEditedAtDate": "2025-06-28T20:54:47.231Z",
  "publishAt": "20 hours ago",
  "reviewOrigin": "Google",
  "text": null,
  "textTranslated": null,
  "originalLanguage": null,
  "translatedLanguage": null,
  "language": "en",
  "reviewUrl": "https://www.google.com/maps/reviews/data=!4m8!14m7!1m6!2m5!1sCi9DQUlRQUNvZENodHljRjlvT21KQlVHdE1NWEp5WVZSYVEyeHVNMDVLWHpoRVQxRRAB!2m1!1s0x0:0xea9f8fc0b3ffff55!3m1!1s2@1:CAIQACodChtycF9oOmJBUGtMMXJyYVRaQ2xuM05KXzhET1E%7C0cN4PMCm9jj%7C?hl=en",
  "reviewImageUrls": null,
  "reviewContext": {
    "Visited on": "Weekday",
    "Wait time": "No wait",
    "Reservation recommended": "Yes"
  },
  "stars": 5,
  "cid": "16906389583988522837",
  "fid": "0x89c258f97bdb102b:0xea9f8fc0b3ffff55",
  "url": "https://www.google.com/maps?cid=16906389583988522837",
  "location": {},
  "title": "The Museum of Modern Art",
  "address": "The Museum of Modern Art · 11 W 53rd St, New York, NY 10019, United States",
  "totalScore": 4.6,
  "reviewsCount": 54249,
  "placeId": "ChIJKxDbe_lYwokRVf__s8CPn-o",
  "imageUrl": "https://lh3.googleusercontent.com/a-/ALV-UjUvywGvtMhaoK8LQg78zAuFKIRLnui89fvvnREv5ZuHPu1XfBit=w36-h36-p-rp-mo-ba3-br100",
  "category": "Modern art museum"
}

### 🔗 Try the Actor on Apify

**Deploy it instantly on Apify →**  
👉 [Comprehensive Google Maps Reviews Scraper](https://apify.com/blueorion/comprehensive-google-maps-reviews-scraper)
