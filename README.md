# Spawny

Spawny is a macOS app for hosting a Minecraft server on your own Mac. Set up a server for Java Edition, Bedrock Edition, or both, then share the addresses your friends need to join.

**[Download Spawny 1.1.9 for Apple silicon](https://github.com/ujjwal-poudel/Spawny/releases/download/v1.1.9/Spawny-1.1.9.zip)** · [All releases](https://github.com/ujjwal-poudel/Spawny/releases)

This preview requires an Apple silicon Mac with macOS 14 Sonoma or later. Setup requires internet access. Spawny runs the server on your Mac, so keep your Mac awake and the server running while friends are playing.

## What Spawny simplifies

- **Install the server and its dependencies.** Pick a Minecraft version and which editions your friends play. Spawny installs Paper and can download a compatible Java runtime. For Bedrock and crossplay, it also sets up Geyser and Floodgate.
- **Invite players outside your Wi-Fi.** Link a playit.gg account during setup. Spawny uses playit tunnels so you can share a server without configuring port forwarding on your router. It checks the selected editions and shows the addresses when sharing is ready.
- **Manage the server from your Mac.** Start or stop the server from the dashboard, review join requests, manage the player list, and switch between saved servers. Use the Backups tab to back up or restore a world.

## Install and start playing

1. Download `Spawny-1.1.9.zip` from the release assets above. Unzip it, drag `Spawny.app` to **Applications**, and open it.
2. Click **Get started**. Name the server, choose **Java only**, **Bedrock only**, or **Both (crossplay)**, and follow the setup screens. Review and accept the Minecraft server EULA if you agree.
3. Follow the prompts to link your playit.gg account. If you selected Bedrock or crossplay, open the assigned Bedrock tunnel in playit, choose **Origin Configuration**, copy the **NetherNet token**, and paste it into Spawny. Keep that token private.
4. Once the dashboard shows sharing is ready, click **Copy invite** for the edition your friend uses. Java players can paste the address in **Multiplayer → Add Server**. Bedrock players whose client supports adding external servers can enter the address and port under **Play → Servers → Add Server**. Console menus can differ by platform.
5. When a new player requests access, review the request in Spawny and approve it if you recognize them. Use **Stop server** in the dashboard when you are done hosting.

The preview uses an ad-hoc signature and has not been notarized by Apple. macOS may block it on first launch. See [Apple’s first-launch guidance](https://support.apple.com/en-us/102445).

## Updates and feedback

Download new builds from [Releases](https://github.com/ujjwal-poudel/Spawny/releases). To report a problem, open an [issue](https://github.com/ujjwal-poudel/Spawny/issues/new) with your macOS version, Spawny version, Minecraft edition, and the step where it occurred. Keep tokens and account details out of your report.

See [third-party notices](THIRD-PARTY-NOTICES.txt) for bundled components.
