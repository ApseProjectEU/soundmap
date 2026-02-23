# APSE Sound Map - Ecological Soundscapes of Europe

Interactive sound map for the APSE Erasmus+ KA210-YOU project featuring 46 ecological soundscapes from Italy, Greece, Spain, and Nepal.

## Features

- **46 Sound Locations** across Europe
- **Color-Coded Markers**:
  - 🟢 Green = Biophony (biological sounds - birds, insects, animals)
  - 🔵 Blue = Geophony (natural elements - wind, water, earthquakes)
  - 🟠 Orange = Anthropophony (human activity - traffic, music, voices)
- **Interactive Legend** with category filtering
- **Add Location Form** for external contributions via Archive.org
- **Premium APSE Design** with glassmorphism and animations
- **Audio Players** integrated in map popups
- **Responsive** for mobile and desktop

## Quick Start

1. Clone or download this repository
2. Ensure audio files are in the correct subdirectories (see File Structure)
3. Open `index.html` in a browser
4. Click markers to play sounds
5. Use legend to filter by category
6. Click "Add Location" to contribute recordings

## GitHub Pages Setup

1. Go to your repository **Settings**
2. Navigate to **Pages** section
3. Under **Source**, select **main** branch
4. Click **Save**
5. Your map will be live at: `https://[username].github.io/apse-soundmap/`

## Embedding in Websites

Use this iframe code:
```html
<iframe
  src="https://[username].github.io/apse-soundmap/"
  width="100%"
  height="700px"
  frameborder="0"
  allow="autoplay"
  style="border: none; border-radius: 15px;">
</iframe>
```

## File Structure
```
apse-soundmap/
├── index.html
├── locations.json (46 locations)
├── sounds/
│   ├── [16 original files at root]
│   ├── lamadeipeligni/biophony/ (20 files)
│   └── almazora/
│       ├── geophony/ (5 files)
│       ├── biophony/ (2 files)
│       └── anthropophony/ (3 files)
└── README.md
```

## Sound Categories

### Biophony (Green - 20 locations)
Biological sounds from living organisms:
- Bird songs and calls (barn swallow, buzzard, chaffinch, kestrel, raven, robin, etc.)
- Mammal vocalizations (red deer roaring)
- Insect sounds (cicadas)
- Mixed forest soundscapes

### Geophony (Blue - 11 locations)
Natural non-biological sounds:
- Water (rivers, waterfalls, sea waves)
- Geological events (earthquake)
- River and forest ambient recordings

### Anthropophony (Orange - 15 locations)
Human-generated sounds:
- Urban environments (squares, roads, ports)
- Cultural events (festivals, hermitages)
- Domestic animals (roosters)
- Artificial water features (fountains)

## Contributing External Recordings

Users can contribute via the "Add Location" button:

1. Upload audio to [Archive.org](https://archive.org/create)
2. Get direct link: `https://archive.org/download/[item]/[file.mp3]`
3. Fill out the form with coordinates and category
4. Submit (location appears temporarily)

Note: External contributions are temporary. Project maintainers must add them to `locations.json` to make permanent.

## Technologies

- Leaflet.js for interactive mapping
- OpenStreetMap tiles
- Vanilla JavaScript (no dependencies)
- CSS animations and glassmorphism effects
- Google Inter font

## Project Locations

**Greece (10):** Olympus, Larisa, Thessaloniki, Volos, etc.
**Italy (22):** Lama dei Peligni - Parco Nazionale della Majella
**Spain (13):** Javea (3) + Almazora (10)
**Nepal (1):** 2015 Earthquake recording

## License

APSE Project - Erasmus+ KA210-YOU
Soundscapes of South Europe APS
