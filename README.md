# Pocket Recovery runtime distribution

Public runtime assets only. Source code lives in the private pocket-recovery repository.
Android 0.1.2: `code/0.1.2/Android/DefaultPackage.version`.
GitHub Pages serves this directory. Publish bundles and manifests atomically in one commit.
Preserve prior hashed bundles for installed clients. Never mix AOT metadata across player versions.
The Android APK contains no YooAsset game bundles; first launch requires a successful download.
