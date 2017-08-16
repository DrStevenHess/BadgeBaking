# Steve's Badge Baking Repo

# outline101_assert
The assert file used to bake the badge at the bakery (http://bakery.openbadges.org/).  It must be generated as to bake the badge and should be created using a PHP-JSON script.  Generated JSON fields should be:

 | Field     | Purpose                                               |
 |-----------|-------------------------------------------------------|
 | recipient | The email of the student receiving the badge.         |
 | issuedOn  | The timestamp of issuance.                            |
 | badge     | URL leading to the raw data for the PNG of the badge. |
 | verify    | URL leading to the raw assert file.                   |

# outline101_class
This file instructs the bakery on the location of the image, criteria, and issuer metadata.  This is manually created upon the defining of a badge.

# outline101_criteria
This is an HTML file containing the criteria for issuing the badge. This is manually created upon the defining of a badge.

# outline101_issuer
This file contains the university issuer data.  This should be universal.

# GitHub Baking
If you host everything on GitHub, all URLs must be the raw versions -- see the above files for examples.

# Mozilla Backpack
Once baked, the badge is imported into the student's backpack (https://backpack.openbadges.org/) and may be posted on social media.
