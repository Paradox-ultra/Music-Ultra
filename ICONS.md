# Bottom-bar outline icons

The final patch binds icons at both the initial tab ImageView assignment and the selection-refresh assignment. The refresh consumer reads icon maps directly, so changing only the provider is insufficient.

- Library: original outline bookmark, resource 0x7f08092f.
- Search: original outline magnifier, resource 0x7f080a65.
- Explore: original outline compass, resource 0x7f080956.

A provider-only candidate did not change the phone rendering. It is superseded and is not published as the latest release. The final bound-icon build was confirmed correct on the phone.
