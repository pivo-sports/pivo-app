# プライバシーポリシー

最終更新日: 2026年3月31日

Pivo（以下「本アプリ」）は、ユーザーのプライバシーを尊重し、個人情報の保護に努めます。本プライバシーポリシーは、本アプリが収集する情報、その利用目的、および保護方法について説明します。

## 1. 収集する情報

### 1.1 アカウント情報
本アプリでは Google アカウントを利用したログイン機能を提供しています。ログイン時に以下の情報を取得します。

- メールアドレス
- 表示名（Google アカウントの名前）
- ユーザー固有の識別子（UID）

### 1.2 ユーザーが入力する情報
本アプリの利用に伴い、ユーザーが自ら入力・登録する以下の情報を保存します。

- 動画に対するタグ付けデータ（タイムスタンプ、カテゴリ、選手名、結果等）
- コメント・メモ
- 選手情報（名前、ポジション、背番号、学年）
- 動画の視聴記録

### 1.3 自動的に収集する情報
- プッシュ通知のためのデバイストークン（Firebase Cloud Messaging）
- アプリ内の設定情報（端末内にローカル保存）

## 2. 情報の利用目的

収集した情報は、以下の目的で利用します。

- ユーザー認証およびアカウント管理
- 動画分析データ（タグ・コメント）の保存・共有・表示
- チームメンバー間でのリアルタイムなデータ同期
- プッシュ通知の送信
- Slack へのメモ通知（ユーザーが手動で送信した場合のみ）

## 3. 情報の共有

収集した情報は、以下の場合を除き第三者に提供しません。

- **同じ組織のメンバー間**: 本アプリは組織（チーム）単位で利用されるため、同じ組織に所属するメンバーはタグ付けデータ、コメント、視聴記録等を閲覧できます。
- **Firebase (Google)**: データの保存・認証・通知のため、Google が提供する Firebase サービスを利用しています。Google のプライバシーポリシーは [こちら](https://policies.google.com/privacy) をご参照ください。
- **法令に基づく場合**: 法令の要請がある場合に開示することがあります。

## 4. データの分離と保護

### 4.1 組織単位のデータ分離
本アプリでは、各組織（チーム）のデータは組織固有の識別子（orgId）により厳密に分離されています。

- タグ付けデータ、選手情報、動画情報等の分析データは、所属する組織のメンバーのみがアクセスできます。
- 他の組織のデータを閲覧・取得・改変することはできません。
- Firebase セキュリティルールにより、サーバー側でもアクセス制御が適用されています。

### 4.2 データの保存先
- ユーザーデータは Google Cloud（Firebase Cloud Firestore）に保存されます。
- データは Firebase のセキュリティルールにより保護されています。
- ローカル設定情報は端末内にのみ保存されます。
- 通信は全て暗号化（TLS）されています。

## 5. データの削除

ユーザーはアカウントの削除を希望する場合、以下の方法でデータの削除を依頼できます。

- アプリ内の設定画面からアカウント削除をリクエスト
- 開発者へメールにて連絡: pivo.support@gmail.com

アカウント削除時には、当該ユーザーに紐づく個人情報（メールアドレス、表示名、UID）を削除します。

## 6. 子どものプライバシー

本アプリは 13 歳未満の子どもを対象としていません。13 歳未満の方は本アプリを利用しないでください。

## 7. 本ポリシーの変更

本プライバシーポリシーは必要に応じて変更されることがあります。重要な変更がある場合は、アプリ内またはその他の方法でお知らせします。

## 8. お問い合わせ

本プライバシーポリシーに関するお問い合わせは、以下の連絡先までお願いします。

- メール: pivo.support@gmail.com

---

# Privacy Policy

Last updated: March 31, 2026

Handball Analyzer ("the App") respects your privacy and is committed to protecting your personal information. This Privacy Policy explains what information we collect, how we use it, and how we protect it.

## 1. Information We Collect

### 1.1 Account Information
The App uses Google Sign-In for authentication. When you sign in, we collect the following information:

- Email address
- Display name (from your Google account)
- Unique user identifier (UID)

### 1.2 User-Provided Information
Through your use of the App, the following information you voluntarily provide is stored:

- Video annotation data (timestamps, categories, player names, results, etc.)
- Comments and memos
- Player information (name, position, jersey number, grade)
- Video viewing history

### 1.3 Automatically Collected Information
- Device tokens for push notifications (Firebase Cloud Messaging)
- App settings (stored locally on your device)

## 2. How We Use Your Information

We use the collected information for the following purposes:

- User authentication and account management
- Storing, sharing, and displaying video analysis data (tags and comments)
- Real-time data synchronization between team members
- Sending push notifications
- Sending memos to Slack (only when manually triggered by the user)

## 3. Information Sharing

We do not share your information with third parties except in the following cases:

- **Within your organization**: The App is used on an organization (team) basis. Members of the same organization can view annotation data, comments, and viewing history.
- **Firebase (Google)**: We use Firebase services provided by Google for data storage, authentication, and notifications. Please refer to [Google's Privacy Policy](https://policies.google.com/privacy).
- **Legal requirements**: We may disclose information when required by law.

## 4. Data Isolation and Protection

### 4.1 Organization-Level Data Isolation
All data in the App is strictly isolated by organization (team) using a unique organization identifier (orgId).

- Analysis data such as annotations, player information, and video data is accessible only to members of the same organization.
- Users cannot view, retrieve, or modify data belonging to other organizations.
- Access control is enforced on the server side through Firebase security rules.

### 4.2 Data Storage
- User data is stored on Google Cloud (Firebase Cloud Firestore).
- Data is protected by Firebase security rules.
- Local settings are stored only on your device.
- All communication is encrypted via TLS.

## 5. Data Deletion

If you wish to delete your account, you can request data deletion through:

- The account deletion option in the App's settings
- Contacting the developer by email: pivo.support@gmail.com

Upon account deletion, personal information associated with your account (email address, display name, UID) will be deleted.

## 6. Children's Privacy

The App is not intended for children under 13 years of age. If you are under 13, please do not use the App.

## 7. Changes to This Policy

This Privacy Policy may be updated from time to time. We will notify you of any significant changes through the App or other means.

## 8. Contact Us

If you have questions about this Privacy Policy, please contact us at:

- Email: pivo.support@gmail.com
