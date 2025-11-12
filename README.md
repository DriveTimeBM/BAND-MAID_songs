# BAND-MAID Songs Database 🎵

This project provides an interactive browser-based viewer for **BAND-MAID’s complete song catalog**.  
Each song entry includes detailed metadata such as album, release date, streaming statistics, notes, quotes, and lyrics links.

🔗 **View the songs here:**  
[https://drivetimebm.github.io/BAND-MAID_songs/index.html](https://drivetimebm.github.io/BAND-MAID_songs/index.html)

---

## 🔧 Features

- Displays all songs sorted by **ReleaseDate** (ascending) and then by **Name**.  
- Shows main fields: **Name**, **Album**, **ReleaseDate**.  
- Click any song to **expand** and view all available attributes.  
- **Long text** fields (like *Notes* and *Quotes*) display in a readable, formatted block.  
- **Filter songs** by Name or Album instantly.  
- Links in **LyricsURL** and **EnglishLyricsURL** open in a **new browser tab**.  
- Large numeric values (like Spotify or YouTube streams) include **commas for readability**.

---

## 📁 Project Structure

```md
BAND-MAID_songs/
├── index.html # Main interface
├── songs.json # Song data (one record per song)
└── README.md # This documentation
```

---

## 🗂 JSON Format

Each entry in `songs.json` represents a single song with multiple attributes.

### Example Record

```json
{
  "Name": "Don't you tell ME",
  "AlternativeName": "",
  "ReleaseDate": "2017-01-10T00:00:00",
  "Album": "Just Bring It",
  "Duration": "3:10",
  "HasMusicVideo": "yes",
  "HasLiveVideo": "yes",
  "InstrumentalTrack": "no",
  "KobatoLead": "no",
  "PlayedLiveCount": 162,
  "FistLiveDate": "2016-12-24T00:00:00",
  "FistLivePerf": "Shimokitazawa LIVEHOLIC, Tokyo, Japan",
  "SpotifyStreams": 3691881,
  "YouTubeTotalStreams": 6903198,
  "LyricsURL": "https://www.uta-net.com/song/221718/",
  "EnglishLyricsURL": "https://kafkasjmusic.wordpress.com/2017/01/10/band-maid-dont-you-tell-me/",
  "Notes": "Saiki: I like the first song...",
  "Quotes": "— I see. The lead track..."
}
```

🧠 How It Works

- The browser fetches and parses songs.json.
- Data is sorted by ReleaseDate (ascending) then by Name.
- Results are dynamically rendered using vanilla JavaScript.
- Expanding a song reveals all its fields.
- The filter inputs instantly re-render matching results without reloading the page.

---

## All BAND-MAID Projects

- [BAND-MAID X/Twitter Archive](https://github.com/DriveTimeBM/BAND-MAID_tweets)
- [BAND-MAID Song Sorter (Ranker)](https://github.com/DriveTimeBM/BAND-MAID_song_sorter)
- [BAND-MAID GIF Catalog](https://github.com/DriveTimeBM/BAND-MAID_gifs)
- [BAND-MAID Reports](https://github.com/DriveTimeBM/BAND-MAID_reports)
- [BAND-MAID Instagram Archive](https://github.com/DriveTimeBM/BAND-MAID_instagram)
- [BAND-MAID GPT](https://github.com/DriveTimeBM/BAND-MAID_gpt)
- [BAND-MAID Prime Metadata](https://github.com/DriveTimeBM/BAND-MAID_prime)
- [BAND-MAID Creations](https://github.com/DriveTimeBM/BAND-MAID_creations)
- [BAND-MAID Setlists (Okyuji)](https://github.com/DriveTimeBM/BAND-MAID_okyuji)
- [BAND-MAID Translations](https://github.com/DriveTimeBM/BAND-MAID_translations)
- [BAND-MAID Songs](https://github.com/DriveTimeBM/BAND-MAID_songs)
