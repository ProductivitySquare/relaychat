# RelayChat

Private one-to-one chat for Windows. No accounts, no history, end-to-end encrypted. When one person leaves, the conversation is wiped for both.

**Free beta. Not independently audited.**

## Download

Open [Releases](../../releases) and download `relaychat-0.1.0.exe`.

## Verify the file

SHA-256 of `relaychat-0.1.0.exe`:

    95D71962D10E852CE1ED81A2B079CC745406786FBADE8F9A5787653BEE3F6429

In PowerShell, from the folder where you saved it:

    Get-FileHash .\relaychat*.exe -Algorithm SHA256

If the result does not match, do not run the file. Windows may show "Windows protected your PC" because the app is not signed with a paid certificate yet. If the fingerprint matched, click More info, then Run anyway.
