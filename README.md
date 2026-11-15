<p align="center">
  <img src="docs/media/banner.webp" alt="MC Rust Edition, a community fork of Horizon" width="100%">
</p>

<p align="center">
  <b>MC Rust Edition — a community-maintained fork of Horizon.</b><br>
  A native Rust client for Minecraft: Java Edition 26.3, built on the MIT-licensed Horizon codebase.
</p>

<p align="center">
  <a href="https://github.com/kritikakumari0972-bit/mc-rust/releases"><b>Fork releases</b></a> ·
  <a href="https://github.com/kritikakumari0972-bit/mc-rust/actions"><b>Builds</b></a> ·
  <a href="https://github.com/horizon-rust/horizon"><b>Original Horizon project</b></a>
</p>

<p align="center">
  <a href="https://github.com/kritikakumari0972-bit/mc-rust/stargazers"><img src="https://img.shields.io/github/stars/kritikakumari0972-bit/mc-rust?style=flat&color=F0795A" alt="MC Rust Edition stars"></a>
  <a href="https://discord.gg/playhorizon"><img src="https://img.shields.io/discord/1559227979002028052?label=Upstream%20Discord&logo=discord&logoColor=white&color=5865F2" alt="Upstream Horizon Discord"></a>
  <a href="https://github.com/kritikakumari0972-bit/mc-rust/graphs/contributors"><img src="https://img.shields.io/github/contributors/kritikakumari0972-bit/mc-rust?color=2EA44F" alt="MC Rust Edition contributors"></a>
  <a href="LICENSE"><img src="https://img.shields.io/badge/licence-MIT-blue" alt="MIT licence"></a>
</p>

> **Fork status:** This repository is based on [horizon-rust/horizon](https://github.com/horizon-rust/horizon). The engine, launcher architecture, and original contributor credits remain from that upstream project; this is not a clean-room rewrite. Fork-specific signed releases and automatic updates are not configured yet. The launcher currently reads upstream signed builds until this fork has its own release-signing key.

<p align="center">
  <a href="https://playhorizon.dev"><b>Website</b></a> ·
  <a href="https://playhorizon.dev/docs/"><b>Docs</b></a> ·
  <a href="https://playhorizon.dev/docs/install"><b>Install guide</b></a> ·
  <a href="https://discord.gg/playhorizon"><b>Discord</b></a> ·
  <a href="ROADMAP.md"><b>Roadmap</b></a>
</p>

<p align="center">
  <img src="docs/media/readme/valley.webp" alt="A river valley with a plains village, savanna hills and a cherry grove, seen from above with a long view distance" width="100%">
</p>

<p align="center">
  <img src="docs/media/readme/panel-worlds.webp" alt="Your worlds, same rules: survival, creative and hardcore, and your saves open as they are" width="49%">
  <img src="docs/media/readme/panel-together.webp" alt="Play together: vanilla and Horizon servers, LAN, or a code from a friend" width="49%">
</p>

<p align="center">
  <img src="docs/media/readme/panel-farther.webp" alt="See farther: terrain up to 1,024 chunks away, HDR and controllers" width="49%">
  <img src="docs/media/readme/panel-dimensions.webp" alt="Every dimension: vanilla world generation, mobs, villagers and redstone" width="49%">
</p>

<p align="center">
  <img src="docs/media/readme/panel-terrain.webp" alt="Same terrain: vanilla world generation, here a savanna village from above" width="49%">
  <img src="docs/media/readme/panel-mobs.webp" alt="Same mobs: attributes, spawn rules and mob AI match vanilla, here a baby piglin" width="49%">
</p>

<p align="center">
  <b>On the roadmap:</b> play in your browser · Android and iOS with mods · splitscreen · <a href="ROADMAP.md">see the roadmap</a>
</p>

<p align="center">
  <img src="docs/media/readme/signs-row.webp" alt="A voxel dragon in welding goggles points at three wooden signs: 3.5x faster start than modded Java, 38 percent more FPS than Java with Sodium, and a mod API to port your mods to Rust" width="100%">
</p>

<p align="center">
  <sub>Against Java Edition with Sodium, Lithium, FerriteCore and ImmediatelyFast on a Ryzen 7 9800X3D with an RTX 5080: the title screen in about 3 seconds instead of 11, and 31 to 38 percent more frames per second across render distances.</sub>
</p>

<h2 align="center">Original Horizon Team (upstream credits)</h2>

<table align="center">
  <tr>
    <td align="center" width="140"><a href="https://github.com/kacpherek"><img src="https://github.com/kacpherek.png?size=160" width="80" alt="Kacper"><br><b>Kacper</b></a></td>
    <td align="center" width="140"><a href="https://github.com/Online5277"><img src="https://github.com/Online5277.png?size=160" width="80" alt="Cosmic"><br><b>Cosmic</b></a></td>
    <td align="center" width="140"><a href="https://github.com/levzzz5154"><img src="https://github.com/levzzz5154.png?size=160" width="80" alt="levzzz"><br><b>levzzz</b></a></td>
    <td align="center" width="140"><a href="https://github.com/rdbtCVS"><img src="https://github.com/rdbtCVS.png?size=160" width="80" alt="rdbt"><br><b>rdbt</b></a></td>
    <td align="center" width="140"><a href="https://github.com/dezer-x"><img src="https://github.com/dezer-x.png?size=160" width="80" alt="Anthony S"><br><b>Anthony S</b></a></td>
    <td align="center" width="140"><a href="https://github.com/ludovic111"><img src="https://github.com/ludovic111.png?size=160" width="80" alt="Ludovic Marie"><br><b>Ludovic Marie</b></a><br><sub>Founder</sub></td>
  </tr>
</table>

<p align="center">
  <sub>and everyone who has contributed</sub><br><br>
  <a href="https://github.com/horizon-rust/horizon/graphs/contributors"><img src="https://contrib.rocks/image?repo=horizon-rust/horizon&max=72&columns=12" alt="Everyone who has contributed to Horizon"></a>
</p>

<p align="center">
  <a href="docs/native-client.md#run-from-a-checkout"><b>Build guide</b></a> ·
  <a href="CONTRIBUTING.md"><b>Contributing</b></a> ·
  <a href="GOVERNANCE.md"><b>Governance</b></a> ·
  <a href="https://discord.gg/playhorizon"><b>Discord</b></a>
</p>

<sub>Horizon is released under the [MIT licence](LICENSE) for the project's original work; dependencies keep their own licences, see the [notices](THIRD_PARTY_NOTICES.md). Founded by [Ludovic Marie](https://lu4ovic.com) and built by the Horizon Team and [its contributors](https://github.com/horizon-rust/horizon/graphs/contributors). You can support it on [GitHub Sponsors](https://github.com/sponsors/ludovic111).</sub>

<sub>NOT AN OFFICIAL MINECRAFT PRODUCT. NOT APPROVED BY OR ASSOCIATED WITH MOJANG OR MICROSOFT. Minecraft is a trademark of Mojang Synergies AB; its code and assets belong to Mojang and Microsoft under the [Minecraft EULA](https://www.minecraft.net/en-us/eula).</sub>
