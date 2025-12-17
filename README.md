<p align="center">
  <img src="icon128.png" alt="SweepYourMail Logo" width="128" height="128">
</p>

<h1 align="center">SweepYourMail</h1>

<p align="center">
  <strong>A 100% local, privacy-first Chrome Extension for cleaning and organizing your Gmail inbox.</strong>
</p>

<p align="center">
  <a href="https://chrome.google.com/webstore"><img src="https://img.shields.io/badge/Chrome-Web%20Store-4285F4?style=for-the-badge&logo=google-chrome&logoColor=white" alt="Chrome Web Store"></a>
  <a href="PRIVACY_POLICY.md"><img src="https://img.shields.io/badge/Privacy-Policy-blue?style=for-the-badge" alt="Privacy Policy"></a>
  <a href="#"><img src="https://img.shields.io/badge/License-MIT-green?style=for-the-badge" alt="License"></a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/100%25-LOCAL-success?style=flat-square" alt="100% Local">
  <img src="https://img.shields.io/badge/NO-SERVERS-success?style=flat-square" alt="No Servers">
  <img src="https://img.shields.io/badge/FREE-FOREVER-success?style=flat-square" alt="Free Forever">
  <img src="https://img.shields.io/badge/NO-TRACKING-success?style=flat-square" alt="No Tracking">
</p>

SweepYourMail helps you take control of your email by grouping messages by sender and enabling bulk operations. Delete, archive, mark as spam, or block senders - all with just a few clicks.

---

## Your Data Never Leaves Your Device

**SweepYourMail operates 100% locally.** We have no servers, no databases, no cloud infrastructure. All email processing happens entirely within your browser. Your credentials, emails, and personal data never touch any external server - only the official Gmail API.

---

## What is SweepYourMail?

SweepYourMail is a free Chrome extension that integrates directly into Gmail as a convenient sidebar. It analyzes your inbox to show you exactly which senders are filling up your mailbox, then lets you clean up with powerful bulk actions.

### The Problem We Solve

- Your inbox has thousands of emails from hundreds of senders
- Finding and cleaning up emails from specific senders is tedious
- Manual deletion takes forever
- Other tools charge $30-100/year and some send your data to their servers

### Our Solution

SweepYourMail gives you a complete overview of your inbox by sender, with one-click bulk actions to clean up fast - all while keeping your data 100% private and local.

---

## Complete Feature List

### Sender Analytics Dashboard

| Feature | Description |
|---------|-------------|
| **Sender Grouping** | All emails automatically grouped by sender |
| **Email Count** | See exactly how many emails each sender has sent you |
| **Date Range** | View first and last email date from each sender |
| **Category Detection** | Automatic detection of newsletters, notifications, promotions |
| **Real-time Updates** | Counts update as you perform actions |

### Bulk Actions

| Action | Description |
|--------|-------------|
| **Bulk Delete** | Delete all emails from selected senders with one click |
| **Bulk Archive** | Archive emails to remove from inbox but keep accessible |
| **Bulk Spam** | Mark all emails from a sender as spam |
| **Block Sender** | Create Gmail filter to automatically delete future emails |
| **Mark as Read** | Mark all emails from a sender as read |
| **Unsubscribe** | Quick access to unsubscribe links when available |

### Selection & Navigation

| Feature | Description |
|---------|-------------|
| **Multi-Select** | Select multiple senders for batch operations |
| **Select All** | Select all visible senders at once |
| **Search** | Find senders by name or email address |
| **Sort by Count** | See heaviest senders first |
| **Sort by Date** | See most recent or oldest senders |
| **Sort Alphabetically** | Find senders by name |
| **Category Filter** | Filter by newsletters, promotions, social, etc. |

### User Interface

| Feature | Description |
|---------|-------------|
| **Gmail Sidebar** | Integrated directly into Gmail interface |
| **Collapsible Panel** | Expand or collapse to save space |
| **Dark Mode** | Automatic detection of Gmail's dark theme |
| **Responsive Design** | Works on different screen sizes |
| **Progress Indicators** | See progress during bulk operations |
| **Confirmation Dialogs** | Prevent accidental mass deletions |

### Conversation Features

| Feature | Description |
|---------|-------------|
| **Reverse Order** | Show oldest emails first in conversation threads |
| **Quick Toggle** | Floating button to switch conversation order |
| **Persistent Setting** | Your preference is remembered |

### Settings & Preferences

