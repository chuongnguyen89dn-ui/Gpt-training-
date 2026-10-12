# DEB / IPA skill

- Distinguish jailbreak rootless/rootful, CPU architecture, iOS version, package layout, dependencies and signing constraints.
- For DEB inspect control metadata, package contents, maintainer scripts, entitlements and binary compatibility; keep original UI/features unless change requested.
- For IPA inspect build system, provisioning/signing, entitlements, dependency versions and artifacts.
- Use actual available toolchain; do not claim iOS build or CarPlay functional test without proof.
- Track states separately: code changed → commit → workflow → artifact → release/Sileo → installed → real-device tested.
- Prefer existing working build workflow and artifacts; avoid restarting from scratch.
