# Blueprints

Blueprints are created from a site that already has a defined structure.
A blueprint should have a root page and the immediate child pages of the root should be language branches.
Each language branch contains one or more child pages.

Blueprints can be linked to several [Live Copies](LiveCopy.md) (meaning several live copies can be created from Blueprints) and users can track the relationship between a Blueprint and its Live Copies in the [MSM console](MSMConsole.md).
A blueprint is a consistent source for Live Copies.
A Blueprint defines the rollout configs for all Live Copies, unless the Live Copy has been designated a different config.
One benefit of Blueprints is that they can be rolled out, which pushes all changes to the live copies.

## Creating a Blueprint

When you create a blueprint configuration, you select a template that defines the internal structure of the blueprint. The default blueprint template assumes that the source website has the following characteristics:

- The web site has a root page.
- The immediate child pages of the root are language branches of the web site. When creating a live copy, the languages are presented as optional content to include in the copy.
- The root of each language branch has one or more child pages. When creating a live copy, child pages are presented as a chapter that you can include in the live copy.

To create a blueprint configuration:

1. Open the **Tools** console <http://localhost:4502/miscadmin>
2. In the folder tree, select **Tools**, then **MSM Control Center**.
3. Select **New** and then **New Page**.
4. Enter a title (MagmaLabs Blog Blueprint), a name (magmablog-blueprint) and select **Blueprint template**.
5. Click **Create**.
6. **Double-click** on the name to open the new blueprint and click **Edit**.
7. In the settings dialog, enter the name, a description, and (optional) a thumbnail image. Select the source path for the site (/content/blog) or the pages for the blueprint.
8. Click **OK**.
