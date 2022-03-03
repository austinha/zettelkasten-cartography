# zettelkasten-cartography
Mockup of a Zettelkasten archive that is structured using Structure Notes, title-based Folgezettel, and direct link Folgezettel.

## notes about the archive
It's important to note that this repo contains an archive that was created in Obsidian. It only contains plaintext files with some measure of consistent formatting for the sake of the Zettelkasten. Note that the contents of the archive are not representative of a "quality" archive – in fact, the contents may not be accurate and were created for the purposes of prototyping only.

## structure of the repo
The archive contains four branches: 
- `master`, which is the same as `direct-link-folgezettel`, except that it contains this readme.
- `direct-link-folgezettel`, which is an archive that implements the Folgezettel technique using direct links between notes. Many of these "direct links" are prefixed by "Next: ". Note that this archive **also contains Structure Notes**, as indicated by the tag `#meta/structure/structure-zettel`. This is because Obsidian allows you to filter results by tag.
- `folgezettel-titles-only`, which is an archive that implements the Folgezettel technique using a special naming technique. Some notes contain direct links to other notes, tying Folgezettel together.
- `structure-zettel-only` (to be renamed to `structure-notes-only` later), which is an archive that implements a Zettelkasten without heavy use of Folgezettel, opting for Structure Notes instead. Some notes contain direct links to other notes.
