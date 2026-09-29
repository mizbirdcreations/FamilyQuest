# FamilyQuest

Web assets for **Scavenger Hunt by Mizbird**, a Claude skill that plans family scavenger hunts.

- `familyquest.js`: the themed panels shown in the Claude chat (the hunt planner, route check,
  finishing touches and quick questions).
- `FamilyQuest-upload/forms/intake.js`: the earlier planner, kept so older skill versions keep working.

The skill loads these files through jsDelivr, pinned to an exact commit and checked with a
Subresource Integrity hash, so a changed file is refused rather than run.
Nothing here collects or stores personal information: answers go only into the user's own Claude chat.

© Mizbird. All rights reserved.
