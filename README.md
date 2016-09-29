# MultiSite Manager

Multi Site Manager (MSM) enables you to use the same site content in multiple locations. Content can be managed at a
page or a paragraph level. MSM allows user to replicate changes to content on one site to other sites. It also
facilitates management of language versions of sites.

<http://dcpinfo.alticor.com/en_us/multi-site-manager.html>

## Helpful terms:

- **Language Copy**: a language variation of the site.
- **Live copy**: A site copied from another site.
- **Blueprint**: A master used to create other sites.
- **RolloutConfig**: An instruction set for synchronizing a Live Copy with a Blueprint.
- **MSM Console**: A tool used to view and manage the relationships between Blueprints and Live Copies.

# Possible scenarios

<https://docs.adobe.com/docs/en/aem/6-2/administer/sites/msm.html>

## Multinationals - Global to Local Company

Reuse content in several multinational same-language sites. This allows the core contentn to be re-used, while allowing for national variations.
For example, the following structure can be used for sites for the United Kingdom, Canada, and Australia:

    /content
        |- geometrixx
            |- en
        |- geometrixx-gb
            |- en
        |- geometrixx-ca
            |- en
        |- geometrixx-au
            |- en

## National - Head-Office to Regional Branches

A company with a network of dealers might want to separate websites for their individual dealerships, each being a variation of the main site provided by the head-office.

    /content
        |- head-office-Berlin
        |- branch-Hamburg
        |- branch-Stuttgart
        |- branch-Munich
        |- branch-Frankfurt

## Multiple Versions

We can use MSM to create versions of a specific sub-branch.

    /content
        |- support
            |- product X
                |- v5.0
                |- v4.0
                |- v3.0
                |- v2.0
                |- v1.0
                
Next: [Blueprints](Blueprints.md)
