# API

```@meta
CurrentModule = CLIMAParameters
```

## Types

```@docs
AbstractParameterSet
AbstractEarthParameterSet
AbstractMicrophysicsParameterSet
AbstractCloudParameterSet
AbstractPrecipParameterSet
AbstractLiquidParameterSet
AbstractIceParameterSet
AbstractRainParameterSet
AbstractSnowParameterSet
```

## Universal Constants

```@docs
gas_constant
light_speed
h_Planck
k_Boltzmann
Stefan
astro_unit
avogad
```

## Planet

```@docs
Planet
Planet.molmass_dryair
Planet.R_d
Planet.kappa_d
Planet.cp_d
Planet.cv_d
Planet.ρ_cloud_liq
Planet.ρ_cloud_ice
Planet.molmass_water
Planet.molmass_ratio
Planet.R_v
Planet.cp_v
Planet.cp_l
Planet.cp_i
Planet.cv_v
Planet.cv_l
Planet.cv_i
Planet.T_freeze
Planet.T_min
Planet.T_max
Planet.T_icenuc
Planet.T_triple
Planet.T_0
Planet.LH_v0
Planet.LH_s0
Planet.LH_f0
Planet.e_int_v0
Planet.e_int_i0
Planet.press_triple
Planet.ρ_ocean
Planet.cp_ocean
Planet.planet_radius
Planet.day
Planet.Omega
Planet.grav
Planet.year_anom
Planet.orbit_semimaj
Planet.tot_solar_irrad
Planet.epoch
Planet.mean_anom_epoch
Planet.obliq_epoch
Planet.lon_perihelion_epoch
Planet.eccentricity_epoch
Planet.lon_perihelion
Planet.MSLP
Planet.T_surf_ref
Planet.T_min_ref
```

## Common

### Sub-grid scale

```@docs
SubgridScale
SubgridScale.von_karman_const
```

### Surface fluxes and universal functions

```@docs
SurfaceFluxes
SurfaceFluxes.UniversalFunctions
SurfaceFluxes.UniversalFunctions.Pr_0_Businger
SurfaceFluxes.UniversalFunctions.a_m_Businger
SurfaceFluxes.UniversalFunctions.a_h_Businger
SurfaceFluxes.UniversalFunctions.Pr_0_Gryanik
SurfaceFluxes.UniversalFunctions.a_m_Gryanik
SurfaceFluxes.UniversalFunctions.a_h_Gryanik
SurfaceFluxes.UniversalFunctions.b_m_Gryanik
SurfaceFluxes.UniversalFunctions.b_h_Gryanik
SurfaceFluxes.UniversalFunctions.Pr_0_Grachev
SurfaceFluxes.UniversalFunctions.a_m_Grachev
SurfaceFluxes.UniversalFunctions.a_h_Grachev
SurfaceFluxes.UniversalFunctions.b_m_Grachev
SurfaceFluxes.UniversalFunctions.b_h_Grachev
SurfaceFluxes.UniversalFunctions.c_h_Grachev
```

## Atmos

```@docs
Atmos
```

### Sub-grid scale

```@docs
Atmos.SubgridScale.C_smag
Atmos.SubgridScale.C_drag
Atmos.SubgridScale.inv_Pr_turb
Atmos.SubgridScale.Prandtl_air
Atmos.SubgridScale.c_a_KASM
Atmos.SubgridScale.c_e1_KASM
Atmos.SubgridScale.c_e2_KASM
Atmos.SubgridScale.c_1_KASM
Atmos.SubgridScale.c_2_KASM
Atmos.SubgridScale.c_3_KASM
```

### EDMF

```@docs
Atmos.EDMF.c_λ
Atmos.EDMF.c_ε
Atmos.EDMF.c_δ
Atmos.EDMF.c_t
Atmos.EDMF.β
Atmos.EDMF.μ_0
Atmos.EDMF.χ
Atmos.EDMF.w_min
Atmos.EDMF.lim_ϵ
Atmos.EDMF.lim_amp
Atmos.EDMF.a_min
Atmos.EDMF.a_surf
Atmos.EDMF.κ_star²
Atmos.EDMF.ψϕ_stab
Atmos.EDMF.α_d
Atmos.EDMF.α_a
Atmos.EDMF.α_b
Atmos.EDMF.H_up_min
Atmos.EDMF.c_d
Atmos.EDMF.c_m
Atmos.EDMF.c_b
Atmos.EDMF.a1
Atmos.EDMF.a2
Atmos.EDMF.ω_pr
Atmos.EDMF.Pr_n
Atmos.EDMF.Ri_c
Atmos.EDMF.smin_ub
Atmos.EDMF.smin_rm
```

### Microphysics_0M

```@docs
Atmos.Microphysics_0M.τ_precip
Atmos.Microphysics_0M.qc_0
Atmos.Microphysics_0M.S_0
```

### Microphysics

Please see the microphysics [documentation](https://clima.github.io/ClimateMachine.jl/latest/Theory/Atmos/Microphysics/) for an explanation of the default values.

```@docs
Atmos.Microphysics.n0
Atmos.Microphysics.μ_sno
Atmos.Microphysics.ν_sno
Atmos.Microphysics.r0
Atmos.Microphysics.m0
Atmos.Microphysics.χm
Atmos.Microphysics.me
Atmos.Microphysics.Δm
Atmos.Microphysics.a0
Atmos.Microphysics.χa
Atmos.Microphysics.ae
Atmos.Microphysics.Δa
Atmos.Microphysics.v0
Atmos.Microphysics.χv
Atmos.Microphysics.ve
Atmos.Microphysics.Δv
Atmos.Microphysics.C_drag
Atmos.Microphysics.τ_cond_evap
Atmos.Microphysics.τ_sub_dep
Atmos.Microphysics.q_liq_threshold
Atmos.Microphysics.τ_acnv
Atmos.Microphysics.r_ice_snow
Atmos.Microphysics.E
Atmos.Microphysics.a_vent
Atmos.Microphysics.b_vent
Atmos.Microphysics.K_therm
Atmos.Microphysics.D_vapor
Atmos.Microphysics.ν_air
Atmos.Microphysics.N_Sc
```
