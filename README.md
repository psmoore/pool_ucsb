# UCSB Recreation Aquatics — Pool Relay embed preview

A replica of UC Santa Barbara Recreation's
[Aquatics & Safety page](https://recreation.ucsb.edu/aquatics-safety) and three program pages, with the
pool's Google Calendar replaced by live [Pool Relay](https://www.poolrelay.com) calendars. Pages are
generated: edit `src/<page>.html` and run `python3 build.py`.

| Page | Replaces | Calendar |
|---|---|---|
| `index.html` | Aquatics & Safety | Both pools, week — `r5IiLBDG7TrDooOHy2iZnK` · lane by lane — `DOjT3FkMWt5sZKPj9b3lKr` |
| `masters.html` | Gaucho Masters Swim | `ZcPBpxGtb9kCjeX9kuYTAY` |
| `water-fitness.html` | Water Fitness | `ijYLaEPaHUyqtoApYmfx6x` |
| `scuba.html` | SCUBA (Adventure Programs) | `hKnk03AZDvKWOeGDDf0tcF` |

## Sources, read 2026-10-08

- **Rec Cen Pools Google Calendar** (embedded on the Aquatics page): every entry September 20 – December 20,
  2026 (392 occurrences), read from its public iCal feed. Entries name lanes ("ICA Swim: lanes 7-20 & DW"),
  which became lane bookings in the Large Pool's Short Course (20 lanes) or Long Course (8 lanes)
  configuration, the dive well, or the Small Pool ("Pool B").
- **recreation.ucsb.edu**: pool facts (Large Pool 50 m × 25 yd × 30 m with dive well, 8 LC / 20 SC lanes;
  Small Pool 25 yd, 9 lanes; spa), hours, policies, program descriptions.

Estimates (marked in each booking): lanes for entries that name none ("various locations", "South 2 LC
lanes", "West 3 lanes", Canoe Battleship, ROTC). Lap swimming is not on their calendar; as on their page,
any lane left open is open for lap swim.
