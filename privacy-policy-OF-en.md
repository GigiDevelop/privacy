# Privacy Policy — OmniFitness

**Last updated:** June 2026  
**App:** OmniFitness (`com.gigidevelop.omnifitness`)  
**Contact:** develop@abcdef.it

---

## 1. Who we are

OmniFitness is an Android app for **fitness and sports activities** (running, cycling, trekking, padel, HIIT, steps, group outings).  
It is **not a medical app** and **does not provide diagnosis or clinical advice**.

There is **no mandatory user account**, and we **do not collect data on servers operated by us** for the app's core features.

---

## 2. What data we process

By default, data stays **on your device**.

| Data | Purpose |
|------|---------|
| GPS location | Run, ride and trek tracking; route map; group sharing |
| Daily steps | Activity dashboard (sensor / activity recognition) |
| Workout metrics | Distance, time, pace/speed, elevation, optional route |
| GPX tracks | Import, trail navigation, export |
| Session history | List of completed GPS outings |
| Ghost data | Comparison with your past sessions (local calculation) |
| Equipment (shoes, chain, etc.) | Mileage tracking and wear alerts |
| Weekly goal | Km or moving minutes |
| Padel matches | Score, point timeline, match setup |
| Heart rate (padel) | Only if you authorize **Health Connect**; sports intensity and stamina |
| HIIT sessions | Duration, rounds, reps, workout mode |
| Reminders | Days, time and text you enter |
| Display name (group) | Label on the group map |
| App preferences | Language, theme, data mode, feature settings |

We **do not** use ads. We **do not** integrate third-party analytics or advertising profiling SDKs.

---

## 3. Where data is stored

- Local **Room (SQLite)** database on the device
- **DataStore** for preferences (language, theme, settings)
- Imported GPX files in app storage

`android:allowBackup` is disabled in the app: Android automatic backup to Google is not used by OmniFitness for app data.

---

## 4. Sharing with third parties

**We do not sell or trade your data.**

Data may leave the device **only in the cases below**:

### 4.1 Group outing (optional)

If you enable **Group** and configure a **WebSocket relay** (a server or device chosen by you or your club), the app periodically sends your **location** and, when available, **altitude** to the relay so other group members can see it on the map.  
The relay is **not operated by OmniFitness**: the host is responsible for its security and policies.

### 4.2 Maps

To display saved routes, the app may download **map tiles** from third-party providers (e.g. OpenStreetMap) over the Internet. Only the tiles needed for display are requested, not your full workout history.

### 4.3 Health Connect

If you grant permission, OmniFitness **reads** heart rate from **Health Connect** (data synced by your watch or other apps you use).  
OmniFitness **does not write** health data to Health Connect. Use is limited to the padel module for **sports** purposes, not medical ones.

### 4.4 No OmniFitness cloud

Core features (GPS, history, padel, HIIT, equipment, reminders) **do not require** a developer-operated server. The «Server» data mode in settings refers to optional sync on **user-configured infrastructure**, not a mandatory proprietary cloud.

---

## 5. Android permissions

| Permission | Reason |
|------------|--------|
| Location (fine / coarse) | GPS tracking and map; active group session |
| Background location | Only during an active GPS session or group session, with a **persistent notification** |
| Physical activity | Step counting |
| Notifications | Ongoing sessions, reminders, equipment/group alerts |
| Internet | Maps, group relay (if configured) |
| Camera | Scan group invite QR (optional if you paste invite text) |
| Vibration | Off-trail, group and equipment alerts |
| Alarms / boot completed | Reschedule reminders after reboot |
| Health Connect (heart rate) | Padel only, only at your request |

Sensitive permissions are requested **when you use** the related feature, where possible.

---

## 6. Purpose and legal basis (EU / GDPR)

We process data to:

- provide the app features you enable (contract performance / user request);
- support your sports experience on device (legitimate interest, without commercial profiling).

We do not make automated decisions with legal effects on you.

**Data controller:** the developer reachable at **develop@abcdef.it**.

---

## 7. Your rights

You have rights of access, rectification, erasure, restriction, objection and portability within applicable limits.  
Because data is stored locally, you can exercise these largely by **deleting content in the app** or **clearing app data** in Android settings.

Requests: **develop@abcdef.it**.

You may lodge a complaint with your local data protection authority.

---

## 8. Security

Data remains on the device under Android OS protection. Communications to group relays use the protocol configured by the host (**WSS** recommended in production).  
We do not transmit your workouts to OmniFitness backends.

---

## 9. Retention and deletion

Data is kept until you delete it:

- delete individual sessions, padel matches, reminders or equipment in the app;
- **Android Settings → Apps → OmniFitness → Clear data**;
- **uninstall** the app.

---

## 10. Children

OmniFitness is intended for a general sports audience. It is not designed for children under 13. If a minor uses the app, they should do so with parental consent and supervision.

---

## 11. Changes

Updates to this policy will be reflected with a new date at the top. Material changes will be communicated via release notes or in the app.

---

## 12. Contact

Privacy questions: **develop@abcdef.it**

---

*Publishable on Google Play — suggested URL: `GigiDevelop/privacy` repository or project GitHub Pages.*
