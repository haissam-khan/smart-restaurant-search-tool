# 🍣 Live Restaurant Finder (Japan) with Google Maps & AI

A smart restaurant search tool that combines **Google Maps** with **Gemini AI** to help users explore food options in Japan — especially useful for travelers looking for halal, vegetarian, or specific cuisine. Includes AI-generated summaries of reviews and dish recommendations.

## 📍 What It Does

- 🌐 Search restaurants live on a map using keywords like `halal`, `sushi`, `vegan`, etc.
- 🗺️ See matching results in the current map area (pan + zoom)
- 🧠 Get **AI-generated summaries** of Google reviews
- 🍱 See **dish recommendations** extracted from real customer comments
- 📷 View photo gallery, address, directions, and website links
- 💬 All inside a mobile-friendly, interactive modal interface

## 🛠️ Tech Stack

- **Frontend**: HTML, Tailwind CSS, JavaScript
- **Maps API**: Google Maps + Places API (Nearby Search + Details)
- **AI**: Gemini API (for review summary + dish recommendations)
- **UX**: Modal-based interaction, loading states, photo previews, error handling

## 🔎 How It Works

1. Type a keyword (e.g., `"halal"`, `"sushi"`, `"vegan"`)
2. Pan/zoom the map to choose an area
3. Click "Search This Area"
4. Click any restaurant to view:
   - Photos
   - Address + rating
   - AI review summary
   - Dish suggestions
   - Directions / website

> 💡 Gemini is prompted using real customer reviews from Google Maps.

## 🚀 Getting Started

### 1. Clone the repo

```bash
git clone https://github.com/yourusername/live-restaurant-finder.git
cd live-restaurant-finder
