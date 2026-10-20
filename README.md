# Ripple source snapshots

Download the versioned source archive from [Build 63](https://github.com/PlasticBuild/Ripple-AI-public-source/releases/tag/build63-vc143). The APK-only download repository is [Ripple-AI](https://github.com/PlasticBuild/Ripple-AI).

Extract the 7z archive with NanaZip/7-Zip. Read README.md, BUILD63-BACKUP.md, RECOVERED-BUILD61.md and recovery/RECOVERY-RUNNER.txt inside it. Build with JDK21, Android platform37.1, Build Tools36.0.0 and the checksum-pinned Gradle wrapper. The recovery runner produces an unsigned APK; signing keys and passwords are excluded.

This is the complete available working source snapshot for the published Java/Kotlin app. Imported original Build61 native bytes remain pinned; rebuilding those bytes identically from the reconstructed native sources is not proven. Existing upstream licenses, notices and historical evidence are retained. Archive integrity, app-build checks and device tests do not establish native source equivalence or NPU performance.
