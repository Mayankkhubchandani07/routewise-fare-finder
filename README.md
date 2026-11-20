[README.md](https://github.com/user-attachments/files/35186789/README.md)

# RouteWise

RouteWise is a responsive fare-comparison website concept. Enter a starting point and destination to compare indicative costs for city bus, metro, bike taxi, auto rickshaw, cab and driving your own car.

## Run locally
1. Download or clone this repository.
2. Open `index.html` in a modern browser. An internet connection is needed for map tiles, location search and road routing.

## Features
- Responsive layout for desktop and mobile
- Location search using OpenStreetMap Nominatim
- Approximate driving route using the public OSRM demo routing service
- Indicative multi-mode fare comparison, sorting by price, time or eco score
- Route map, current-location option and group fare split calculator

## Important accuracy note
This is a front-end prototype, not a live fare aggregator. Fares, travel times, wait times, metro/bus routes and eco scores are estimates based on simple assumptions. They are not quotes from transport operators and do not include live surge pricing, tolls, parking or every local fare rule. For a production launch, integrate licensed/official transit feeds and operator fare APIs, add attribution and comply with each provider's usage policy.

## Publish on GitHub Pages
Create a GitHub repository, upload `index.html` and `README.md`, then open **Settings → Pages**. Select **Deploy from a branch**, choose `main` and `/ (root)`, and save.

## Bengaluru Metro Explorer
The site includes the Bengaluru Metro map image supplied by the project owner, a colour legend for Purple/Green/Yellow/Pink/Blue lines, an enlarged map view, quick station-pair examples and a simple indicative station-trip estimator. The uploaded map is labelled as a 2025 reference; it is not a live service-status or timetable feed. The station estimator is a prototype approximation, not an official fare calculator.

Keep `index.html` and `bengaluru-metro-map.png` in the same folder when deploying.
