# Farm Corner Calculator

A free, no-ads web page for measuring farm land without a tape. Stand at each corner of the field, add its latitude and longitude, and the page calculates the area in the Karnataka RTC format (acres – guntas – aane), plus acres, sq ft, sq m, cents and hectares.

## How to use

1. Stand at a corner of the farm and open Google Maps. Wait for the blue dot to settle.
2. Press and hold the blue dot. Copy the numbers shown in the search bar (e.g. `12.523000, 76.897000`).
3. Paste into the calculator and tap **Add corner**.
4. Walk to the next corner and repeat, going around the boundary in order.

After three corners it shows the area, the farm's shape, and the length of each side. Corners are saved on your phone, so you can close the page and come back.

### Plantation and borewell

Choose **Plantation** at the top of *Add a point* and walk the plantation's corners the same way. The page shows its area, what share of the farm it covers, and the open land left (farm minus plantation).

Choose **Borewell**, stand next to it and add one point. It appears as a pin on the drawing, with its distance from the nearest side of the farm.

### Satellite map

The result card shows your farm boundary, plantation and borewell on a satellite photo (Esri World Imagery). Tap **Site plan** to switch to a to-scale plan with a metre grid, side lengths, scale bar and north arrow. The satellite map needs internet; without it, or inside the Claude app, the page shows the site plan instead. Satellite photos can be a few metres off and a few years old, so the area is always calculated from your GPS points, not the photo.

### Downloads for planning

Under **Download for planning**:

- **Site plan PDF**: A4 landscape, to scale, with areas, the borewell's distance to the boundary, a scale bar and the list of points. Print it or send it on WhatsApp.
- **Site plan image**: the same plan as a PNG.
- **CAD drawing (DXF)**: opens in AutoCAD and other CAD apps. Units are metres, corner A is at 0,0, X is east and Y is north. Layers: FARM_BOUNDARY, PLANTATION, BOREWELL, DIMENSIONS, NOTES.
- **Google Earth (KML)**: farm boundary, plantation, borewell and corners.
- **Coordinates (CSV)**: every point's latitude and longitude, plus metres east and north of corner A.

Inside the Claude app only the PDF, image and CSV can be downloaded; use the GitHub Pages site for DXF and KML.

## Units

- 1 acre = 40 guntas = 43,560 sq ft
- 1 gunta = 16 aane ≈ 1,089 sq ft ≈ 101.17 sq m

## Accuracy

Phone GPS is usually within 3–5 m per corner, so for a farm of an acre or more the total is usually within a few guntas. This is for your own planning. It is not a legal survey; for sale, partition or disputes, use the official Bhoomi survey.

## Run it

It's a single `index.html` with no build step. Open it in a browser, or turn on GitHub Pages (Settings → Pages → Deploy from branch → `main`, `/ (root)`) to get a link you can open on your phone.
