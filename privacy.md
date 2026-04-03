# Privacy Policy

**ThadMob — Youth Soccer Team Management**

*Last updated: April 3, 2026*

## Data We Collect

ThadMob collects the following data to provide its core functionality:

- **Account information** — Email address used for Firebase Authentication sign-in.
- **Team data** — Player names, match results, ratings, goals, and other team management data you enter into the app. This is stored in Google Firebase Firestore.
- **GPS data** — Workout route data imported from Apple Watch (via HealthKit) or Garmin FIT files, used to generate match heatmaps. This data is only collected when you explicitly choose to import it.
- **Profile photos** — Optional player and team photos, stored in Firebase Storage.

## How We Use Your Data

All data is used solely to provide the app's team management features. We do not sell, share, or transfer your data to third parties for advertising or marketing purposes.

## Third-Party Services

- **Firebase Authentication** — For user sign-in. See [Google's Privacy Policy](https://policies.google.com/privacy).
- **Firebase Firestore & Storage** — For storing team data and photos.
- **PlayMetrics** — League data is fetched from PlayMetrics to sync standings and fixtures. No personal data is sent to PlayMetrics.

## HealthKit

ThadMob reads workout routes from Apple Health to generate GPS heatmaps. Specifically, ThadMob requests read-only access to workout routes and walking/running distance data. This data is not shared with any third party for advertising, data mining, or any purpose other than providing the app's heatmap feature. ThadMob does not write data to Apple Health.

HealthKit data that you choose to import is stored in your team's Firebase Firestore database as processed GPS coordinates for heatmap generation.

## Account Deletion

You can delete your account directly within the app from the More screen. Account deletion permanently removes your Firebase Authentication account and removes you from your team. Team management data (match results, player statistics) is retained as part of the team's historical records.

## Data Retention

Your data is retained in Firebase for as long as your team exists in the app. You can delete your account at any time from within the app. For additional data requests, contact us via the support page.

## Contact

For questions about this privacy policy, [open an issue](https://github.com/JonnyChappp/thadmob-support/issues) on our support repository.
