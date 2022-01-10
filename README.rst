MineOS Turnkey - Debian GNU/Linux with MineOS Web User Interface
=======================================================

Based on the proven Debian foundation, Turnkey Linux is a perfect delivery system: a trimmed, yet supremely extensible server platform. Respun with MineOS components pre-configured, MineOS Turnkey is the quickest way to get a managed hosting platform for Minecraft, capable of starting/stopping, backing up, restoring, and archiving your worlds.

Features:

- **Base Operating System**: Debian GNU/Linux 10 (Bullseye).

- **Web management interface** (MineOS):
   
  - Listens on port 8443 (uses HTTPS).
  - Many server types to choose from, e.g., Vanilla, FTB, Spigot, Pocketmine

- **First boot initialization**:
   
  - Prompt user for passwords for user `root` and `mc`
  - Regenerates SSL and SSH cryptographic keys.
  - Installs latest security updates, unless user chooses to defer this
    for later.
