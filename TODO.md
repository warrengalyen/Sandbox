## Immediate Todo
1. Redo layout
    * Fix scrollbar being weird
2. Clean up main.rs - Move things into separate functions/files, add comments

## Later Todo
1. Make particles move left/right randomly when they can do either
2. Fix to Electricity getting stuck with 1 particle of water in mid-air
3. Make Fire not spread so fast when starting from the top/left
4. Replace simdnoise and flume with a shader
---
5. Update to flatpak to 20.08 and remove Cargo.toml hacks
6. Add back support for wayland when less buggy (missing virtual keycodes, slow input events infinitely triggering, buggy fullscreen toggling on gnome, buggy decorations)
7. Replace heap_array.rs with 'placement new' when it gets added to rust
---
8. Save/Load simulations with files
9. MISX package
10. Mobile linux
11. WASM

## Release Procedure
1. Bump Cargo.toml version
2. Update CHANGELOG.md
3. Add another release element to flatpak/com.mechanikadesign.Sandbox.metainfo
4. Update flatpak to 20.08 and remove Cargo.toml hacks
5. Add back support for wayland when less buggy
6. Tag git commit
7. Update flathub repo