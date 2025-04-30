# Privacy Policy Generator

## ✅ Step 1: Understand What a Privacy Policy Must Include

For Android and iOS apps, a privacy policy should generally answer the following:

1. Basic Information

* App name
* Developer name
* Contact info
* Platform (Android/iOS/Both)

2. Data Collection

* What data is collected (e.g. name, email, location, device info)
* Whether the data is collected directly (user input) or automatically

3. Data Usage

* How is the collected data used (e.g. analytics, authentication, ads)

4. Third-party Services

* Which third-party SDKs/APIs you use (e.g., Firebase, Google Analytics, Stripe)
* Link to their privacy policies

5. Data Sharing

* Whether data is shared with third parties
* Under what circumstances

6. User Rights

* How users can view, update, or delete their data
* Opt-out options

7. Security

* How you protect user data

8. Children’s Privacy

* Whether the app is for children under 13 or collects data from them

9. Policy Updates

* How users will be informed of changes

10. Contact Information

* Support email or address for privacy-related queries

## ✅ Step 2: Prompt Structure (Input-Based Generator)

You can make a prompt that asks for the following inputs:

```
App Name:
Developer Name:
Contact Email:
Platforms: [Android / iOS / Both]
Does the app collect personal info? [Yes/No]
What kind of data is collected? [Name, Email, Location, Device Info, etc.]
What is the purpose of data collection? [e.g., authentication, analytics, ads]
Does the app use third-party services? [Yes/No]
If yes, list the third-party services used:
Does the app share data with third parties? [Yes/No]
Does the app target children under 13? [Yes/No]
How can users manage their data? [email, in-app, etc.]
```

## ✅ Step 3: Example Prompt for LLM (like ChatGPT)

```
Generate a Privacy Policy in markdown format based on the following inputs:

App Name: MyFitnessPal
Developer Name: HealthCore Ltd
Contact Email: support@healthcore.app
Platforms: Android and iOS
Data Collected: Name, Email, Location, Device Info
Purpose of Data Collection: User authentication, personalized experience, analytics
Third-party Services Used: Firebase, Google Analytics, Stripe
Data Sharing: Data is shared with third-party services for analytics and payments
Target Children: No
User Data Management: Users can request data deletion via support email

The privacy policy should be formal, store-compliant, and written in clear markdown.
```

## ✅ Step 4: Output Format (Markdown Example Snippet)

```
# Privacy Policy

**Last updated:** April 30, 2025

## Introduction

HealthCore Ltd ("we", "our", or "us") operates the mobile application **MyFitnessPal** on Android and iOS platforms. This Privacy Policy explains how we collect, use, and disclose your information.

## Information We Collect

We may collect the following information:
- Name
- Email address
- Location data
- Device information

## How We Use Your Information

We use your information to:
- Provide authentication and account access
- Personalize your experience
- Analyze app usage to improve performance

## Third-party Services

We use third-party services such as:
- [Firebase](https://firebase.google.com/support/privacy)
- [Google Analytics](https://policies.google.com/privacy)
- [Stripe](https://stripe.com/privacy)

These services may collect information in accordance with their own privacy policies.

...

## Contact Us

If you have any questions, contact us at [support@healthcore.app](mailto:support@healthcore.app)
```
