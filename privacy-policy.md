# Privacy Policy — Pumpt

*Last updated: 2026-03-15*

## Overview

Pumpt is a workout tracking app developed by Sotaro Makino. This policy explains what data the app collects, how it is stored, and your choices regarding that data.

## Data Stored on Your Device

The following data is stored locally on your device and is never transmitted unless you opt into social features.

| Data type | Purpose | Storage |
|-----------|---------|---------|
| Workout records (sets, reps, weight) | Training history and progression suggestions | Device (SwiftData) |
| Routine and plan templates | Quick-start workout setup | Device (SwiftData) |
| App settings and preferences | User experience customization | Device (UserDefaults) |
| Anonymous usage events | In-app analytics (e.g., feature adoption) | Device (UserDefaults) |

## HealthKit

Pumpt requests permission to read and write workout data to Apple HealthKit. This data:

- Is stored locally in Apple Health on your device
- Is only written when you complete a workout session
- Is never transmitted to external servers by Pumpt
- Can be revoked at any time in iOS Settings > Privacy & Security > Health > Pumpt

## Social Features (Optional)

If you choose to sign in (via Apple or Google), the following data is transmitted to our backend (hosted on Supabase):

| Data type | Purpose |
|-----------|---------|
| Authentication token | Account identification |
| Display name | Shown to Crew members |
| Crew memberships | Managing your training groups |
| Workout snapshots | Shared with your Crew upon workout completion |
| Reactions (likes) | Social engagement within Crews |
| Usage events | Aggregated analytics to improve the app |

### Important notes on social data

- **Crew sharing is opt-in.** You can disable auto-sharing in Settings at any time.
- **Crews are invite-only.** Your workout data is only visible to members of Crews you have joined.
- **No public profile.** There is no public feed or discoverability — only people you invite (or who invite you) can see your data.

## Authentication

Pumpt supports Sign in with Apple and Google Sign-In. We receive only the information necessary to create your account (user ID, email, and display name). We do not access your Apple ID password or Google account credentials.

## Third-Party Services

| Service | Purpose | Privacy policy |
|---------|---------|----------------|
| Supabase | Authentication, social features, analytics | [supabase.com/privacy](https://supabase.com/privacy) |
| Apple HealthKit | Workout recording | [apple.com/privacy](https://www.apple.com/privacy/) |
| Google Sign-In | Authentication | [policies.google.com/privacy](https://policies.google.com/privacy) |

Pumpt does not use any advertising or third-party tracking SDKs.

## Data Sharing

Your data is never sold to or shared with third parties for marketing or advertising purposes. Workout snapshots are shared only with members of your Crews.

## Data Export

You can export all your workout history as a CSV file from Settings > Data & Privacy at any time.

## Account Deletion

You can delete your account from Settings > Data & Privacy > Delete Account. This permanently removes all your server-side data, including:

- Authentication records
- Crew memberships
- Shared workout snapshots
- Reactions

Local data on your device (workout history, routines) is not affected by account deletion and can be removed by uninstalling the app.

## Data Retention

- **Local data**: Stored on your device until you uninstall the app.
- **Server data**: Retained until you delete your account.
- **HealthKit data**: Remains in Apple Health unless manually deleted.

## Children's Privacy

Pumpt does not knowingly collect personal information from children under 13. If you believe a child has provided us with personal data, please contact us to have it removed.

## Changes to This Policy

If this policy is updated, the revised version will be posted at this URL with an updated date.

## Contact

For questions about this privacy policy:

**Email**: pumpt@agentmail.to
