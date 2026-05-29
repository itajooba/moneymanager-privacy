---
layout: default
title: Delete your data — Money Manager Pro
---

# Delete your data — Money Manager Pro

Money Manager Pro lets you delete individual records (or all of them) at any
time, directly inside the app, without deleting your account. This page
explains exactly what you can delete, how, and what — if anything — is
retained.

If you want to delete your **entire account** and stop using the app, see
[Delete your account]({{ "/delete-account.html" | relative_url }}) instead.

## What you can delete from inside the app

Every record you create in Money Manager Pro can be deleted from within the
app. There is no separate request needed — deletion happens immediately and
syncs to the cloud (for signed-in users) within minutes.

You can delete:

- Individual **transactions** (income, expenses, transfers)
- **Accounts** (your bank, cash, or card accounts you track)
- **Categories** and sub-categories
- **Loans** and the payments recorded against them
- **Investments**
- **Goals**
- **Recurring transaction rules**
- Individual **cloud backups** (snapshots)

## How to delete a specific item

1. Open Money Manager Pro on your phone.
2. Navigate to the item you want to delete (a transaction, account, goal, etc.).
3. Tap the item to open it, then tap the **delete** icon (a trash can) or
   the **Delete** option in the menu.
4. Confirm the deletion.

The item is removed from your device immediately. If you are signed in to the
cloud, the deletion propagates to your other devices on the next sync.

## How to delete several items at once

- To delete **all transactions in a specific account**: delete that account,
  which removes its associated transactions.
- To delete **all data of a specific category**: delete the category and its
  sub-categories.
- To delete **everything in the cloud at once**: sign in to Profile, scroll
  to Cloud, and delete each backup snapshot, then delete your account (see
  the dedicated [account deletion page]({{ "/delete-account.html" | relative_url }})).

## What is deleted versus what is retained

**Deleted immediately on your action:**

- The record from your device's local database.
- The corresponding record from your cloud-synced data (Firestore).
- Any backup snapshots you choose to delete.

**Retained until you delete it (no automatic deletion):**

- Anything you do not delete remains stored on your device and, if signed
  in, in your cloud account, until you delete it or delete your account.

**Retained only where required by applicable law:**

- Subscription / billing records held by Google Play for tax-compliance
  purposes. These are managed by Google Play, not by us, and follow Google's
  own retention schedule.

## Need help?

If you cannot find a delete option in the app, or if you have a deletion
request for data you can no longer access (for example, because you've
uninstalled the app), email
[shashi.k@abitindia.com](mailto:shashi.k@abitindia.com) and we will action
the request within **30 days**.

For the full privacy policy, including all your data-protection rights,
see the [privacy policy]({{ "/" | relative_url }}).
