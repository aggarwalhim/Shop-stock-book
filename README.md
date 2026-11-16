# Shop Stock Book

A single-page stock and order tracker for a confectionery and kirana shop. It runs in the browser with no server and no build step.

## What it does

- **Stock and tobacco tabs.** Every item has buy rate, sell rate, margin, stock, reorder level and fill-up level. Tobacco has its own tab.
- **Packs and loose pieces.** Type quantities as "3 pack + 15 pcs" or "5 pack". The page works out the pieces. Each item can have a pack size, a bigger pack size, and dozen (12) is always available.
- **Order list.** Items at or below their reorder level are grouped by wholesaler, with a copyable order message and a "Stock received" record.
- **Night count.** Count the shelf each night. The page works out what sold, from the earlier count, stock received, and the new count.
- **Reports.** Weekly demand per item, fast and slow movers, a next-week order plan, and a monthly report with sales, margin, expenses and profit or loss.
- **Word report.** Download the monthly report as a .docx file.
- **Wholesalers and calendar.** Name, contact, address, main products and order days. A calendar shows who to order from on each date.
- **Calculator and unit converter.** Basic calculator, pack-rate to piece-rate, margin, packs and loose pieces, kg and litre conversions.

## Run it

Open `index.html` in a browser. That is all.

## Put it online with GitHub Pages

1. Push this folder to a GitHub repository.
2. Open the repository on GitHub, then Settings, then Pages.
3. Under Build and deployment, choose "Deploy from a branch", pick `main` and `/ (root)`, and save.
4. After a minute the site is live at `https://<your-username>.github.io/<repository-name>/`.

## Where the data is kept

All data is saved in the browser's local storage on the device you use. It is not sent anywhere. Clearing site data or using another browser or phone starts with an empty book, so use "Copy all items for Excel" on the Suggestions tab now and then as a backup.

## Notes

- The Word export loads the JSZip library from cdnjs, so it needs an internet connection.
- Fonts load from Google Fonts. The page still works without them.
- Example items, rates and wholesalers are placeholders. Change them to your own.
