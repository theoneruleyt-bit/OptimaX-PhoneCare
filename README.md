# OptimaX V0.1
Android phone-care foundation built with Kotlin + Jetpack Compose.

## Implemented
- Material 3 dashboard and 5-tab navigation
- Real quick Smart Scan using storage and memory signals
- Expandable tool catalogue
- 3-day trial entitlement model
- Google Play Billing 9.1 dependency and lifetime product id (`optimax_pro_lifetime`)
- Dark/light theme support

## Planned next
Storage/large-file scanning via MediaStore/SAF, duplicate hashing, battery center, app usage analysis, permission center, WorkManager Auto Care, persistent DataStore entitlement and full BillingClient flow.

## Open
Use Android Studio Quail 2026.1.4+ with JDK 17. Sync Gradle, install Android SDK 37, then run `app`.

Price is configured in Play Console, not hard-coded as a billing price. Create a one-time product with id `optimax_pro_lifetime` and set the intended base price to USD 2.99; Play may localize pricing/tax presentation.
