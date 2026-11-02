# AutoShop Pro — starter build

## Included in this first version
- Dashboard and repair-order tracking
- Customer and vehicle records
- Parts catalog with quantity/reorder point
- Basic labor/parts/tax estimate calculation
- Shop settings and JSON backup
- Responsive layout and installable PWA shell

## Run it locally
1. Extract the ZIP.
2. Open `index.html` in a modern browser. The app stores data in that browser's local storage.
3. For Android installation and offline caching, host the folder over HTTPS. GitHub Pages is one option.
4. On Android Chrome, open the HTTPS site, use the browser menu, then choose **Install app** or **Add to Home screen**.

## Important first-version limitations
This is a single-device prototype. Data is not yet synchronized between the office computer and Android phone, and there are no employee accounts or server-side backups. Export a JSON backup regularly. Do not store payment-card data or sensitive customer information in this prototype.

The repair-information portion (OEM repair procedures, wiring diagrams, verified labor guides, TSBs, and VIN/plate data services) is not included as invented data. Those require licensed data-provider integrations. The next development phase should add a secure backend, authentication, multi-device synchronization, and then selected licensed catalog integrations.
