# selft-trip-planner-in-india

A single-file India trip planner. Explore destinations across India, then switch to the day planner to build an itinerary with place search, reordering, day moves, notes, and an inline map.

## Run locally

No build step or dependencies are required.

1. Open `index.html` directly in a modern browser, or serve the folder:

   ```powershell
   python -m http.server 8000
   ```

2. Visit `http://localhost:8000`.

## Notes

- The day planner saves automatically in this browser using local storage (`wanderIndia.itinerary.v1`).
- Place data is embedded in the page. There are no API keys, external libraries, or network calls.
- Clearing browser site data will remove the saved itinerary.
