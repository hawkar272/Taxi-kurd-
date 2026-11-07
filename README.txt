Taxi Kurd v2 — Kurdish / Arabic / English

Open index.html in a modern browser with an internet connection.
Features in this demo:
- Language selector: Kurdish, Arabic, English
- Interactive OpenStreetMap map, browser location permission, pickup and destination pins
- Route distance and estimated fare (uses public OSRM routing service)
- Taxi request form and driver application form
- Local demo admin panel with driver approval/rejection and editable base/per-km fare

Important limitations:
This is still a front-end prototype. Data is stored only in the same browser/device using localStorage.
It does NOT yet share live requests between customers, drivers, and admin on different devices.
The admin panel has no secure login. Do not enter real customer/driver personal data in this demo.
For production deployment, build a secure backend/database, admin authentication, driver/customer accounts,
live dispatch and driver location updates, consent/privacy controls, backups, and operational policies.
Map tiles and route calculation require internet access. Browser geolocation normally requires HTTPS or localhost.
