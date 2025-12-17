# Privacy Policy for SweepYourMail

**Last Updated:** December 2024

---

## Our Privacy Commitment

SweepYourMail is built on a fundamental principle: **your email data should never leave your device**. We have designed our extension with a strict local-only architecture. We operate no servers, collect no data, and have no way to access your information even if we wanted to.

---

## Overview

SweepYourMail is a Chrome extension that helps users clean and organize their Gmail inbox by grouping emails by sender and enabling bulk actions. This privacy policy explains what data we access, how we use it, and how we protect your privacy.

---

## The Most Important Points

1. **100% LOCAL PROCESSING** - All operations happen in your browser
2. **NO REMOTE SERVERS** - We don't operate any servers or cloud infrastructure
3. **NO DATA TRANSMISSION** - Your data is never sent anywhere except Gmail's official API
4. **NO DATA COLLECTION** - We collect zero user data
5. **NO ANALYTICS** - We don't track how you use the extension
6. **NO THIRD PARTIES** - We don't share anything with anyone

---

## Data We Access

### Email Metadata (Read-Only Access)

When you use SweepYourMail, we access the following email metadata through the official Gmail API:

| Data Type | Purpose |
|-----------|---------|
| Sender name | To group emails by sender |
| Sender email address | To identify unique senders |
| Email subject lines | For category detection (newsletters, promotions, etc.) |
| Email dates (sent/received) | To show date ranges and sorting |
| Email labels | To understand inbox organization |
| List-Unsubscribe headers | To provide unsubscribe functionality |
| Message IDs | To perform actions on specific emails |

### What We NEVER Access

We explicitly DO NOT access:

- **Email body content** - We never read your actual messages
- **Attachments** - We don't access any attached files
- **Contacts** - We don't access your contact list
- **Calendar** - We don't access Google Calendar
- **Drive** - We don't access Google Drive
- **Photos** - We don't access Google Photos
- **Any other Google services** - Only Gmail, and only metadata

---

## How We Use Your Data

### Local Processing Only

All email metadata is processed **entirely within your browser**:

1. **Fetching:** Email metadata is fetched directly from Gmail API to your browser
2. **Processing:** Analysis and grouping happens in browser memory
3. **Storage:** Only aggregated statistics are cached in your browser's IndexedDB
4. **Display:** Results are shown in the extension sidebar
5. **Actions:** Your commands are sent directly to Gmail API

**At no point does any data pass through our infrastructure, because we have no infrastructure.**

### What Gets Stored Locally

In your browser's IndexedDB storage:
- Sender email addresses
- Email counts per sender
- First/last email dates per sender
- Your filter preferences

In Chrome's sync storage:
- Your extension preferences (dark mode, sort order, etc.)

### What NEVER Gets Stored

- Individual email content
- Email subjects
- Attachments
- Passwords or OAuth tokens (managed by Chrome)

---

## Actions We Perform

When you explicitly request it, SweepYourMail can perform these actions through the Gmail API:

| Action | What Happens |
|--------|--------------|
| **Delete** | Moves emails to Gmail's Trash |
| **Archive** | Removes Inbox label from emails |
| **Mark as Spam** | Moves emails to Gmail's Spam folder |
| **Block Sender** | Creates a Gmail filter to auto-delete future emails |
| **Mark as Read** | Sets email status to read |
| **Unsubscribe** | Opens the unsubscribe link in a new tab |

All actions are performed directly between your browser and Gmail's servers. We have no visibility into these operations.

---

## Data Storage Architecture

### Local Storage (Your Device)

| Storage Type | What's Stored | Where |
|--------------|---------------|-------|
| IndexedDB | Sender aggregates | Your browser |
| Chrome Storage Sync | Preferences | Your Google account (synced by Chrome) |
| Memory | Processing data | Your browser RAM (cleared on close) |

### Remote Storage

**None.** We operate:
- No servers
- No databases
- No cloud storage
- No CDN
- No analytics platforms
- No logging services

---

