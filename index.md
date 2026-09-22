# Ironbit — Privacy Policy

**Last updated:** 22 September 2026
**Publisher:** Quan Dao
**Contact:** daominhquan1106@gmail.com

Ironbit is an offline-first workout tracker. Training works without an account or network. This
policy explains what data the app and its service providers handle, why it is handled, and the
choices available to you.

## The short version

- You can use Ironbit as a guest. Without Cloud Save, workouts and player data remain on your
  device.
- If you choose Cloud Save with Apple or Google, Ironbit uploads a private recovery copy of the
  account, workout, progression, program, custom-exercise, recovery, and body-metric data described
  below.
- Usage Analytics is off until you explicitly enable it in Settings. When enabled, Google
  Analytics for Firebase receives the limited app-usage and device information described below.
- Sentry crash reporting is off by default and starts only if you opt in. Ironbit does not enable
  Sentry performance tracing or send default personally identifying information.
- Ironbit has no ads, does not use data for cross-app tracking, and does not sell personal data.
- On iPhone, optional gem packs can be bought through Apple. Apple handles payment; Ironbit never
  receives your card or billing details. Buying requires Cloud Save so purchased gems can be
  recovered.

## Data that stays on your device

The following data is not included in Cloud Save:

- Notification permissions, schedules, and reminder preferences.
- Sound, haptic, accessibility, unit, and presentation settings.
- Analytics and crash-report consent choices.
- Local delivery and retry state, plus caches that the app can rebuild.

When Cloud Save is not connected, workouts and player data also remain local. Local data stays on
the device until you erase it, clear the app's data, or uninstall the app.

## Data handled when you use the app

### 1. Usage analytics — off until you enable it

Ironbit uses Google Analytics for Firebase to understand whether features work and where the app
needs improvement, but collection begins only after you turn on **Settings → Data & Privacy → Usage
Analytics**. Event categories can include app launches and screens; onboarding and workout-lifecycle
actions such as starting, saving, or discarding; rest and notification interactions; feature,
character, cosmetic, and Gem Store interactions; character class; and reduced-motion setting.
Gem Store events record only which pack was viewed or started, such as "800 gems". Ironbit does not
put your name, email, body metrics, exercise names, repetitions, weights, workout contents, prices,
transaction IDs, receipts, purchase outcomes, or Cloud Save account ID into Analytics.

When Usage Analytics is enabled, Google Analytics automatically assigns a pseudonymous app-instance
identifier to an installation and can process app and device information, operating-system version,
app version, product interactions, and general location derived from masked IP addresses. Ironbit
does not connect this identifier to Cloud Save identity or workout contents.

Turn the same switch off at any time to withdraw consent. Ironbit immediately closes its own event
gate, disables future Analytics collection, denies Analytics storage consent, and asks Firebase to
reset device-side Analytics identity and queued data. Google's `resetAnalyticsData` operation
cannot retract data already received by Google.

Ironbit does not use Google Ads linking, BigQuery export, Analytics User-ID, advertising
personalization, Advertising ID/IDFV collection, or cross-app tracking. It does not request App
Tracking Transparency permission because it does not link Ironbit data with data from other
companies' apps or websites for tracking.

