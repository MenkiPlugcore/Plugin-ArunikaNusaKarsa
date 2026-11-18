# Nusa Karsa — one-file import

The repository is initialized but historical source/binaries are not imported yet.

1. Download the verified `ArunikaNusaKarsa-through-1.0.4.git.bundle` attachment from the chat.
2. Open https://github.com/MenkiPlugcore/Plugin-ArunikaNusaKarsa/upload/main
3. Drop the file into the root of the repository without renaming it, commit directly to main.
4. Open https://github.com/MenkiPlugcore/Plugin-ArunikaNusaKarsa/actions and check "Import verified Nusa Karsa history". If automatic execution is unavailable and Actions is enabled, run the workflow manually.

The workflow verifies SHA-256 `c1345b129b69b7d12cd5ddec2d1fdc1ac96a5fb6a24230696ea4ca883a090779`, fetches the reconstructed commits/tags, merges the source into main, removes the temporary bundle from the current tree and pushes all tags atomically. A local test imported 23 tags and all baseline files, but GitHub-hosted execution awaits the upload.

Expected baseline: v1.0.4 preview, Paper 1.21.11 / Java 21, 73 historical files, Java ItemsAdder models, Bedrock Geyser packs and mappings. Read the imported README and distribution/1.0.4/START-HERE.md before installation. Runtime testing is outstanding. Do not install standalone ArunikaWTB alongside the embedded module.
