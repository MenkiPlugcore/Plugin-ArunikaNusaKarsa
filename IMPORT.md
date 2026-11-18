# ARUNIKA — Nusa Karsa

Repository initialization for import of v0.1.0–v1.0.4 (preview), Paper 1.21.11 / Java 21.

The Git bundle delivered in the chat contains 23 reconstructed release tags and 73 original archive files. Download `ArunikaNusaKarsa-through-1.0.4.git.bundle`, then run in the download directory:

```sh
git clone -b main ArunikaNusaKarsa-through-1.0.4.git.bundle Plugin-ArunikaNusaKarsa
cd Plugin-ArunikaNusaKarsa
git remote set-url origin https://github.com/MenkiPlugcore/Plugin-ArunikaNusaKarsa.git
git fetch origin main
git merge --allow-unrelated-histories origin/main -m "Merge GitHub initialization"
git push origin main --tags
```

If Git requests identity or authentication, configure your normal GitHub Git credentials first. Do not use force-push.

Once imported, `main` contains the 1.0.4 editable source, archived release files, Java ItemsAdder rune/book models, Bedrock Geyser packs and mappings, and deployment documentation. v0.5.7 is an asset-only update. v1.0.5 is not included.

This initialization commit does not contain the source or binaries. Preview builds require real Paper, Vault, and Geyser/Floodgate runtime testing. Back up all plugin/WTB/economy data. Do not run a standalone ArunikaWTB JAR alongside the embedded module.
