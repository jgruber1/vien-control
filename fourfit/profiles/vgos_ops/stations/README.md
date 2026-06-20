# Fourfit station fragments for VIN / vien-control

These files were generated from the uploaded `vo6147.cf` control file.

Each `<station>.cf` file contains the active `if station <X>` blocks found in the source file, including station-specific `pc_tonemask`, `weak_channel`, `sampler_delay_x/y`, `pc_phases_x/y`, `pc_delay_x/y`, and `pc_phase_offset_x/y` where present.

Notes:
- Stations `W` and `P` contain sampler-delay blocks in the source file, but no generated `pc_phases` / `pc_delay` blocks.
- Baseline-specific blocks such as `ST` and `WV` are intentionally not included here; they should live under `baselines/`.
- Global parameters should live in a separate profile-level `global.cf`.
