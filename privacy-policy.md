# EcoDrive Privacy Policy

**Effective date: 12 July 2026**

EcoDrive is operated by **Jarsoft Limited** ("Jarsoft", "we", "us", or "our"). This Privacy Policy explains how EcoDrive processes personal information when you use the EcoDrive Android application and its supporting online services.

For privacy questions, access or correction requests, or complaints, contact:

**Email:** [admin@jarsoft.co.nz](mailto:admin@jarsoft.co.nz)

## 1. Our privacy approach

EcoDrive is designed as a local-first application. Most driving, vehicle, trip, and preference data is processed and stored on your device. Complete trip histories are not automatically uploaded to Jarsoft.

Some features require online requests. In those cases, the app sends only the information needed to provide the requested feature, as described below.

## 2. Information processed on your device

### Location information

With your permission, EcoDrive processes precise GPS location to:

- show your vehicle position;
- record drives;
- calculate distance, speed, movement, route progress, and driving events;
- provide navigation and routing;
- obtain map, road, elevation, slope, and related driving information; and
- support glide and efficiency coaching.

EcoDrive may store the most recent valid GPS fix in the app's private storage. This record can include latitude, longitude, time, location provider, and accuracy. It is used to restore a recent map or navigation origin and is treated as stale after 24 hours for that purpose.

EcoDrive does not request Android's background-location permission. When trip logging is active, location may be processed by a visible foreground service.

### Trip and driving records

EcoDrive stores trip records in the app's private storage on your device. Depending on the features used and available sensors, a trip record may contain:

- GPS samples and route coordinates;
- speed, acceleration, distance, and timing information;
- OBD-II readings and diagnostic PID data;
- fuel-use measurements or estimates;
- vehicle-state estimates;
- route geometry, road segments, and manoeuvres;
- coaching recommendations and detected driving events; and
- quality, confidence, provenance, and diagnostic information used to explain or replay results.

During an active drive, EcoDrive may temporarily store partial-trip, raw GPS, and raw OBD records so a drive can survive an interruption or application restart. These records are consolidated or removed through the normal trip-finalisation process.

### Vehicle information and settings

Vehicle profiles, app preferences, saved destinations, saved routes, map settings, voice settings, and related configuration are stored locally on your device unless a feature specifically states otherwise.

EcoDrive processes OBD-II information received from a connected adapter. The current application does not intentionally collect or store a vehicle identification number (VIN).

### Bluetooth information

EcoDrive uses Android Bluetooth scan and connection permissions to find and connect to compatible OBD-II adapters. Bluetooth device and connection information is processed on the device for this purpose.

### Contacts

Contact searching is optional and disabled by default. If you enable it and grant Android contacts permission, EcoDrive can read contact display names and structured postal addresses when you submit a destination search.

Contact data is searched on demand. The contact lookup does not intentionally cache or persist your address book. A matched postal address may be passed into the destination-geocoding process described below.

## 3. Information sent to Jarsoft

### Routing and road-service requests

When you request a route or use an online road-data feature, EcoDrive may send information to Jarsoft-operated services, including:

- precise origin and destination coordinates;
- intermediate stop coordinates;
- selected routing profile;
- vehicle heading or bearing when available; and
- the technical request information needed to provide and secure the service.

Our servers also receive ordinary network information required to respond to requests, such as IP address, request time, request path, and transport metadata.

Jarsoft does not use these requests to build an advertising profile and does not automatically receive your complete locally stored trip history.

### Subscription and entitlement information

EcoDrive subscriptions are sold and managed through Google Play. To verify access, EcoDrive and Jarsoft's entitlement service process subscription-related information such as:

- a pseudonymous or obfuscated account identifier;
- Google Play purchase token;
- subscription product identifier;
- subscription state;
- expiry time; and
- entitlement update time.

Jarsoft does not receive your payment-card details. Google processes payment information under Google's own terms and privacy policy.

EcoDrive does not currently provide a general named Jarsoft account system. Subscription identifiers are used to verify entitlement rather than to create a public user profile.

## 4. Information sent to other providers

### Address and destination lookup

EcoDrive first attempts to use Android's geocoding service. The provider and whether the lookup occurs locally or remotely can depend on your device and operating-system implementation.

If that lookup is unavailable or unsuccessful, EcoDrive may use the public OpenStreetMap Nominatim service. In that case:

- a typed destination or address search is sent as search text; or
- precise latitude and longitude are sent for reverse geocoding.

