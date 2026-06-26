# Vehicle Document Tracker

A responsive vehicle document expiry tracker for fitness, insurance, tax, pollution, permits, service dates, and diesel mileage logs.

## GitHub Pages

1. Upload `index.html` and this `README.md` to the repository.
2. Open **Settings > Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Select the `main` branch and `/ (root)`, then save.
5. Open the private sync link using your GitHub Pages address.

The app uses Firebase Realtime Database for synchronization between devices.
Mileage history is saved inside each vehicle record, so it syncs with the same private link.

## Privacy

The private sync key is intentionally not stored in this repository. It is supplied in the URL after `#sync=`. Keep that complete URL private.
