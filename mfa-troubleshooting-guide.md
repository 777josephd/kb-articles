# MFA Troubleshooting Guide

**Audience:** All staff  
**Last updated:** 2026  
**Maintained by:** IT Help Desk

---

## What is MFA and why does it matter?

MFA stands for Multi-Factor Authentication. It is a second layer of security on top of your password. When you log in, MFA asks you to confirm your identity a second time — usually by entering a code from an app on your phone or receiving a text message.

This matters because passwords alone can be stolen. Even if someone gets your password, they cannot access your account without also having your phone. MFA is one of the most effective ways to protect your account and the organization's data.

---

## Common MFA Issues and How to Fix Them

### Issue 1: My authenticator app is not generating codes, or the codes are not working

This is almost always caused by your phone's clock being slightly off. Authenticator apps generate codes based on the current time — if your phone's clock is even a minute behind or ahead, the codes will not match and your login will fail.

**How to fix it:**

1. Open your phone's **Settings**
2. Go to **Date & Time** (on iPhone) or **Date & Time** (on Android under General Management)
3. Make sure **"Set Automatically"** or **"Automatic date & time"** is turned on
4. Close the settings and try generating a new code

If the codes still do not work after syncing your clock, contact the Help Desk.

---

### Issue 2: I got a new phone and lost access to my MFA app

If you got a new phone and did not transfer your MFA app before switching, you will not be able to generate codes for your account. **Do not try to log in repeatedly** — too many failed attempts may lock your account.

**What to do:**

Contact the Help Desk directly. We will verify your identity and walk you through re-enrolling your MFA. You will need to have your new phone with you and be available for a short call or chat session. If you have backup codes that were provided when you first set up MFA, have those ready — they can sometimes be used to regain access without Help Desk involvement.

---

### Issue 3: I am not receiving SMS verification codes

If you chose to receive MFA codes by text message and the texts are not arriving, start with these checks before calling in:

1. **Check your signal** — no signal means no texts. Try moving to an area with better reception.
2. **Check for Do Not Disturb mode** — your phone may be blocking incoming messages.
3. **Wait 2–3 minutes** — SMS codes can be delayed. Do not request a new code repeatedly, as this can temporarily block further attempts.
4. **Try a different network** — if you are on Wi-Fi calling, switch to cellular or vice versa.

If texts are consistently not arriving, the Help Desk can switch you to an authenticator app instead, which is more reliable and does not depend on cell service.

---

### Issue 4: I am being prompted for MFA every time I log in

In most cases, you should only be asked for MFA when you log in from a new device or after a period of inactivity. If you are being asked for MFA on every single login — even on your regular work computer — one of the following is likely happening:

- Your browser is set to clear cookies when it closes, which removes the "trusted device" record
- You are using a private or incognito browsing window
- Your organization's security policy requires MFA on every login (this is intentional, not a bug)

**Try this first:** Log in using a normal browser window (not incognito) and check whether your browser is set to clear history on close. If the issue continues, contact the Help Desk to confirm whether your account has a policy applied that requires step-up authentication each session.

---

## When to Contact the Help Desk

Contact us if:

- You are completely locked out and cannot access your account
- Your authenticator app is lost, deleted, or on a device you no longer have
- You have tried the steps above and the issue is not resolved
- You are seeing an error message you do not recognize

**Do not share your MFA codes with anyone — including Help Desk staff.** We will never ask for your code. We verify your identity other ways.

---

## What to have ready when you contact us

Having this information ready will speed up your support call:

- Your **full name** and **employee ID or username**
- The **device you use for MFA** (iPhone, Android, work laptop, etc.)
- The **error message** you are seeing, if any (a photo of the screen is helpful)
- Whether this worked before, and roughly **when it stopped working**
- Whether you recently got a new phone, changed your number, or reinstalled the app

The more detail you can provide upfront, the faster we can get you back in.