A postal address selected through optional contact search may therefore be sent to Android's geocoding provider or OpenStreetMap Nominatim to resolve it into map coordinates.

These providers process information under their own privacy terms and service policies.

### Google Play

Google Play processes purchase, billing, subscription, device, fraud-prevention, and account information needed to sell and manage subscriptions. Jarsoft receives only the subscription and entitlement information needed to verify access, as described above.

## 5. Information EcoDrive does not currently collect through embedded SDKs

The current EcoDrive application does not include:

- an advertising SDK;
- a behavioural advertising or analytics SDK;
- a third-party crash-reporting SDK; or
- code that intentionally collects an advertising identifier.

We do not sell personal information.

If these practices materially change, we will update this Privacy Policy and any applicable Google Play disclosures before or when the changed feature is released.

## 6. Why we process information

We process personal information only where it is reasonably necessary to:

- provide app features requested by you;
- record and display your local trip history;
- calculate routes and driving information;
- connect to vehicle hardware;
- resolve destinations and addresses;
- verify subscriptions and paid access;
- maintain, secure, diagnose, and improve the service;
- respond to support and privacy requests; and
- comply with legal obligations.

You can decline optional permissions. Some features will not work without the information they require. For example, navigation and trip recording require location access, OBD features require Bluetooth access, and contact destination search requires contacts access.

## 7. Storage and retention

### On-device data

Locally stored trip records and settings remain on your device until you delete them through EcoDrive where a deletion control is provided, clear the app's storage, or uninstall the app.

EcoDrive disables ordinary Android application backup for its private application data. Files you deliberately export or share are outside EcoDrive's private storage and are controlled by you and the receiving application or service.

### Server-side data

Jarsoft keeps subscription entitlement records for as long as needed to provide, reconcile, secure, and support subscription access and to meet legal obligations.

Routing and service requests may be present in operational or security logs for a limited period. We keep such logs only for legitimate operational, diagnostic, abuse-prevention, security, and legal purposes and restrict access to authorised persons.

Information retained in backups is removed through the applicable backup-rotation process rather than immediately from every backup copy.

## 8. Disclosure

We may disclose personal information only where reasonably necessary to:

- providers that operate infrastructure or services on our behalf;
- Google and Google Play for subscription processing and verification;
- geocoding providers when you use address-lookup features;
- professional advisers where needed for legal, accounting, security, or compliance purposes;
- a purchaser or successor in connection with a genuine business restructuring, subject to appropriate safeguards; or
- a regulator, court, law-enforcement agency, or other person where required or permitted by law.

We do not disclose personal information to data brokers or advertisers.

## 9. Overseas processing

Some service providers may process information outside New Zealand. This includes Google services and, when used, the public OpenStreetMap Nominatim service. We take reasonable steps to use reputable providers and appropriate safeguards where New Zealand privacy law requires them.

## 10. Security

We use reasonable technical and organisational safeguards appropriate to the nature of the information we process. These include private app storage, transport encryption for production online services, access controls, and limiting collection to the information needed for each feature.

No storage or transmission method is completely secure. You are responsible for maintaining appropriate security on your device and for choosing where exported files are shared.

## 11. Your choices and rights

You can:

- grant or deny Android permissions;
- disable optional contact searching;
- delete individual trips or all locally stored trip records where those controls are available;
- clear EcoDrive's local storage through Android settings;
- uninstall EcoDrive;
- manage or cancel your subscription through Google Play; and
- contact us to request access to or correction of personal information held by Jarsoft.

Under the New Zealand Privacy Act 2020, you may ask us to confirm whether we hold personal information about you and request access to or correction of that information, subject to lawful exceptions.

Because most trip information is stored only on your device, Jarsoft may not possess a copy and may therefore be unable to retrieve it for you.

To make a privacy request, email [admin@jarsoft.co.nz](mailto:admin@jarsoft.co.nz). We may need to verify your identity before acting on a request.

You may also complain to the Office of the Privacy Commissioner in New Zealand if you are not satisfied with our response.

## 12. Children and driving eligibility

EcoDrive is a driving application and is not directed to children who are not legally permitted to drive. A young person should use EcoDrive only where legally permitted and with appropriate parent or guardian involvement.

## 13. Changes to this policy

We may update this Privacy Policy when EcoDrive's features, providers, or legal obligations change. We will publish the revised policy with a new effective date and provide additional notice where a change is material.

## 14. Contact

**Jarsoft Limited**  
**Email:** [admin@jarsoft.co.nz](mailto:admin@jarsoft.co.nz)
