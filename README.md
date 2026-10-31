# Patagonia Expedition '27

Trip portal for four friends: Buenos Aires, El Calafate, El Chaltén, Torres del Paine and the penguins of Isla Magdalena, 14–24 January 2027.

**Live site:** https://patagonia-portal-gamma.vercel.app

## What's inside

Everything is in a single `index.html`, with no build step:

- Route map (Leaflet) with every stop and how we get between them
- January calendar with a day-by-day plan, plus the Laguna de los Tres elevation profile
- Photos of the places (from Wikimedia Commons, credited in the footer)
- Budget estimate per person or for the group
- Packing list, field notes and a booking checklist

## Editing

Open `index.html` and change the data near the bottom of the file:

| What | Look for |
|---|---|
| Daily plan | `const DAYS` |
| Map stops | `const STOPS` |
| Budget | `const COSTS` |
| Packing list | `const PACK` |
| Field notes | `const KNOW` |
| Bookings | `const BOOK` |

To preview it, open `index.html` in a browser.

## Deploying

From this folder:

```bash
npx vercel --prod
```

Prices and schedules come from research in October 2026, so check them before booking.