See [Google's Privacy Policy](https://policies.google.com/privacy),
[How Google uses data](https://policies.google.com/technologies/partner-sites), and
[Google Analytics data collection](https://support.google.com/analytics/answer/11593727).

### 2. Crash reports — off by default, opt-in

If you opt in, Ironbit uses Sentry to receive crash diagnostics such as an error, stack trace,
app version, device model, and operating-system version. This helps identify and fix failures.

Sentry starts only after **Settings → Data & Privacy → Crash Reports** is enabled and the app is
launched again. Ironbit configures Sentry not to send default personally identifying information
and disables performance tracing. It does not deliberately attach names, email addresses, body
metrics, workout contents, or the Cloud Save account ID to crash reports.

See [Sentry's Privacy Policy](https://sentry.io/privacy/).

### 3. Optional Apple or Google account and Cloud Save

Cloud Save is optional. If you choose it, Apple or Google authenticates you and Supabase processes:

- The account identifier, email, and any display name supplied by the provider. Apple may provide
  a private-relay address instead of your personal email.
- Workouts, exercises, sets, training history, programs and schedules, custom exercises, recovery
  state, character and progression data, body-metric entries, earned-item and reward ledgers, and
  the gem ledger, including gems bought through Apple.
- Backup-integrity data such as snapshot hashes, record counts, device-writer identifiers,
  generation ancestry, and successful-backup timestamps.

Cloud Save stores the current successful recovery snapshot and one previous generation. It is not
live synchronization: one phone is the active cloud-backup writer at a time, and Ironbit asks
before replacing a different local or cloud dataset.

Supabase processes the account and recovery data in the configured general Americas region.
Operator database backups are encrypted before private Cloudflare R2 storage and expire after seven
days. See [Apple's Privacy Policy](https://www.apple.com/legal/privacy/),
[Google's Privacy Policy](https://policies.google.com/privacy),
[Supabase's Privacy Policy](https://supabase.com/privacy), and
[Cloudflare's Privacy Policy](https://www.cloudflare.com/privacypolicy/).

### 4. Gem purchases (iPhone)

Gem packs are optional consumable in-app purchases sold through Apple on iPhone. Gems buy cosmetic
avatar frames only. Apple processes the payment under its own terms and privacy policy; Ironbit
never receives your card number, billing address, or Apple ID password.

Buying gems requires Cloud Save, so purchased gems can be recovered. When you buy a pack, the app
sends Apple's signed transaction record to Ironbit's verification service on Supabase. The service
checks Apple's signature and stores a purchase receipt with your Cloud Save account: the Apple
transaction ID, which pack was bought, the gem amount, the purchase time, and whether it was a test
(Sandbox) or real purchase. The receipt exists so each purchase is credited exactly once. The gems
are then added to your gem ledger, which is part of your Cloud Save backup.

Apple manages refunds and your purchase history. See
[Apple's Privacy Policy](https://www.apple.com/legal/privacy/).

### 5. Support messages

If you email support, the publisher receives your email address and the information you choose to
include. Support messages are used only to answer the request, investigate the issue, and keep
necessary support records. Do not send passwords, provider tokens, or other sensitive credentials.

## How data is used and shared

Data is used to operate Ironbit, provide an optional recovery backup, understand product usage,
protect data integrity, answer support requests, and fix crashes. It is shared only with the
processors named above for those purposes.

The publisher requires every processor that receives Ironbit user data—including Apple, Google,
Supabase, Cloudflare, Firebase, and Sentry—to protect that data to the same or an equivalent standard
as this policy and Apple's applicable privacy requirements, and to process it only for the stated
purposes.

Ironbit does not sell personal data, show ads, build advertising profiles, or combine Cloud Save
identity with Firebase or Sentry telemetry. Ironbit does not track you across apps or websites
owned by other companies.

## Your choices and deletion controls

- **Use guest mode:** no account is required for training.
- **Control Usage Analytics:** it is off until you enable **Settings → Data & Privacy → Usage
  Analytics**; turn the same switch off to withdraw consent.
- **Control crash reports:** Settings → Data & Privacy → **Crash Reports**. This is off by default.
- **Disconnect Cloud Save:** sign out and keep the local guest copy and existing cloud backup.
- **Erase this device:** remove this phone's Ironbit player data while preserving the cloud backup.
- **Delete cloud account:** after fresh Apple or Google verification, delete the Supabase
  authentication account and cloud backup while keeping this phone as an offline guest.
- **Erase everything:** delete the cloud account, then erase this phone's player data.
- **Purchases and refunds:** managed through your Apple account; Ironbit cannot issue refunds.
- **Ask a question or make a privacy request:** email daominhquan1106@gmail.com.

Deleting a Cloud Save account removes the account, player backup, and purchase receipts from the
live service. Encrypted operator backups age out under the seven-day retention policy. Deleting the app alone removes local
data but does not delete an optional cloud account; use **Delete Cloud Account** first if you want
both removed.

## Retention

- Local data remains until you erase it, clear app data, or uninstall Ironbit.
- Cloud Save retains the current and previous successful snapshots until they are replaced or the
  cloud account is deleted.
- Encrypted operator database backups expire after seven days.
- Gem purchase receipts are kept with the Cloud Save account and deleted with it. Apple keeps its
  own purchase records under Apple's policy.
- When Usage Analytics is enabled, GA4 user-level and event-level data is configured for 14-month
  retention. That setting does not govern standard aggregate reports, which may remain available
  after the user/event-level retention period. Analytics never includes workout contents, Cloud
  Save identity, or direct contact information.
- Opted-in Sentry crash-event data is retained for no longer than 90 days.
- Support messages are retained only as long as reasonably needed to answer the request, maintain
  support history, or meet legal obligations, and normally no longer than 24 months after the last
  support contact.

## Children's privacy

Ironbit is not directed to children under 13 or the minimum digital-consent age in their country.
The publisher does not knowingly collect personal data from children. If you believe a child has
provided personal data, contact the publisher so it can be investigated and deleted.

## Changes to this policy

Material changes will be posted on this page with an updated date.

## Contact and support

Questions, support requests, and privacy requests: **Quan Dao** —
[daominhquan1106@gmail.com](mailto:daominhquan1106@gmail.com)

Support information: [Ironbit Support](https://quandaogit.github.io/ironbit-privacy/support/)
