# TODO, MITgcm skill

## Tier B
- [ ] List of major packages: gmredi, kpp, seaice, thsice, ptracers, gchem, exf, cal, diagnostics
- [ ] Standard ocean configurations: global 1°, regional, channel
- [ ] Standard atmospheric / "atm-mit" configurations
- [ ] Diagnostic output via `pkg/diagnostics` and `data.diagnostics`
- [ ] Optfile naming convention (`linux_amd64_gfortran`, `darwin_*`, ...)

## Tier C
- [ ] Common build failures (NetCDF version, pkg ordering)
- [ ] Verification suite usage: `testreport.py`
- [ ] Debugging dead bottoms / NaN propagation
- [ ] Adjoint workflow: TAF licensing, runtime patterns, ECCO conventions
- [ ] Forward / Adjoint memory considerations (`maxstor`, checkpoints)

## Verification
- [ ] Cite Marshall et al. 1997 (a, b)
- [ ] Gemini critique pass
