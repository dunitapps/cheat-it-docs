PRIVACY POLICY<br>
CheatIt: Watch Notes & AI<br>
Effective date: 18.11.2026

This Privacy Policy explains how CheatIt (we, us, our) handles information when you use the CheatIt app on iPhone and Apple Watch (the Service).

CheatIt is published by Ilija Ivkovic, based in the Republic of Serbia, who is responsible for (the controller of) your personal data. You can reach us at contact@dunitapps.com.

CheatIt is a notes app with optional AI features. Most of your content stays on your devices. When you choose to use AI features, the content you select is sent to our backend and to third-party AI providers to generate a response.

1) The information we handle

A) Notes, documents, photos, and chat content (your Content)<br>
CheatIt lets you create notes and attach PDFs and photos. This content is stored on your device and synced between your iPhone and Apple Watch.

If you have iCloud enabled, Apple may also store and sync your content using iCloud services. Apple’s iCloud data handling is governed by Apple’s policies.

B) AI requests (only when you use AI)
AI features are optional. When you ask AI a question, we send the following to our backend service so it can generate an answer:<br>
• the prompt you type<br>
• relevant context you choose to include (for example, note text, PDF text, and images you attach)<br>

Your request is routed through OpenRouter to the model provider you selected, so the provider can generate a response.

C) Subscription and entitlement information<br>
AI features may require a paid subscription. Purchases are handled by Apple through In-App Purchases.

We use RevenueCat to manage subscription entitlements. RevenueCat provides us with an entitlement status (for example, whether AI features are active). The app also uses an app-specific identifier (often called an “App User ID”) for entitlement checks.

When you use AI features, our backend receives this identifier so we can verify entitlements, enforce usage limits, and prevent abuse.

We do not receive your payment card information. Apple handles payment details.

D) Usage, diagnostics, and security data<br>
To operate the Service, we may process limited technical data such as:<br>
• request metadata (for example, timestamps, platform like iOS or watchOS, and a request identifier)<br>
• token counts and similar usage metrics needed to enforce quotas and manage costs<br>
• basic logs for reliability and security (for example, error messages and rate-limiting events)<br>
• network information like IP address, which is typically processed by servers when you connect<br>

The app also sends usage statistics (which features are used, and whether an action succeeded or failed) and crash reports, with basic details such as device model, iOS version, app version, language, time zone, and a random ID created on your device. These are not linked to your name, email, or account, and do not include the content of your notes, files, or chats. If we show a short in-app survey, your answers are sent the same way. Our backend reports its own errors and AI request metrics (such as the model, response time, and token counts, without your prompts or answers) to the same service.

We do not require you to create an account with your name or email address.

E) Feature requests and support messages<br>
The app has a board where you can suggest features and vote on them, and a form for writing to us.<br>
• When you suggest a feature, we store the title and description you write, with your App User ID. We review each suggestion before anyone else can see it. Once we approve it, everyone using the app can read the title and description, but not who sent it.<br>
• When you vote for a feature request or follow one, we store that with your App User ID. Other people only see the number of votes.<br>
• When you send a support message, we store your name, email address, and message, plus your app version, iOS version, device model, and language and region setting, with your App User ID, so we can reply and look into the problem.<br>

New suggestions and support messages are delivered to us in a private Telegram chat, so Telegram stores a copy of them too.

F) Feature request notifications (only if you turn them on)<br>
If you turn on “Notify Me About Progress” for a feature request and allow notifications, your device sends us its Apple push notification token. We store it encrypted, with your App User ID and whether it came from a test or App Store build. We use it only to tell you when a feature request you follow is planned, in progress, or available. A notification contains a short standard message and the feature request’s ID, never your notes or other content. Apple Push Notification service delivers it.

We delete the token when you turn off notifications for CheatIt in iOS Settings (the next time you open the app), when Apple tells us it is no longer valid, or 90 days after the app last sent it. We delete follows of a feature request within 30 days after it is closed or removed, and our record of which notifications we sent after 90 days.

2) How we use information

We use the information above to:<br>
• provide core app functionality, including syncing between iPhone and Apple Watch<br>
• provide optional AI features when you request them<br>
• manage subscriptions and enforce entitlements and usage limits<br>
• run the feature request board, answer support messages, and send notifications you turned on<br>
• maintain, secure, and improve the Service<br>
• comply with legal obligations and enforce our Terms of Service<br>

