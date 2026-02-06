# Account & Region Selection

## Connecting Your Roblox Account

Connecting your account unlocks region selection, recent games on the [Quickplay](/guide/quickplay) page, and authenticated API features. Head to the **Account** page.

![Account page showing connection options](/images/account/sign-in.png)

### Sign in with Browser (Recommended)

Click **Sign in with Browser**. A native login window opens showing the Roblox website. Log in as you normally would. The cookie is automatically extracted and stored in your macOS Keychain when you complete the login. The window closes on its own.

![Browser login window](/images/account/browser-login.png)

### Manual Cookie Entry

If the browser method doesn't work, click **Manual Cookie Entry**, paste your `.ROBLOSECURITY` cookie, and it will be validated against the Roblox API before being saved.

<img src="/images/account/cookie-entry.png" alt="Manual cookie entry dialog" width="530">

### Connected State

Once connected, the Account page shows your avatar, display name, and username. You can refresh validation or remove your account at any time.

![Account page when connected](/images/account/connected.png)

If your cookie expires, the Account page shows an "Expired" badge. Just sign in again.

### Security

- Your cookie is stored in the **macOS Keychain** (encrypted, local to your device).
- It is only ever sent to `roblox.com` domains.
- No admin account is required. Any Roblox account works.
- The browser login uses a non-persistent session, so no data lingers after closing.
- Cookies are automatically redacted from log files.

## Region Selection

Region selection lets you pick which geographic region to join game servers in, useful for lower ping or playing with friends in a specific area.

![Region selection panel on the Account page](/images/account/region-selection.png)

### Setup

1. Connect your Roblox account.
2. Go to **Account** and enable **Region Selection**.
3. Accept the data contribution agreement (anonymous server data shared with the RoValra database to improve region accuracy for everyone).
4. Pick your preferred region from the dropdown (US East, US West, EU Central, Asia, etc.) or leave it on **Auto**.

When you join a game, AppleBlox automatically finds a server in your preferred region. If it can't find one, it falls back to Roblox's default server assignment. A notification tells you which region you connected to.

<img src="/images/account/region-notification.png" alt="Region notification" width="350">

::: tip
Not all games have servers in every region. Server availability depends on the game's popularity and Roblox's infrastructure.
:::
