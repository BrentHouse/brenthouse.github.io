# Fira Sans & Fira Mono font families

Copyright (c) 2012–2018 The Mozilla Foundation, Telefonica S.A.,
Carrois Corporate GbR, bBox Type GmbH, and contributors

Source: https://github.com/LiberalArtist/FiraSans
Branch: corresponding-source
Commit: f54eeb3124c63fe9b5bcd36d09d1cd46788cd15e
Version: Fira Sans 4.203; Fira Mono 3.206

SIL Open Font License, Version 1.1

There is no Reserved Font Name: see below for details.

## Sources & Version Details

The state of the upstream sources for Fira is confusing.
The repository at <https://github.com/LiberalArtist/FiraSans>
has tracking branches for most of the upstream repositories:

- `mozilla` tracks <https://github.com/mozilla/Fira>,
  the original upstream repository.
  Development of the actual fonts stopped here with
  version 4.202 in commit 48a8d0a (December 2015);
  however, some metadata has been updated here but not
  elsewhere, in particular regarding the removal of the
  Reserved Font Name (see below).
  This repository includes both Glyphs and UFO sources.

- `master` tracks <https://github.com/bBoxType/FiraSans>.
  Development of the fonts continued here through
  Fira Sans 4.301 in commit f54eeb3 (March 2018).
  However, it lacks corresponding sources: UFO sources
  were removed in commit 7eded07, and Glyphs sources were
  never provided. See <https://github.com/bBoxType/FiraSans/issues/4>.

- Development then moved to <https://github.com/bBoxType/FiraGO>,
  which never included corresponding sources and dropped support
  for Mono, Condensed, and Compressed.

We are using Fira Sans 4.203, the final version from
<https://github.com/bBoxType/FiraSans> that included UFO sources.
The relevant files had not been changed since commit 6034516 (October 2016).

This is also the version distributed by Google Fonts,
which is a source of more confusion.
The canonical sources for the TTF files served by Google Fonts are:

- <https://github.com/google/fonts/tree/9b9ec93/ofl/firamono>
- <https://github.com/google/fonts/tree/9b9ec93/ofl/firasans>
- <https://github.com/google/fonts/tree/9b9ec93/ofl/firasanscondensed>
- <https://github.com/google/fonts/tree/9b9ec93/ofl/firasansextracondensed>

(Observe that Google renames “Compact” to “ExtraCondensed”.)

I have not yet discovered the precise provenance of these TTF files,
but <https://github.com/google/fonts/pull/483>
and <https://github.com/google/fonts/issues/10#issuecomment-263219753>
explain the process that was likely used to generate them.
The `googlefonts` branch of <https://github.com/LiberalArtist/FiraSans>
tracks <https://github.com/googlefonts/FiraGFVersion>,
but those don't seem to be exactly the same TTF files.


## Removal of Reserved Font Name

Note that “Fira” is no longer a Reserved Font Name.

Mozilla and other copyright holders relicensed the font without
the RFN in commit 606cb1fc9995666203c50ecf6c14c2c10cdb6659
to Mozilla's repository,
but the bBoxType version of OFL.txt has not been updated accordingly.

For discussion, see <https://github.com/mozilla/Fira/pull/219>,
<https://github.com/mozilla/Fira/issues/221>,
<https://github.com/mozilla/Fira/issues/218>,
<https://github.com/tonsky/FiraCode/issues/573>, and
<https://github.com/tonsky/FiraCode/pull/731>.