Legal bases<br>
Where data protection law applies (such as the GDPR or Serbia’s Law on Personal Data Protection), we rely on:<br>
• contract: to provide the app and the features you use, including AI features, subscriptions, the feature request board, and replies to your support messages<br>
• consent: for feature request notifications, which you give by allowing notifications and can withdraw at any time<br>
• legitimate interests: for usage statistics, crash reports, security, and usage limits, so we can keep the app working and improve it. You can object at any time, for example with the “Share Anonymous Usage Stats” switch<br>
• legal obligation: where the law requires us to keep or share information<br>

3) How we share information

We do not sell your personal information.

We share information only as needed to provide the Service, including with:<br>
• Apple, for iCloud syncing (if enabled), In-App Purchases, and delivering notifications you turned on<br>
• RevenueCat, for subscription entitlement management<br>
• OpenRouter and the AI model provider you selected, to generate AI responses<br>
• PostHog, which processes usage statistics and crash reports for us on servers in the European Union<br>
• Telegram, where we receive new feature suggestions and support messages<br>
• service providers that help us run our backend infrastructure (for example, hosting and database providers)<br>

4) OpenRouter and AI provider data handling

OpenRouter and model providers are third parties. Their data practices can differ by provider and model.<br>

Based on OpenRouter documentation, OpenRouter does not store prompts or responses unless prompt logging is explicitly enabled. OpenRouter does store request metadata such as token counts and latency, and it may perform limited anonymous prompt categorization for reporting and rankings.

We configure our OpenRouter account privacy settings to:<br>
• disable free endpoints that may train on inputs<br>
• disable free endpoints that may publish prompts<br>
• disable paid endpoints that may train on inputs<br>
• keep OpenRouter input/output logging for all requests disabled<br>

We do not enable “ZDR Endpoints Only” because many models do not support it. As a result, even with the settings above, the underlying model provider may retain or process data for limited periods for safety, abuse prevention, debugging, or operational purposes, depending on the provider and model.

If you are sending sensitive information, consider not using AI features, or limit what you include in prompts and attachments.

5) Data storage and retention

On your devices<br>
Your notes, documents, photos, and chat history are stored locally on your device and synced to your Apple Watch.<br>

If iCloud is enabled<br>
If you use iCloud, your content may be stored in iCloud. Apple controls iCloud retention and deletion behavior.<br>

On our backend
We store limited records needed to operate AI features, such as subscription entitlement snapshots and usage metrics (for example, request counts and token usage). We keep these records as long as reasonably necessary for operating the Service, handling support requests, and complying with legal obligations.

Feature suggestions and votes are kept while the feature board runs. Support messages are kept as long as reasonably necessary to answer you and handle follow-ups. Push tokens and follows are deleted as described in section 1F.

Third-party retention
OpenRouter and model providers may retain or process data according to their own policies. See their documentation for details.

6) Your choices

• AI is optional. You can use CheatIt without AI features.<br>
• You can delete notes and attachments at any time in the app. If iCloud syncing is enabled, deletions will also sync through iCloud.<br>
• You can manage or cancel subscriptions in your Apple ID settings.<br>
• You can turn off usage statistics and crash reports at any time in Settings, under “Share Anonymous Usage Stats”.<br>
• Feature request notifications are optional. Turn them off with the “Notify Me About Progress” switch on a feature request, or in iOS Settings > Notifications > CheatIt.<br>
• If you want to request deletion of backend records associated with your usage, contact us at contact@dunitapps.com.<br>
• Depending on where you live, you also have the right to access, correct, or delete your data, to restrict or object to how we use it, and to receive a copy of it. Contact us at the same address.<br>

7) International users

We are based in the Republic of Serbia, and we may process information in other countries depending on where our service providers (such as OpenRouter, model providers, RevenueCat, Apple, PostHog, Telegram, and hosting providers) operate.

8) Changes to this policy<br>
We may update this Privacy Policy from time to time. If we make material changes, we will update the effective date and provide notice where required.

9) Contact<br>
If you have questions about this Privacy Policy, contact us at contact@dunitapps.com

10) Third-party policies

For more information about third-party services, you can review:
• OpenRouter privacy policy: https://openrouter.ai/privacy<br>
• OpenRouter privacy and logging overview: https://openrouter.ai/docs/features/privacy-and-logging/<br>
• OpenRouter zero data retention (ZDR): https://openrouter.ai/docs/features/zdr<br>
• RevenueCat privacy policy: https://www.revenuecat.com/privacy/<br>
• PostHog privacy policy: https://posthog.com/privacy<br>
• Telegram privacy policy: https://telegram.org/privacy<br>
• Apple privacy policy: https://www.apple.com/legal/privacy/<br>
