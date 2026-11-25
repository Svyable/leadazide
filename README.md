# Leadwatch — Iowa incident observatory

An independent, static, public-interest dashboard inspired by the map-first presentation of [Iowa Lead Tracker](https://iowaleadtracker.com/), focused on evidence provenance, agency updates and environmental monitoring rather than generating an independent release forecast.

## Run

Open `index.html` in a modern browser or serve the repository with `python -m http.server 8000`. No build, API key, tracking, external map tile service or runtime dependency is required. GitHub Pages can serve the repository root if enabled by an administrator.

## Features

- Responsive regional orientation diagram (schematic, not a hazard map).
- Source-linked public safety and assistance desk.
- Interactive dated document timeline with keyboard-accessible scrubber.
- Air, soil and water monitoring ledger with explicit missing-data status and filtering.
- JSON snapshot export and print view.
- Primary-source library and evidence policy.

## Data and limitations

The initial snapshot is dated November 24, 2026. It is not live or an emergency warning system. The reported aggregate sampling and staffing figures are from the EPA interagency update; they are not concentrations or exposure measurements. No sample-level readings have been ingested. No hazard boundaries, dispersion calculations, facility coordinates or address-level assessments are provided. Follow current instructions from the relevant authorities.

Sources: [Army advisory](https://www.army.mil/article/297039/public_safety_advisory_controlled_mitigated_detonation_of_unstable_lead_azide_at_iowa_army_ammunition_plant), [EPA response](https://www.epa.gov/newsreleases/epa-army-and-other-federal-partners-provide-public-update-iowa-army-ammunition-plant), [EPA permit](https://www.epa.gov/ia/iowa-army-ammunition-plant-middletown-iowa-3), [Illinois EPA](https://epa.illinois.gov/iowa-plant-updates).

## Verification checklist

Open the site at desktop and mobile widths; test the timeline with the keyboard and previous/next controls; change the media filter; download the snapshot and inspect null values; check external source links; verify the print view. The UI should remain readable without JavaScript, with static source links and default records.

Updates should preserve publication dates and original source links. Future laboratory records must preserve reported units, time, medium, qualifiers and provenance, and must not imply an all-clear.
