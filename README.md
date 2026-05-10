# MITgcm Skill

Progressive-disclosure skill for the [MIT General Circulation Model](https://github.com/MITgcm/MITgcm) (MITgcm), a versatile finite-volume model that runs as ocean, atmosphere, sea-ice, or coupled configurations on a single dynamical core.

> **Skill author:** Koutian Wu (ktwu01@gmail.com)
> **Skill version:** 0.1.0-scaffold

## What This Is

A guide to setting up, building, running, and adjoint-ing MITgcm experiments. Covers the canonical experiment layout (`code/input/build/run`), the `genmake2` build system, the package (`pkg/`) opt-in mechanism, the namelist files (`data`, `data.pkg`, `eedata`), the verification regression suite, and the adjoint/ECCO workflow.

## Status

Scaffold. Layout and conventions source-grounded against the cloned `MITgcm/MITgcm` tree. This is one of the priority skills slated for full deep-dive after scaffold pass.

## License

MIT (skill content). MITgcm itself is MIT-licensed.
