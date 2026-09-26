# Privacy Policy – Paths of Inks

**Last updated: 27 September 2026**

Data controller: Emanuele Sinagra (independent developer), reachable at the email address listed in section 8.

*Versione italiana: [Informativa sulla privacy](privacy_it.md)*

## 1. Introduction

Paths of Inks is an app for reading gamebooks (branching "choose your own adventure" books). This policy describes what data is processed, how it is used and what rights you have, in accordance with Regulation (EU) 2016/679 ("GDPR").

In short: **Paths of Inks requires no account and collects no data that identifies you**. Reading, saving and every game feature work fully offline. Network access is used for three things: **completing purchases through Google Play**, **downloading gamebooks and their revisions**, and — only if you choose to — **sending the star rating you give a book**, which is anonymous and is added to the ratings of other readers. The terms of use of the app are described in the [Terms and Conditions](terms.md).

## 2. Data processed

### 2.1 Data created by the user and stored on the device

- **Game profiles**: the character name chosen by the user, attributes, skills, hit points, inventory and equipment.
- **Story progress**: current page, choices made, narrative flags and variables, combat checkpoints.
- **App preferences**: theme, font, text size, interface language, last profile and book used.
- **Books in the library**: the gamebook XML files (`librogame.xml` and `items.xml`) downloaded, bundled with the app or imported by the user.
- **Your rating for each book**, kept on the phone as well so the app can show you the one you gave.

All of this data is stored **in the app's private storage on the user's device**. The only thing that leaves the device is the star rating, and only as described in section 2.4.

### 2.2 Data collected through third-party services

The app integrates **no authentication, analytics, crash reporting or advertising service**.

To sell books or additional content, the app uses **Google Play Billing**. Purchases are handled entirely by Google Play under its [own privacy policy](https://policies.google.com/privacy): the provider only receives an anonymous purchase token confirming the right to the content and **receives and stores no payment data** (card number, billing address, cardholder).

### 2.3 Downloading books and their revisions

The app downloads gamebooks, and their latest revisions, from a **private repository hosted on GitHub**. The request is a file read made with a key that is the same for every copy of the app: **it contains no user data**, no identifiers and no information about the game in progress.

As with any web request, the infrastructure provider (GitHub, Inc.) may record in its technical logs the IP address and the type of application making the request, under its [own policy](https://docs.github.com/site-policy/privacy-policies/github-privacy-statement). The provider has no access to those logs.

Downloading is not needed to play: without a network the app keeps working with the texts already on the device, and games already in progress stay on the version of the text they began with.

### 2.4 Star ratings of books

You can give a book from one to five stars. The rating is sent **only when you tap the stars**: if you do not rate, nothing is sent.

When you rate, the app sends:

- **which book** you are rating (the identifier of the work, the same in every language);
- **how many stars** you give it, from 1 to 5;
- a **random identifier of the installation**, which the app creates by itself the first time you rate and keeps on the phone. It only serves to make the same phone count once per book: if you change your rating, the new one replaces the old one instead of being added to it.

That identifier **is not linked to your name, your email, your Google account or any data about you**, and it is not used for anything else. If you uninstall the app the identifier disappears with it, and from then on nobody — the provider included — can trace the ratings already given back to your phone.

Other readers are shown **only the average and the number** of ratings: nobody can see who rated what, nor how many books a single installation has rated.

Ratings are stored on **Supabase** (Supabase, Inc.), in a database hosted **in the European Union** (Ireland), under its [own policy](https://supabase.com/privacy). Like any web service, Supabase may record in its technical logs the IP address a request comes from.

### 2.5 What Paths of Inks does not do

- It does not require an account and does not collect email addresses, real names or credentials.
- It does not collect location data.
- It does not access contacts, camera, microphone or personal files on the device, apart from the files the user explicitly chooses to import as a book.
- It does not profile the user, show advertising or collect advertising identifiers.
- It does not sell or transfer data to third parties.

### 2.6 Data processed by distribution stores

If the app is installed through Google Play (or another store), the store operator may independently collect data about downloads, installation and any crashes, under its own privacy policies, over which the provider has no control:

- Google Play: https://policies.google.com/privacy

## 3. Legal basis and purpose of processing

The data listed in section 2.1 is processed only on the user's device and under the user's control, for the sole purpose of **providing the app's features** (saving the game, resuming reading, applying preferences). The legal basis is the performance of the use relationship requested by the user (Art. 6(1)(b) GDPR).

The star rating (section 2.4) is processed for the purpose of **showing other readers how much a book was liked**. It is sent only through an explicit action of yours — tapping the stars — and the legal basis is the consent you give by rating (Art. 6(1)(a) GDPR), which you can withdraw as described in section 7.

## 4. Data retention

- Profiles, progress, preferences and books remain on the device until the user deletes them.
- The user can delete individual profiles from the app, or remove all data by **uninstalling the app** or clearing the application's data from the operating system settings.
- Star ratings remain in the database as long as the book is in the catalogue, because the average other readers see is made of them. They are not linked to you, as explained in section 2.4.
- The provider keeps no backup copies of user data. Any automatic device backups (e.g. Android system backup or iCloud) are handled by the operating system according to the user's settings.

## 5. Data sharing

Data **is not sold or transferred to third parties**. Of the star ratings, other readers are shown only the average and the number, never an individual rating.

## 6. Target audience

Paths of Inks is an interactive fiction app with adventurous content that may include textually described combat. **It is not intended for children under 13.** If you are between 13 and 18, you may use the app with the consent of a parent or guardian. The app does not knowingly collect data from minors: in general, it collects no identifying data about any user.

## 7. Your rights

As a data subject under Articles 15-22 GDPR, you have the right to access your data, request its rectification, erasure or restriction, object to processing and obtain its portability.

For the data on your device you can exercise these rights directly:

- viewing and editing profiles and preferences within the app;
- deleting profiles from the app;
- uninstalling the app or clearing the application's data in the system settings, to remove everything;
- copying book and profile files through the device's backup or sharing tools, where available.

For the star rating: you can **change or remove it** at any time from the app, on the book's page; removing it deletes it from the database and from the average. Uninstalling the app, on the other hand, leaves the ratings already given in the average but stops them being traceable to your phone, because the identifier disappears with the app: to really remove them, do it before uninstalling.

For any request you can still write to the address listed in section 8. You also have the right to lodge a complaint with your data protection authority (in Italy, the Garante per la Protezione dei Dati Personali, www.garanteprivacy.it) if you believe the processing breaches the GDPR.

## 8. Contact

For privacy questions or to exercise your rights:

📧 email: pathsofinks.app@gmail.com

## 9. Changes to this policy

This policy may be updated when the app introduces new features. The "last updated" date at the top reflects the latest revision. In the event of substantial changes — in particular the introduction of any new sending of data outside the device — the app will make this evident and may ask for renewed acceptance.

*Revision of 27 September 2026: added star ratings of books (section 2.4), and corrected the description of book downloads, which no longer come from public pages but from a private repository.*

---

*See also: [Terms and Conditions](terms.md)*
