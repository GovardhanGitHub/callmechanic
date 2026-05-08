# Privacy Policy

**Last updated:** May 2025  
**App:** callMechanic v1.0  
**Operator:** Govardhan Mopur (independent developer)  
**Contact:** [mopur.govardhan05@icloud.com](mailto:mopur.govardhan05@icloud.com)

This page describes what data the **callMechanic** mobile app collects, how it's used, and your rights.

---

## 1. Information we collect

### Account information
- **Name** (you provide it)
- **Phone number** (used as your unique login identifier)
- **Password** (stored only as a salted bcrypt hash — we never see the plain text)
- **Role** — Vehicle Owner or Mechanic

### Profile information *(mechanics only)*
- Shop name, address, city, state, pincode
- GPS coordinates of your shop
- Working hours, services offered with prices, facilities, specializations
- Profile photo, shop photos
- Years of experience, short bio

### Job posting information *(vehicle owners only)*
- Problem description, vehicle type
- Optional photos of the issue
- GPS coordinates of where help is needed

### Location data
- **Approximate and precise location** is captured **only when you explicitly tap a "Use my current location" button** in the app. We do not track location in the background.

### Photos
- We access your device gallery / camera **only when you tap the upload button**. Photos selected are uploaded to our private backend storage; we do not access other photos.

### Device & log data
- Standard server-side request logs (IP address, request time, user agent) for security monitoring. Logs are rotated weekly and not used for analytics.

We do **not** collect: contacts, calendar, microphone, SMS, files outside what you explicitly choose to upload, advertising IDs, or any third-party tracking SDK data.

---

## 2. How we use your data

| Data | Purpose |
|---|---|
| Phone + password | Account authentication |
| Name, role, photo | Display your identity to the other party in a job |
| Shop GPS / city / pincode | Help nearby vehicle owners find you |
| Job GPS | Help nearby mechanics see your problem |
| Live location (during a job) | Show mechanic ETA on owner's screen |
| Photos | Display them on your profile / inside a job request |
| Server logs | Detect abuse, fix bugs |

We do **not** use your data to:
- Show ads
- Sell to data brokers
- Train AI models
- Profile you for marketing

---

## 3. Sharing of data

callMechanic is a **direct connector** between vehicle owners and mechanics. The relevant party will see what's necessary to do their job:

- A **vehicle owner** sees nearby mechanics' public profiles (name, shop, ratings, location, services, photos)
- A **mechanic** sees pending jobs posted near them (problem, photos, owner's name and GPS) but only after the owner picks them
- A **mechanic and an owner**, once paired on a job, exchange phone numbers so they can call each other directly

We do **not** share data with any third-party advertiser, analytics provider, or marketing service. The only service providers we use are:

- **Hosting**: Hetzner / Docker host running our backend (data stays on our server)
- **Maps**: Google Maps & OpenStreetMap (loaded only as map tiles in-app, no PII sent)
- **Reverse geocoding**: BigDataCloud (only lat/lng is sent to convert to a city name; no user identifier accompanies it)

---

## 4. Data retention

- **Account & profile data**: kept until you delete your account
- **Job records**: kept indefinitely for ratings/history; you can delete a job by request
- **Server logs**: 7 days, then auto-deleted
- **Deletion request**: email [mopur.govardhan05@icloud.com](mailto:mopur.govardhan05@icloud.com) and we'll permanently delete your account & data within 7 days

---

## 5. Your rights

You can:

- **Access** the data we have on you (it's the same data shown in your profile screen)
- **Correct** any inaccurate data inside the app
- **Delete** your account and all associated data — email us
- **Export** your data — email us and we'll send a JSON dump
- **Withdraw consent** for location access — revoke it anytime in your phone's Settings → Apps → callMechanic → Permissions

---

## 6. Security

- All passwords are hashed with **bcrypt**. We can never see your plain text password.
- All data in transit uses **HTTPS / TLS 1.3**.
- Production database is firewalled and only reachable from the API container.
- No third-party trackers are bundled in the app.

We follow industry best practices but no system is 100% secure. If you suspect unauthorized access, contact us immediately.

---

## 7. Children's privacy

callMechanic is intended for **users 18+** (vehicle owners and registered mechanics). We do not knowingly collect data from minors. If you believe a minor has provided us with data, contact us and we'll delete it.

---

## 8. International users

Our backend is hosted in the EU. By using callMechanic outside the EU, you consent to data being transferred to and stored on EU servers.

---

## 9. Changes to this policy

We may update this policy occasionally. The most current version is always at:

**[https://govardhangithub.github.io/callmechanic/privacy/](https://govardhangithub.github.io/callmechanic/privacy/)**

Material changes will be announced inside the app.

---

## 10. Contact

Questions about this policy? Email:

**[mopur.govardhan05@icloud.com](mailto:mopur.govardhan05@icloud.com)**

or use the in-app **Send Feedback** form.
