# Vaultwarden User Enrolment Guide

## Purpose

This guide explains how to enrol and start using the organisation's self-hosted Vaultwarden password manager.

Vaultwarden is compatible with the official Bitwarden apps and browser extensions. Users should use the official Bitwarden app or extension, but must change the server option to the self-hosted Vaultwarden address.

---

## Vaultwarden Site

Use this server address:

```text
https://vault.darol.club
```

---

## Important Note

Before logging in or creating an account, users must change the Bitwarden app or browser extension server option from the default Bitwarden cloud service to the self-hosted server.

The self-hosted server is:

```text
https://vault.darol.club
```

If this step is missed, the user may accidentally create or access an account on the public Bitwarden cloud instead of the organisation's Vaultwarden server.

---

## Enrolment Overview

Each user needs to complete the following steps:

```text
[ ] Open https://vault.darol.club
[ ] Create a new account
[ ] Install the Bitwarden app or browser extension
[ ] Change the server option to Self-hosted
[ ] Use https://vault.darol.club as the server URL
[ ] Log in to the new account
[ ] Enable MFA / two-step login using Email or Duo
[ ] Send the email address used for registration to the administrator
[ ] Wait for the administrator to invite the account into the organisation vault
[ ] Accept the organisation vault invitation
```

---

## Step 1 — Create Your Account

1. Open a web browser.
2. Go to:

   ```text
   https://vault.darol.club
   ```

3. Select **Create Account**.
4. Enter your email address.
5. Create a strong master password.
6. Complete the registration process.
7. Log in using your new account.

Important: make a note of the exact email address used to create the account. You will need to send this email address to the administrator so they can invite you into the organisation vault.

---

## Step 2 — Install the Bitwarden App or Browser Extension

Vaultwarden works with the official Bitwarden apps and browser extensions.

You can install Bitwarden on:

- Apple iPhone or iPad
- Android phone or tablet
- Google Chrome
- Microsoft Edge
- Mozilla Firefox
- Brave
- Windows desktop
- macOS desktop

---

## Step 3 — Change the App or Extension to Self-hosted

Before signing in to the app or browser extension:

1. Open the Bitwarden app or browser extension.
2. On the login screen, look for the server, region, or settings option.
3. Select **Self-hosted**.
4. Enter the server URL:

   ```text
   https://vault.darol.club
   ```

5. Save or continue.
6. Sign in using the account you created.

---

## Step 4 — Enable MFA / Two-Step Login

After creating your account, you must enable MFA / two-step login.

This helps protect your password vault even if your master password is exposed.

### Approved MFA methods

Use one of the following methods:

```text
Email
Duo
```

### Enable MFA using Email

1. Log in to the web vault:

   ```text
   https://vault.darol.club
   ```

2. Open your account settings.
3. Go to **Security** or **Two-step Login**.
4. Choose **Email**.
5. Follow the prompts to confirm your email address.
6. Save the setting.
7. Log out and log back in to confirm that the email MFA prompt works.

### Enable MFA using Duo

1. Log in to the web vault:

   ```text
   https://vault.darol.club
   ```

2. Open your account settings.
3. Go to **Security** or **Two-step Login**.
4. Choose **Duo**.
5. Follow the Duo enrolment prompts.
6. Confirm that Duo approval works.
7. Log out and log back in to test the Duo MFA prompt.

---

## Step 5 — Send Your Registration Email to the Administrator

After your account has been created and MFA has been enabled, send the administrator the email address you used to register.

Send only the email address.

Example:

```text
I have created my Vaultwarden account and enabled MFA.

Email used: user@example.com
```

Do not send your master password.

The administrator needs your registered email address so they can invite you into the organisation vault.

---

## Step 6 — Accept the Organisation Vault Invitation

After the administrator invites you:

1. Check your email inbox.
2. Open the Vaultwarden / Bitwarden organisation invitation.
3. Accept the invitation.
4. Log in to:

   ```text
   https://vault.darol.club
   ```

5. Confirm that you can see the organisation vault or shared collections.

If you cannot see the organisation vault after accepting the invitation, contact the administrator.

---

## Choosing a Strong Master Password

Your master password protects everything stored in your vault.

Use a password that is:

- Long
- Unique
- Not used anywhere else
- Easy for you to remember but difficult for others to guess

A good approach is to use a passphrase.

Example format:

```text
Several-Random-Words-Year-Symbol
```

Do not use example passwords. Create your own.

---

## Very Important: Do Not Forget Your Master Password

