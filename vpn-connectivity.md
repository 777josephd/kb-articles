# VPN Connectivity FAQ

**Audience:** All staff  
**Last updated:** 2026  
**Maintained by:** IT Help Desk

---

## Why do I need a VPN?

VPN stands for Virtual Private Network. When you work outside the office — from home, a coffee shop, or while traveling — your connection to the internet is not automatically secure or private. A VPN creates an encrypted tunnel between your device and the organization's network, so your work traffic is protected and you can access internal resources (shared drives, internal websites, printers) as if you were sitting in the office.

If you are working remotely and cannot access something that works fine when you are on-site, connecting to the VPN is usually the first step.

---

## Common VPN Issues and Solutions

### Issue 1: VPN won't connect at all

If the VPN client is not connecting at all, work through these steps before calling in:

1. **Check your internet connection** — open a website in your browser. If the internet itself is not working, the VPN cannot connect either. Restart your router if needed.
2. **Restart the VPN client** — close the application completely and reopen it.
3. **Restart your computer** — this clears many temporary connection issues.
4. **Check for a firewall or antivirus blocking the connection** — some security software blocks VPN traffic. If you recently installed new software, that may be the cause.

If none of these work, contact the Help Desk with the exact error message you are seeing.

---

### Issue 2: VPN connects but I can't access internal resources

This is a common issue and it does not always mean something is wrong with the VPN itself. When your VPN connects, your computer sometimes holds onto old network information and does not immediately know how to find internal addresses correctly.

**Try this first:**

1. **Disconnect from the VPN completely**, wait 30 seconds, then reconnect
2. If that does not work, **restart the VPN client** entirely
3. If you are trying to reach a specific internal website or shared drive by name (not an IP address), try restarting your computer after reconnecting — this gives your system a fresh start on looking up internal addresses

If only one specific resource is unavailable (for example, one shared drive but not others), it may be a permissions issue rather than a VPN issue. Let the Help Desk know exactly what you are trying to reach.

---

### Issue 3: VPN keeps disconnecting randomly

Frequent random disconnects are frustrating and usually come down to one of two causes: an unstable internet connection, or a clock sync problem.

**Check your internet first:**
- If you are on Wi-Fi, try moving closer to your router or switching to a wired connection
- Run a quick speed test at fast.com — if speeds are inconsistent, your internet connection is the likely cause

**Check your computer's clock:**
- Your VPN uses your computer's time as part of how it verifies your identity securely. If your clock is even slightly off, the VPN may periodically fail that check and drop the connection.
- Go to your computer's **Date & Time settings** and make sure the time is set to **update automatically**. On Windows: Settings → Time & Language → Date & Time → toggle "Set time automatically" to On. On Mac: System Settings → General → Date & Time → toggle "Set automatically."

If disconnects continue after both checks, contact the Help Desk.

---

### Issue 4: VPN is slow

A VPN will always add some overhead to your connection — all your traffic is being routed through an extra layer of security. Some slowness is expected. But if things feel unusably slow, try the following:

1. **Test your base internet speed** without the VPN at fast.com — if your internet is already slow, the VPN will make it worse
2. **Close applications you are not using** — video calls, large file syncs, and streaming services use significant bandwidth
3. **Check if your VPN client has a server location setting** — if you are connecting to a server in a different region than necessary, switching to a closer server can improve speed
4. **Restart your router** — this often resolves slowness caused by an overloaded local connection

If speed issues are severe and consistent, report it to the Help Desk. We can check whether there is a broader issue affecting other users.

---

## Before You Call the Help Desk — Quick Checklist

Running through this before you call will speed up your support session significantly. Check each item:

- [ ] Is your basic internet working? (Can you open google.com without the VPN?)
- [ ] Are you on Wi-Fi or a wired connection?
- [ ] Have you tried restarting the VPN client?
- [ ] Have you restarted your computer?
- [ ] What is the exact error message you are seeing? (Take a photo or write it down)
- [ ] Has the VPN worked for you before, or is this the first time you are trying to connect?
- [ ] Did anything change recently — new laptop, new network, new location?

The more of these you can answer, the faster we can identify the issue.

---

## What to tell the Help Desk when you call

When you reach us, please have the following ready:

- Your **full name** and **employee ID or username**
- The **device you are using** (work laptop, personal laptop, etc.) and the **operating system** (Windows 10, Windows 11, Mac)
- The **VPN client name** if you know it (for example: Cisco AnyConnect, GlobalProtect, Pulse Secure)
- The **exact error message** you are seeing
- Whether you are on **Wi-Fi or wired**, and whether the issue happens in all locations or just one
- **When it last worked**, if it has worked before

This information lets us skip the basic questions and get straight to solving the problem.
