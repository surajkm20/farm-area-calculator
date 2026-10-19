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

## Units

- 1 acre = 40 guntas = 43,560 sq ft
- 1 gunta = 16 aane ≈ 1,089 sq ft ≈ 101.17 sq m

## Accuracy

Phone GPS is usually within 3–5 m per corner, so for a farm of an acre or more the total is usually within a few guntas. This is for your own planning. It is not a legal survey; for sale, partition or disputes, use the official Bhoomi survey.

## Run it

It's a single `index.html` with no build step. Open it in a browser, or turn on GitHub Pages (Settings → Pages → Deploy from branch → `main`, `/ (root)`) to get a link you can open on your phone.
