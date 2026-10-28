# AXO Life character profile

This folder contains the first AXO character profile for AIRI.
The profile defines Italian dialogue, identity, and greetings.
It does not include an avatar model, a voice provider, persistent memory, or an arena engine.

## Import

1. Create a ZIP archive with `manifest.json` and `card.json` at its root.
2. Open AIRI character settings.
3. Import the ZIP archive as a character package.
4. Select AXO.
5. Configure a chat provider and a speech provider in AIRI.
6. Select an Italian voice from the speech provider.

Provider credentials stay in AIRI settings. Do not commit credentials to this repository.
The package contains no model or provider credentials.
The original AXO image is a design reference. It is not a rigged VRM model.

## Next steps

- Run AIRI on Windows and measure rendering performance.
- Connect an Italian speech provider and a chat provider.
- Build the original AXO design as a rigged VRM model.
- Add persistent memory with explicit save and delete operations.
- Connect progression and arena actions to application state.

## Validation

The JSON fields were compared with the AIRI character package importer and CCv3 schema.
Application import, voice output, and rendering remain unverified.
No runtime source files or dependencies change in this branch.
