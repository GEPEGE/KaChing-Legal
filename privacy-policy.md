Privacy Policy for Ka Ching!
Last updated: November 2026

Overview
Ka Ching! is an Android app for tracking personal finances. You can enter transactions manually, manage accounts and budgets, and optionally detect payments from notifications or use voice and OpenAI assistance. This policy explains what the app handles, what stays on your device, and when information can leave it.

In short
Your financial records are stored in an encrypted database on your device. We do not operate a server that receives your transaction history.
You do not need a Ka Ching! account or sign-in. There are no ads or analytics in the app.
Notification capture is optional. Android grants notification access system-wide, but Ka Ching! ignores notifications from apps you have not selected before reading their text.
If you enable OpenAI assistance using your own API key, selected notification text or a voice transcript, along with relevant account, category and rule names, is sent to OpenAI.
Backups go to a location you choose and are encrypted before they are written. Readable exports and diagnostic files leave the app only when you choose to export or share them.
An optional purchase is handled by Google Play Billing. We do not receive your payment card details.
Data We Handle
Ka Ching! does not ask for your name, email address or phone number to use the app. It does not create an online user profile. The information it handles comes from what you enter, the features you enable, and the payment notifications you choose to capture.

What is stored on your device
The encrypted local database contains your accounts and balances, transactions and descriptions, categories, budgets, recurring transactions, merchant rules and related preferences. If you enable notification capture, it may also contain the text and details of captured notifications from your selected sources, detected payment suggestions and diagnostic events. Your OpenAI API key, if supplied, is encrypted locally using Android Keystore.

The app uses these records to show your history and statistics, prepare transactions, apply your rules and avoid duplicate payment suggestions. They are not routinely uploaded to a Ka Ching! server.

When Data Leaves Your Device
Notification capture
Android's notification-listener permission grants access at the system level. Ka Ching! first checks which app sent a notification and ignores unselected apps before reading their text. For apps you select, it may process notification text and fields such as the time, amount, currency, merchant and payment method. Depending on your settings, a recognized payment may be offered for review or added automatically.

Selecting a source does not mean every notification from it is necessarily a payment. Do not select an app whose notification content you do not want Ka Ching! to inspect. Captured information remains on your device unless you separately enable OpenAI assistance or choose to export it. You can disable capture, change sources and clear diagnostics in the app.

Voice input and your device's speech recognizer
Voice input uses your microphone only while you invoke it. The Android speech-recognition service available on your device converts speech to text. That service, often supplied by Google or another provider, may process your audio or transcript under its own privacy policy. Ka Ching! does not keep the microphone active in the background or store an audio recording in its database. It uses the recognized words to prepare a transaction.

Optional OpenAI assistance
If you provide your own OpenAI API key and turn on assistance, Ka Ching! sends requests directly to OpenAI to interpret a voice transcript or a notification from a selected app. The request can include the phrase or notification text, the sending app's name, a preliminary local interpretation, and the names and currencies of available accounts, categories and enabled merchant rules. This information may reveal purchases and spending habits.

The key is sent to OpenAI to authenticate the request. Ka Ching! sets store: false, but OpenAI may still retain security or abuse-monitoring logs according to its own policies. Your OpenAI API account may incur charges independently of any Google Play purchase. You can turn off assistance and remove your key in the app's settings. OpenAI's API data controls are explained at https://developers.openai.com/api/docs/guides/your-data.

Backups and exports
You choose where to save a backup using Android's document picker, or select a folder for automatic backups. Ka Ching! encrypts backup files with your backup password before writing them. If the chosen location is a cloud service such as Google Drive, that provider stores the encrypted file under its own privacy policy. Ka Ching! does not receive the file. Keep your password safe: a lost backup password cannot be recovered by the app.

You can also export records in a readable format. Unlike an encrypted backup, a readable export may reveal your transactions to anyone with access to that file or its destination. Sharing it is your choice.

Notification diagnostics
You can manually export a diagnostic JSON file to investigate notification detection. Ka Ching! replaces or removes certain free text and identifiers, but the file is not guaranteed to be anonymous. Amounts, timing and other details may still reveal information. Review it before sharing. We do not receive diagnostics automatically.

In-app purchase through Google Play
Google Play Billing handles the optional Plus purchase and provides the app with purchase status and technical purchase information needed to confirm or restore it. We do not receive your full payment card number. Google's privacy policy applies: https://policies.google.com/privacy. Plus purchasing and access controls are currently being tested and may change before public release.

Storage, Retention and Deletion
Local records stay on your device until you delete them, clear the app's storage or uninstall it. Deleted transactions may remain recoverable in the app's trash for 30 days before they are purged. From Settings, you can clear diagnostics, delete transaction history or erase financial data.

Uninstalling or clearing app storage removes local app data. It does not delete copies you placed in other locations, including cloud backups, readable exports or diagnostic files. Delete those files from their respective locations separately. External providers retain information they receive under their own policies and applicable law.

Security
Ka Ching! encrypts its local database and backup files. Requests to OpenAI use HTTPS. You may also enable an app lock using Android credentials or biometrics. Protect your device, backup password and API key. No security measure is absolute.

Permissions
Ka Ching! requests internet access for optional OpenAI assistance and Google Play services; microphone access for voice input; and permission to display its own notifications if you enable payment alerts. Notification capture requires a separate Android notification-listener access grant. You control these permissions in Android Settings. The app may display installed apps so you can choose notification sources; that visibility does not itself grant access to their data.

Your Choices and Rights
You can use manual tracking without enabling notification capture or OpenAI. You can change your settings, revoke Android permissions, export records and delete local data. In general, we cannot access or identify records stored only in your encrypted local database. For privacy questions or requests concerning information you have sent us, contact us below. If you are in the European Economic Area, you may also complain to your data protection authority.

Children's Privacy
Ka Ching! is not designed for children. We do not knowingly request personal information from children.

Changes to This Policy
We may update this policy when the app or its providers change. The current version will be published at this URL with an updated date.

Contact
For questions about this policy, contact:

appsgpg@gmail.com