The master password cannot normally be recovered by an administrator.

If you forget your master password, your vault may need to be reset and saved passwords may be lost.

Recommended actions:

1. Memorise your master password.
2. Store a recovery copy securely if approved by your organisation.
3. Do not share your master password with anyone.
4. Do not send your master password to the administrator.

---

## Adding a New Password

1. Open the Vaultwarden web vault, app, or browser extension.
2. Select **New Item** or **Add Item**.
3. Choose **Login**.
4. Enter the website name.
5. Enter the username or email address.
6. Enter the password.
7. Add the website URL.
8. Save the item.

---

## Generating a Strong Password

When creating a new account online:

1. Open Bitwarden or Vaultwarden.
2. Use the password generator.
3. Generate a strong password.
4. Save the login item to your vault.

Recommended password settings:

```text
Length: 16 characters or more
Use uppercase letters: Yes
Use lowercase letters: Yes
Use numbers: Yes
Use special characters: Yes
```

---

## Using Autofill

After saving a login:

1. Go to the website login page.
2. Open the Bitwarden browser extension or mobile app.
3. Select the matching login.
4. Autofill the username and password.

If autofill does not work, copy and paste the username and password manually from your vault.

---

## Troubleshooting

### I cannot log in

Check that the app or browser extension is using the self-hosted server:

```text
https://vault.darol.club
```

If it is using the default Bitwarden cloud server, change it to **Self-hosted** and try again.

---

### I created an account but cannot see the organisation vault

Creating an account does not automatically add you to the organisation vault.

You must:

```text
[ ] Create your account
[ ] Enable MFA using Email or Duo
[ ] Send the registered email address to the administrator
[ ] Wait for the administrator invitation
[ ] Accept the invitation
```

---

### I created an account but cannot see it in the app

You may have created the account on the wrong server.

Check whether the app is connected to:

```text
https://vault.darol.club
```

If it is connected to the default Bitwarden cloud service, switch to **Self-hosted** and enter the correct server URL.

---

### I forgot my master password

Contact the administrator.

Be aware that the administrator may not be able to recover the existing vault contents. A reset may be required.

---

### I did not receive the MFA email

Check:

1. Your spam or junk folder.
2. That you are using the correct email address.
3. That you are logging in to:

   ```text
   https://vault.darol.club
   ```

4. Contact the administrator if the email still does not arrive.

---

### Duo is not working

Check:

1. Your phone has internet access.
2. Duo notifications are enabled.
3. You are using the correct Duo account.
4. The device time and date are correct.
5. Contact the administrator if Duo still fails.

---

### The site does not open

Check:

1. You are using the correct address:

   ```text
   https://vault.darol.club
   ```

2. Your internet connection is working.
3. The service is available.
4. You are not using an old or incorrect bookmark.

---

## Security Rules

Users must follow these rules:

1. Do not share your master password.
2. Do not store your master password inside the same vault.
3. Do not reuse passwords across multiple websites.
4. Lock your vault when not in use.
5. Report suspicious login prompts or unknown MFA requests.
6. Use the password generator for new passwords.
7. Keep the Bitwarden app and browser extension updated.
8. Enable MFA using Email or Duo.
9. Send only your registered email address to the administrator, never your password.

---

## User Completion Message Template

After creating your account and enabling MFA, send this message to the administrator:

```text
Hello,

I have created my Vaultwarden account and enabled MFA.

Email used for registration: user@example.com

Thank you.
```

Replace `user@example.com` with the actual email address used to create the account.

---

## Quick Setup Checklist

Use this checklist when setting up a new user:

```text
[ ] User opened https://vault.darol.club
[ ] User created a Vaultwarden account
[ ] User installed the Bitwarden app or browser extension
[ ] User changed the server option to Self-hosted
[ ] User entered https://vault.darol.club as the server URL
[ ] User logged in successfully
[ ] User enabled MFA using Email or Duo
[ ] User sent the registered email address to the administrator
[ ] Administrator invited the user into the organisation vault
[ ] User accepted the organisation invitation
[ ] User confirmed they can access the organisation vault
```

---

## Summary

To use the organisation Vaultwarden service:

1. Create an account at:

   ```text
   https://vault.darol.club
   ```

2. In the Bitwarden app or browser extension, select **Self-hosted** and use:

   ```text
   https://vault.darol.club
   ```

3. Enable MFA using **Email** or **Duo**.
4. Send the registered email address to the administrator.
5. Accept the organisation vault invitation.
