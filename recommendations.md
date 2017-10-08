TODO: write up concrete suggestions for a way forward that would satisfy the laid-out requirements

Have dedicated online community moderators, who actively welcome new members, and seek out and encourage quieter voices to speak up when conversation turns to their interests.

## Technical Design

Implementations should be designed to be as portable, adaptable, and generally anti-fragile as possible, with servers being cattle, not pets. This avoids having massive failures compounded around a trivial issue arising in a critical component where the issue can't be easily rectified through simple replacement.

Backups are essential.