| Feature | Description |
|---------|-------------|
| **Auto-refresh** | Automatically refresh sender list on open |
| **Sync Preferences** | Settings sync across Chrome browsers |
| **Account Management** | Easy connect/disconnect of Gmail account |
| **Cache Management** | Clear local cache when needed |

---

## Privacy & Security

**[Read our full Privacy Policy](PRIVACY_POLICY.md)**

### 100% Local Processing

SweepYourMail is built with a strict **local-only architecture**:

- **NO remote servers** - We don't operate any servers whatsoever
- **NO data transmission** - Your email data never leaves your browser
- **NO cloud storage** - Nothing is stored outside your device
- **NO analytics** - We don't track usage or collect telemetry
- **NO cookies** - We don't use tracking cookies
- **NO third-party services** - Only official Google/Gmail APIs

### How Your Data Stays Local

1. **Authentication:** Handled by Chrome's secure identity API
2. **Email Fetching:** Direct from Gmail API to your browser
3. **Processing:** All analysis happens in your browser's memory
4. **Storage:** Only aggregated sender counts stored in browser's IndexedDB
5. **Actions:** Sent directly to Gmail API from your browser

### What We Access (Read-Only)

- Sender name and email address
- Email subject lines (for categorization)
- Email dates
- Email labels

### What We NEVER Access

- Email body content
- Attachments
- Contacts
- Calendar
- Drive files
- Any other Google services

### Security Measures

- **HTTPS Only** - All Gmail API communication is encrypted
- **OAuth 2.0** - Industry-standard secure authentication
- **Chrome Identity API** - Tokens managed securely by Chrome
- **No Plain Text Storage** - Credentials never stored in readable form
- **Minimal Permissions** - Only request what's necessary

---

## How It Works

1. **Install** the extension from Chrome Web Store
2. **Open Gmail** in your browser
3. **Click Connect** to authenticate with your Gmail account
4. **Wait for Analysis** - The extension scans your inbox (locally!)
5. **View Senders** - See all senders sorted by email count
6. **Select & Act** - Choose senders and perform bulk actions
7. **Enjoy** your clean inbox!

---

## Comparison with Paid Alternatives

| Feature | SweepYourMail | Clean Email | Unroll.me | Mailstrom |
|---------|---------------|-------------|-----------|-----------|
| **Price** | **FREE** | $29.99/year | Free* | $49.99/year |
| **100% Local** | **YES** | No (Cloud) | No (Cloud) | No (Cloud) |
| **No Data Collection** | **YES** | No | No | No |
| **Sender Analytics** | YES | YES | YES | YES |
| **Bulk Delete** | YES | YES | Limited | YES |
| **Block Senders** | YES | YES | No | YES |
| **Open Source** | YES | No | No | No |

*Unroll.me is free but monetizes by selling anonymized email data

**Why choose SweepYourMail?** Your data stays on YOUR device. Period.

---

## Technical Details

- **Platform:** Chrome Extension (Manifest V3)
- **Authentication:** OAuth 2.0 via Chrome Identity API
- **API:** Gmail API (googleapis.com)
- **Storage:** IndexedDB (local browser storage)
- **Language:** JavaScript (Vanilla, no frameworks)

### Permissions Explained

| Permission | Why We Need It |
|------------|----------------|
| `identity` | To authenticate with Google OAuth 2.0 |
| `storage` | To save your preferences locally |
| `alarms` | For background sync of new emails |
| `gmail.readonly` | To read email metadata (sender, date, labels) |
| `gmail.modify` | To perform actions you request (delete, archive, spam) |

---

## Frequently Asked Questions

### Is SweepYourMail really free?
Yes, completely free with no premium tiers, no trials, no hidden costs.

### Do you sell my data?
No. We don't collect any data to sell. Everything stays on your device.

### Can you read my emails?
We only access metadata (sender, subject, date). We never read email body content.

### What happens if I uninstall?
All local data is deleted. Since we have no servers, there's nothing to delete remotely.

### Is it safe to give Gmail access?
Yes. We use Google's official OAuth 2.0 system. You can revoke access anytime at https://myaccount.google.com/permissions

### Why is it free if others charge?
Because we don't have server costs - everything runs locally. And we believe email privacy tools should be accessible to everyone.

---

## Support

For questions, issues, or feedback:
- **Email:** casblasvic@gmail.com
- **GitHub:** [github.com/casblasvic](https://github.com/casblasvic)

---

## Legal

- [Privacy Policy](PRIVACY_POLICY.md)
- By using SweepYourMail, you agree to Google's Terms of Service for Gmail.

---

**Made with privacy as the #1 priority. Your inbox, your data, your device.**
