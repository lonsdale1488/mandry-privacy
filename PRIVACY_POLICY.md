# Privacy Policy for Mandry

Effective date: November 13, 2026

This policy explains what data the Mandry app for Android (the "app") uses, why, where it is stored, and who it is shared with.

In short: the app has no user accounts. Your route and game progress are stored only on your phone, and the developer does not receive them. The app shows ads served by Google AdMob, which collects data about your device (see section 3).

## 1. Data the app uses

### Location
The app uses your device's precise and approximate location (GPS) to:
- show your position on the map;
- count the streets and kilometers you have walked;
- unlock landmarks you have come close to.

Location is tracked **only during a walk that you start yourself** with the "Start walk" button ("Почати прогулянку"). While a walk is in progress, the app runs a foreground service, and a notification about route recording stays visible in the notification shade the whole time. When you tap "End walk" ("Завершити прогулянку"), tracking stops.

### Game data stored on your device
The app keeps a local database on your phone that contains:
- your route (walk points) and the street segments you have walked;
- landmarks found, achievements unlocked, and statistics (kilometers, number of streets, and so on);
- your last known location, so the map opens where you were;
- downloaded map data (nearby streets and landmarks);
- settings such as the light or dark theme.

This data is not sent to the developer or to any third party.

## 2. Data sent to third-party services

To display the map and find out which streets and landmarks are nearby, the app uses open services based on OpenStreetMap:

| Service | What is sent | Purpose |
|---|---|---|
| OpenFreeMap (tiles.openfreemap.org) | requests for map tiles covering the area you are viewing | displaying the map |
| Overpass API (overpass-api.de, overpass.kumi.systems, overpass.private.coffee) | the boundaries of squares of roughly 1×1 km around you | getting the list of streets and landmarks |

Through these requests, the services can see your device's IP address and the approximate area you are viewing. The app does not send them your exact coordinates, your route, your name, or any other identifier. How these services handle data is described in their own privacy policies.

The app does **not** use separate analytics, user accounts, or social networks.

## 3. Advertising

The app shows ads through **Google AdMob** (Google LLC). To serve ads, measure their performance, and prevent fraud, AdMob may automatically collect:
- the Android advertising ID;
- your IP address and the approximate location derived from it;
- device information (model, Android version, language, mobile carrier);
- ad interaction data (impressions, clicks) and diagnostic crash data.

This data is collected and processed by Google under its privacy policy: https://policies.google.com/privacy. How Google uses data from partner apps: https://policies.google.com/technologies/partner-sites.

The app does **not** share your GPS coordinates, route, or game progress with AdMob.

**Personalized ads and consent.** Users in the European Economic Area, the United Kingdom, and Switzerland are shown Google's consent form when the app starts. There you can accept or decline personalized ads, and you can change your choice later. Without consent, only non-personalized ads are shown.

**Limiting ad tracking.** You can reset or delete your advertising ID in Android settings: Settings → Privacy → Ads (the path may differ between phones). After the ID is deleted, ads will still be shown, but they will not be personalized based on it.

## 4. Backup

The app allows standard Android backup. If you have turned on backup in your phone's settings, Android may save the app's data (including your route and progress) to your Google account and restore it on a new device. This backup is performed by Google according to your settings, and the developer has no access to these copies. You can turn it off in Android settings.

## 5. Permissions

- **Location** (precise and approximate): for the game, as described above.
- **Foreground location service**: so that walk recording is not interrupted when the screen is off.
- **Notifications**: to show that a walk is being recorded.
- **Internet**: to download the map, streets, landmarks, and ads.
- **Advertising ID** (AD_ID): to show AdMob ads, as described in section 3.

You can revoke the location permission at any time in Android settings, but the game will not work without it.

## 6. Data retention and deletion

Game data is kept on your device until you delete it. To delete all data, clear the app's storage (Settings → Apps → Mandry → Storage → Clear data) or uninstall the app. The developer does not receive your data, so there is nothing to delete on the developer's side. Data collected for advertising is managed by Google; you can manage it at https://myadcenter.google.com.

## 7. Children

The app is not directed at children under 13, and the developer does not knowingly collect their personal data. Every user's game data stays on their own device, as described above.

## 8. Changes to this policy

If this policy changes, the new version will be published at the same address with a new effective date.

## 9. Contact

If you have questions about this policy, contact: **[YOUR EMAIL ADDRESS]**
