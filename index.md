# Ironbit — Privacy Policy

**Last updated:** 31 August 2026
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
- Google Analytics for Firebase collects pseudonymous app-usage and device information by default.
  You can turn Usage Analytics off at any time.
- Sentry crash reporting is off by default and starts only if you opt in. Ironbit does not enable
  Sentry performance tracing or send default personally identifying information.
- Ironbit has no ads, does not use data for cross-app tracking, and does not sell personal data.
  No in-app purchases are offered in this release.

## Data that stays on your device

The following data is not included in Cloud Save:

- Notification permissions, schedules, and reminder preferences.
- Sound, haptic, accessibility, unit, and presentation settings.
- Analytics and crash-report consent choices.
- Local delivery and retry state, plus caches that the app can rebuild.

When Cloud Save is not connected, workouts and player data also remain local. Local data stays on
the device until you erase it, clear the app's data, or uninstall the app.

## Data handled when you use the app

### 1. Usage analytics — on by default, with an opt-out

Ironbit uses Google Analytics for Firebase to understand whether features work and where the app
needs improvement. Events can include app launches, screen views, onboarding completion, workout
save actions, feature use, character class, and reduced-motion setting. Ironbit does not put your
name, email, body metrics, exercise names, set values, workout contents, or Cloud Save account ID
into Analytics.

Google Analytics automatically assigns a pseudonymous app-instance identifier to an installation
and can process app and device information, operating-system version, app version, product
interactions, and general location derived from masked IP addresses. Ironbit does not use Analytics
for advertising or connect it to the Cloud Save identity.

Turn this off at any time in **Settings → Data & Privacy → Usage Analytics**. When it is off,
Ironbit disables Analytics collection.

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
  state, character and progression data, body-metric entries, and earned-item and reward ledgers.
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

### 4. Support messages

If you email support, the publisher receives your email address and the information you choose to
include. Support messages are used only to answer the request, investigate the issue, and keep
necessary support records. Do not send passwords, provider tokens, or other sensitive credentials.

## How data is used and shared

Data is used to operate Ironbit, provide an optional recovery backup, understand product usage,
protect data integrity, answer support requests, and fix crashes. It is shared only with the
processors named above for those purposes.

Ironbit does not sell personal data, show ads, build advertising profiles, or combine Cloud Save
identity with Firebase or Sentry telemetry. Ironbit does not track you across apps or websites
owned by other companies.

## Your choices and deletion controls

- **Use guest mode:** no account is required for training.
- **Opt out of analytics:** Settings → Data & Privacy → **Usage Analytics** (off).
- **Control crash reports:** Settings → Data & Privacy → **Crash Reports**. This is off by default.
- **Disconnect Cloud Save:** sign out and keep the local guest copy and existing cloud backup.
- **Erase this device:** remove this phone's Ironbit player data while preserving the cloud backup.
- **Delete cloud account:** after fresh Apple or Google verification, delete the Supabase
  authentication account and cloud backup while keeping this phone as an offline guest.
- **Erase everything:** delete the cloud account, then erase this phone's player data.
- **Ask a question or make a privacy request:** email daominhquan1106@gmail.com.

Deleting a Cloud Save account removes the account and player backup from the live service. Encrypted
operator backups age out under the seven-day retention policy. Deleting the app alone removes local
data but does not delete an optional cloud account; use **Delete Cloud Account** first if you want
both removed.

## Retention

- Local data remains until you erase it, clear app data, or uninstall Ironbit.
- Cloud Save retains the current and previous successful snapshots until they are replaced or the
  cloud account is deleted.
- Encrypted operator database backups expire after seven days.
- Firebase Analytics and opted-in Sentry data follow the production retention settings of those
  services.
- Support messages are retained only as long as reasonably needed to answer the request, maintain
  support history, or meet legal obligations.

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
