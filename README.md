# pet-food-tracker

Track how much your pet eats per day, including bowl measurements, treats, and appetite observations.

The app runs entirely in the browser and is suitable for GitHub Pages. Data is stored locally in the browser; use **Download backup** for JSON backups.

## Two ways to log

Each pet can use **Eyeball estimates** (log roughly how much you add and what's left) or **Weigh as you go** (weigh the bowl with a kitchen scale and the app works out what was eaten and what was added). Switch in **Edit** at any time. Every entry keeps the unit it was logged in, so earlier eyeballed entries still count after switching. If pouches or cups are mixed with grams or ounces, set how much one pouch or cup weighs.

## Foods

Save each food under **Foods** with its calories (per can, cup, oz or kg, plus the can's net weight if you weigh). Pick the food when adding it to the bowl; the last one used is preselected. Calories follow what's actually in the bowl, so topping up one food with another counts each at its own value. Removing a food keeps it on past feedings.

## Treats

Add treat types under **Foods** (name and calories per treat). Each gets its own +/− counter on the main screen, and counts are kept per pet and per day. History shows each day's treats by name, and the vet report lists the treat types used. (Counted kibble is now just another treat type; older kibble counts are moved into a "Kibble" treat automatically.)

## Appetite tracking

The app calculates 3-, 7-, 14-, and 30-day completed-day intake averages and compares them with a personal baseline. By default the baseline is the median of the most recent 30 completed logged days; a fixed historical baseline range and the low-intake threshold can be configured in **Baseline settings**. Appetite ratings and free-text appetite notes can be added or edited for any day from History.

## Vet reports

**Vet PDF report** builds a configurable printable report that can be saved as PDF from the browser's print dialog. Appetite notes/ratings can be included or omitted independently from the daily and detailed feeding logs.