## Permissions Explained

Our extension requests the following Chrome permissions:

### `identity`
**Why:** To authenticate with your Google account using OAuth 2.0
**What it does:** Allows Chrome's secure identity API to handle login
**Privacy:** Credentials are managed by Chrome, never by us

### `storage`
**Why:** To save your preferences
**What it does:** Stores settings like sort order, dark mode preference
**Privacy:** Data stays in your Chrome profile

### `alarms`
**Why:** To enable background sync for new email notifications
**What it does:** Allows periodic checks for new emails
**Privacy:** Only triggers local processing

### Gmail API Scopes

| Scope | Purpose |
|-------|---------|
| `gmail.readonly` | Read email metadata to display sender analytics |
| `gmail.modify` | Perform actions (delete, archive, spam) when you request them |

---

## Third-Party Services

SweepYourMail communicates with **only** these services:

| Service | URL | Purpose |
|---------|-----|---------|
| Gmail API | `https://gmail.googleapis.com` | Email operations |
| Google OAuth | `https://www.googleapis.com` | Authentication |

**We do not use:**
- Analytics services (Google Analytics, Mixpanel, etc.)
- Crash reporting services (Sentry, Bugsnag, etc.)
- Advertising networks
- Social media integrations
- Any other third-party services

---

## Data Security

### Encryption
- All communication with Gmail uses HTTPS/TLS encryption
- Data in transit is protected by Google's security infrastructure

### Authentication
- OAuth 2.0 tokens are managed by Chrome's identity API
- Tokens are never stored in plain text by our extension
- Tokens are never transmitted to any server except Google's

### Local Security
- Data stored in IndexedDB is protected by Chrome's security model
- Data is isolated per extension and cannot be accessed by other extensions or websites

---

## Your Rights and Controls

### Access Your Data
You can view all locally stored data:
1. Open Chrome DevTools (F12)
2. Go to Application tab
3. View IndexedDB > SweepYourMail

### Delete Your Data
Option 1: Clear extension data
- Right-click extension icon > Manage extension > Clear data

Option 2: Uninstall extension
- All local data is automatically deleted

Option 3: Clear browser data
- Chrome Settings > Privacy > Clear browsing data

### Revoke Gmail Access
Remove SweepYourMail's access to your Gmail:
1. Go to https://myaccount.google.com/permissions
2. Find SweepYourMail
3. Click "Remove Access"

---

## Children's Privacy

SweepYourMail is not intended for use by children under 13 years of age. We do not knowingly collect information from children.

---

## Changes to This Policy

We may update this privacy policy from time to time. If we make significant changes, we will:
- Update the "Last Updated" date
- Notify through extension update notes
- The latest version is always available at this URL

---

## Compliance

While we are a simple Chrome extension with no data collection, we are designed with privacy regulations in mind:

### GDPR (EU)
- **Data minimization:** We only access necessary metadata
- **Purpose limitation:** Data used only for stated purposes
- **Storage limitation:** Data stored locally, deletable anytime
- **Right to erasure:** Uninstall removes all data

### CCPA (California)
- **No sale of data:** We don't sell any data (we don't collect any)
- **Right to know:** This policy explains all data practices
- **Right to delete:** Clear data anytime via browser settings

---

## Open Source Commitment

SweepYourMail is committed to transparency:
- No hidden data collection
- No monetization of user data
- Clear and honest communication
- Privacy-first architecture

---

## Contact Us

For questions or concerns about this privacy policy:

- **Email:** casblasvic@gmail.com
- **GitHub:** [github.com/casblasvic](https://github.com/casblasvic)

We typically respond within 48 hours.

---

## Summary

**SweepYourMail processes your email metadata 100% locally to help you organize your inbox.**

- We have NO servers
- We collect NO data
- We share NOTHING with third parties
- Your emails NEVER leave your browser
- You can delete all data instantly by uninstalling

**Your privacy is not just a feature - it's our architecture.**

---

*This privacy policy is effective as of December 2024.*
