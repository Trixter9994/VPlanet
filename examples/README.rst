VPLanet Examples
================

This subdirectory contains examples of numerous ways to use `VPLanet`. A brief
description of each is provided below, arranged by topic [with modules listed in brackets]. Click on the directory to see VPLanet input files, Python scripts,
plots, and more description of the physics. Use these VPLanet input files and Python scripts to reproduce published figures, or as a starting point to begin your own fundamental research. The simulations used to generate these figures are `validated with continuous integration <../tests>`_ with the identical (or representative, in the case of parameter sweeps) initial conditions. Looking for something not present? E-mail Rory Barnes, rory@astro.washington.edu, to inquire if that functionality is available and validated.

To run the Python scripts and generate the figures in the subdirectories, you must install `vplot <https://github.com/VirtualPlanetaryLaboratory/vplot>`_. Note, however, that you can run VPLanet with installing vplot and use your preferred method to visualize the output.

**Atmospheric Escape**
===============

`AbioticO2 <AbioticO2>`_: Production of abiotic oxygen on terrestrial worlds due to water photolyzation and hydrogen escape. [AtmEsc, STELLAR]

`AtmEscKepler-36 <AtMescKepler-36>`_: Energy-limited hydrogen envelope loss due to stellar XUV flux. [AtmEsc, STELLAR]

`AtmEscRegimes <AtmEscRegimes>`_: Hydrogen envelope loss due to Roche lobe overflow, radiation-recombination-limited escape, energy-limited escape, and "automatic" loss in which the local environment sets the escape rate. [AtmEsc, STELLAR]

`HabEvapCores <HabEvapCores>`_: Transition of Proxima b from a mini-Neptune to a habitable evaporated core via hydrogen loss. [AtmEsc, STELLAR]

`HLossTides <HLossTides>`_: Coupled atmospheric escape and tidal evolution for
the CPL tidal model with hydrogen escape via energy-limited,
radiation-recombination-limited, Bondi-limited, and automatic models. [AtmEsc,
EqTide, STELLAR]

`MiniNeptuneEvap <MiniNeptuneEvap>`_: Removal of a mini-Neptune's isothermal hydrogen atmosphere by high energy radiation and/or Roche lobe overflow. [AtmEsc, STELLAR]

`NBodyAtmEsc <NBodyAtmEsc>`_: Coupled envelope loss and N-Body evolution in the
pulsar planet system PSR1257+12. [AtmEsc, SpiNBody]

`VenusWaterLoss <VenusWaterLoss>`_: Water loss from Venus due to water photolyzation and hydrogen escape. [AtmEsc, STELLAR]

`WaterLossTides <WaterLossTides>`_: Evolution of a planet losing water from
photolysis and hydrogen escape while it tidally evolves. [AtmEsc, EqTide,
STELLAR]

**Climate**
===========

`EarthClimate <EarthClimate>`_: Energy balance climate model of Earth over one year, as well as ice sheet growth and retreat on long timescales due to orbital and rotational forcings, i.e. Milankovitch Cycles. [DistOrb, DistRot, POISE]

`IceBelts <IceBelts>`_: Formation of equatorial ice belts on planets with high obliquity. [POISE]

**Galactic Effects**
====================

`GalaxyEffects <GalaxyEffects>`_: Evolution of a wide binary's orbit due to the galactic tide, perturbations from passing stars, and radial migration in the galaxy. [GalHabit]

**Interiors**
=============

`EarthInterior <EarthInterior>`_: Evolution of Earth's thermal and magnetic properties (plate tectonics). [RadHeat, ThermInt]

`IoHeat <IoHeat>`_: Tidal heating of Io as a function of eccentricity and obliquity according to equilibrium tide theory. [EqTide, VSPACE]

`RadHeat <RadHeat>`_: Radiogenic heating evolution in Earth's core, mantle, and crust. [RadHeat]

`TidalEarth <TidalEarth>`_: Coupled internal/orbital/tidal evolution of Earth if it were in the habitable zone of a low mass star and tidally heated. [EqTide, RadHeat, ThermInt]

`VenusApproxInterior <VenusInterior>`_: Thermal and magnetic evolution of Venus' interior (stagnant lid). [RadHeat, ThermInt]

**Orbital Dynamics**
====================

