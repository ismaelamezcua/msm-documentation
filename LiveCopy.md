# Live Copy

A **Live Copy** allows a user to make a copy of an existing site. If the live copy is **made** from a Blueprint, the live copy can be automatically updated when changes are mode to the source site.

**Rollout Configs** can be set on the live copy to determien how content is automatically updated. Rollout Configs consists of two things:

1. An event that triggers an update, such as a change to the content on the source page.
2. One or more actions that occur, such as updating the content on the Live Copy.

A [Blueprint](Blueprints.md) can also be the source for a Live Copy. Blueprints define a source for the Live Copy and consists of the following:

1. The path of the root page of a Website: The path defines the pages that are copied as Live Copy pages.
2. One or more Rollout Configs: Live Copies made from Blueprints inherit the Blueprint Rollout Config.

> Creating Live Copies from non-blueprint pages is more flexible, but more difficult to track.

Live Copies can be linked to only one blueprint, but a blueprint can be linked to many live copies.
