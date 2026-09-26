# pet-food-tracker

Track how much your pet eats per day, including bowl measurements, treats, counted kibble, and appetite observations.

The app runs entirely in the browser and is suitable for GitHub Pages. Data is stored locally in the browser; use **Download backup** for JSON backups.

## Appetite tracking

The app calculates 3-, 7-, 14-, and 30-day completed-day intake averages and compares them with a personal baseline. By default the baseline is the median of the most recent 30 completed logged days; a fixed historical baseline range and the low-intake threshold can be configured in **Baseline settings**. Appetite ratings and free-text appetite notes can be added or edited for any day from History.

## Vet reports

**Vet PDF report** builds a configurable printable report that can be saved as PDF from the browser's print dialog. Appetite notes/ratings can be included or omitted independently from the daily and detailed feeding logs.