`ApseLock <ApseLock>`_: Evolution of a tidally-damped two-planet system into a state in which the major axes circulate with the same frequency. [DistOrb, EqTide]

`CassiniStates <CassiniStates>`_: Decay of a body's obliquity to a constant value due to perturbations from other bodies and tidal damping. [DistOrb, DistRot, EqTide]

`CassiniMulti <CassiniMulti>`_: Tidal damping of the two planets orbiting Teegarden's Star into Cassini states. [EqTide, DistOrb, DistRot, STELLAR]

`ChaoticResonances <ChaoticResonances>`_: N-body integration of a planetary system in a chaotic eccentricity-inclination mean motion resonance. [SpiNBody]

`CircumbinaryOrbit <CircumbinaryOrbit>`_: Orbital evolution of a circumbinary planet. [BINARY]

`DampedCBP <DampedCBP>`_: Evolution of planet orbiting a tidally evolving binary star. [BINARY, EqTide, STELLAR]

`EarthClimate <EarthClimate>`_: Earth's climate through one year, as well as ice sheet growth and retreat on long timescales due to orbital and rotational forcings, i.e. Milankovitch Cycles. [DistOrb, DistRot, POISE]

`NBodyAtmEsc <NBodyAtmEsc>`_: Coupled envelope loss and N-Body evolution in the
pulsar planet system PSR1257+12. [AtmEsc, SpiNBody]

`SSDistOrbDistRot <SSDistOrbDistRot>`_: Evolution of the Solar System planets' orbital and rotational angular momenta from approximate models. [DistOrb, DistRot]

`TidalEarth <TidalEarth>`_: Coupled internal/orbital/tidal evolution of Earth if it were in the habitable zone of a low mass star and tidally heated. [EqTide, RadHeat, ThermInt]

**Stars**
=========

`BinaryTides <BinaryTides>`_: Coupled stellar and tidal evolution of short-period binary stars. [EqTide, STELLAR]

`MagneticBraking <MagneticBraking>`_: Rotational evolution of stars under different magnetic braking assumptions. [STELLAR]

`STEEP <STEEP>`_: Tidal evolution of a binary star, including the instability radius for circumbinary planets. [EqTide, STELLAR]

`StellarEvol <StellarEvol>`_: Pre-main sequence and main sequence evolution of stellar properties. [STELLAR]

**Tidal Effects**
=================

`ApseLock <ApseLock>`_: Evolution of a tidally-damped two-planet system into a state in which the major axes circulate with the same frequency. [DistOrb, EqTide]

`BinaryTides <BinaryTides>`_: Coupled stellar and tidal evolution of short-period binary stars. [EqTide, STELLAR]

`CassiniStates <CassiniStates>`_: Decay of a body's obliquity to a constant value due to perturbations from other bodies and tidal damping. [DistOrb, DistRot, EqTide]

`CassiniMulti <CassiniMulti>`_: Tidal damping of the two planets orbiting Teegarden's Star into Cassini states. [EqTide, DistOrb, DistRot, STELLAR]

`DampedCBP <DampedCBP>`_: Evolution of planet orbiting a tidally evolving binary star. [BINARY, EqTide, STELLAR]

`HLossTides <HLossTides>`_: Coupled atmospheric escape and tidal evolution for
the CPL tidal model with hydrogen escape via energy-limited,
radiation-recombination-limited, Bondi-limited, and automatic models. [AtmEsc,
EqTide, STELLAR]

`IoHeat <IoHeat>`_: Tidal heating of Io as a function of eccentricity and obliquity according to equilibrium tide theory. [EqTide, VSPACE]

`STEEP <STEEP>`_: Tidal evolution of a binary star, including the instability radius for circumbinary planets. [EqTide, STELLAR]


`TidalEarth <TidalEarth>`_: Coupled internal/orbital/tidal evolution of Earth if it were in the habitable zone of a low mass star and tidally heated. [EqTide, RadHeat, ThermInt]

`TideLock <TideLock>`_: Tidal locking of habitable planets with the CPL and CTL equilibrium tide models. [EqTide]

`WaterLossTides <WaterLossTides>`_: Evolution of a planet losing water from
photolysis and hydrogen escape while it tidally evolves. [AtmEsc, EqTide,
STELLAR]
