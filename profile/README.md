<div align="center">
  <img height="200" src="https://raw.githubusercontent.com/changelog-bot/.github/main/assets/logo.svg"  />
</div>
<h1 align="center">Changelog Bot</h1>
<p align="left">Discord bot for changelog with dashboard and support for editing, multiple projects, images, logos and themes.</p>

```mermaid
flowchart BT
    database[(Database)]--->bot(Bot)
    database[(Database)]--->api(Api)
    localization[(Localization)]--->bot(Bot)
    localization[(Localization)]~~~~site(Site)
    localization[(Localization)]--->dashboard(Dashboard)
    api{Api}--->dashboard(Dashboard)
```
##
<div align="center">
  <img height="150" src="https://moe-counter.glitch.me/get/@changelog-bot?theme=gelbooru"  />
</div>
