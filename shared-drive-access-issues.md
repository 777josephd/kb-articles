# Shared Drive Access Issues

**Audience:** All staff  
**Last updated:** 2026  
**Maintained by:** IT Help Desk

---

## What is a shared drive?

A shared drive is a folder stored on a central server that multiple people can access, rather than a folder saved only on your personal computer. Shared drives are used to store team files, department documents, and resources that need to be available to a group of people.

You access a shared drive through File Explorer on Windows — it typically appears as a lettered drive (like `H:` or `S:`) under **This PC**.

---

## Common Reasons You May Lose Access

Shared drive access issues fall into a few predictable categories. Knowing which one applies to you helps the Help Desk resolve it faster.

**The drive mapping disappeared**
Drive mappings — the connection between the letter on your PC and the actual folder on the server — are applied automatically when you log in. Occasionally, a system update or policy change can cause these mappings to not apply correctly. The drive was not deleted; your computer just lost the shortcut to it.

**Your account permissions changed**
Access to shared drives is controlled by group membership. If your role changed, you were recently onboarded, or an administrator made a change to your account, your permissions may have been updated — intentionally or by mistake.

**You are not connected to the network or VPN**
Shared drives on a corporate server are only accessible when you are on the corporate network or connected through VPN. If you are working remotely and not connected to VPN, shared drives will appear disconnected or unavailable.

**The server or share is temporarily unavailable**
Less common, but possible. If multiple people report the same issue at the same time, this is likely the cause.

---

## What to Try Before Calling the Help Desk

**If you are working remotely:** Connect to VPN first, then check whether the drive reappears. This resolves the issue in many remote work cases.

**If you are in the office or already on VPN:**

1. Open **File Explorer** and click **This PC**
2. Check whether the drive letter appears but shows as disconnected (a red X icon)
3. If so, double-click the drive — it will attempt to reconnect
4. If the drive letter is gone entirely, right-click **This PC**, select **Map network drive**, and re-enter the path provided by IT

**If remapping does not work or you receive an access denied error:**
This indicates a permissions issue that requires Help Desk involvement. Do not attempt to work around it — contact us directly.

---

## What an "Access Denied" Error Means

An access denied message means your account does not currently have permission to open that folder. This is not a technical glitch — it means the system is working correctly and your account simply is not on the access list.

This happens most often when:
- You are new to the team and permissions have not been set up yet
- You are trying to access a folder outside your department's scope
- Your account was recently modified and something was inadvertently removed

In all of these cases, the Help Desk will need to verify what access you should have and request the appropriate permissions on your behalf.

---

## When to Contact the Help Desk

- The drive is missing and remapping it does not work
- You receive an "access denied" error
- The drive was working yesterday and nothing has changed on your end
- Multiple people on your team have lost access at the same time
- You need access to a new shared folder that was recently created

---

## What to have ready when you contact us

- Your **full name** and **employee ID or username**
- The **drive letter or path** you are trying to access (for example: `S:\Finance\Reports` or `\\server01\shared`)
- The **exact error message** you are seeing
- Whether you are working **in the office or remotely**
- Whether this **worked before**, and roughly when it stopped
- Whether **anyone else on your team** is experiencing the same issue
