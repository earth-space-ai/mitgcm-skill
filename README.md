# MITgcm Skill

Progressive-disclosure skill for the [MIT General Circulation Model](https://github.com/MITgcm/MITgcm) (MITgcm), a versatile finite-volume model that runs as ocean, atmosphere, sea-ice, or coupled configurations on a single dynamical core.

> **Skill author:** Koutian Wu (ktwu01@gmail.com)
> **Skill version:** 0.1.0-scaffold

> ⚠️ **Disclaimer — please read before using this skill.**
> This skill is **not a gold-standard reference**. It is a helper that lowers
> the barrier for new users to **get their hands dirty** with the model. AI
> agents (and the humans drafting this material) make mistakes; commands, file
> paths, namelist options, and physics explanations here can be wrong,
> incomplete, or out of date. **Always cross-check with the official model
> documentation, the source code, and a human expert before trusting any
> output for research, publication, or operational use.**

## What This Is

A guide to setting up, building, running, and adjoint-ing MITgcm experiments. Covers the canonical experiment layout (`code/input/build/run`), the `genmake2` build system, the package (`pkg/`) opt-in mechanism, the namelist files (`data`, `data.pkg`, `eedata`), the verification regression suite, and the adjoint/ECCO workflow.

## Status

Scaffold. Layout and conventions source-grounded against the cloned `MITgcm/MITgcm` tree. This is one of the priority skills slated for full deep-dive after scaffold pass.

## Acknowledgments

**Gold-standard references for MITgcm** (use these to cross-check anything in this skill):
- MITgcm user manual: https://mitgcm.readthedocs.io/
- MITgcm/MITgcm repository: https://github.com/MITgcm/MITgcm
- MITgcm project page: https://mitgcm.org/
- ECCO portal (adjoint / state estimation): https://www.ecco-group.org/

This scaffold exists only because of the work of other people, and any value
it has is borrowed from theirs.

- The **MIT EAPS group** and the broader MITgcm developer community for
  building and maintaining [MITgcm/MITgcm](https://github.com/MITgcm/MITgcm),
  the `genmake2` build system, the `pkg/` opt-in mechanism, the verification
  regression suite, and the manual at https://mitgcm.readthedocs.io/.
- The **ECCO consortium** for the adjoint / state-estimation workflow that
  the adjoint section of this skill is built around.
- **Zesen Huang** for [laps-skill](https://github.com/huangzesen/laps-skill),
  the progressive-disclosure layout this repo borrows.

Any errors, oversimplifications, or out-of-date claims in this skill are the
skill author's responsibility, not the upstream community's. This is a
scaffold; operational depth is being filled in iteratively.

## License

MIT (skill content). MITgcm itself is MIT-licensed.
