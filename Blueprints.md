# Blueprints

Blueprints are created from a site that already has a defined structure.
A blueprint should have a root page and the immediate child pages of the root should be language branches.
Each language branch contains one or more child pages.

Blueprints can be linked to several [Live Copies](LiveCopy.md) (meaning several live copies can be created from Blueprints) and users can track the relationship between a Blueprint and its Live Copies in the [MSM console](MSMConsole.md).
A blueprint is a consistent source for Live Copies.
A Blueprint defines the rollout configs for all Live Copies, unless the Live Copy has been designated a different config.
One benefit of Blueprints is that they can be rolled out, which pushes all changes to the live copies.
