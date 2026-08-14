# musicxmlTestSuite

This is a fork of Lilypond's extensive MusicXML test suite
developed for testing the `musicxml2ly` program.  Since it is
useful for lots of music projects that want to support MusicXML,
Michael Scott Asato Cuthbert forked it here with Reinhold Kainhofer's blessing.

In 2026, Michael generously donated it to the
[W3C Music Notation Community Group](https://www.w3.org/community/music-notation/)
for ongoing stewardship. This test suite [is currently used by the main MusicXML
repository to validate the XSD schemas and exercise various other validations](https://github.com/w3c-cg/musicxml/tree/gh-pages/tests).

# Usage

The test suite borrows the structure of the original Lilypond test suite, with some changes.

* 01-03: Basics: Pitches, Rests, Rhythm
* 11-14: Staff attributes: Time, Clefs, Key
* 21-24: Notes, Chords, Tuplets, Grace
* 31-34: Notations and articulations
* 41-43: Parts
* 45-46: Repeats, Barlines, Measures
* 51-52: Page layout
* 55-59: Other positioning and layout
* 61: Lyrics
* 71-75: Instrument-specific
* 81-89: MIDI and Sound
* 90: Compressed MusicXML and other MusicXML Formats
* 95-99: Ambiguities, Issues, and Problems
  - 95: Interpretation of changed specifications in different MusicXML versions (unused)
  - 96: Ambiguous situations (unused)
  - 97: Contradictory MusicXML instructions (3/4 + cut time, etc.) (unused)
  - 98: Compatibility with nonsensical but in spec. MusicXML (unused)
  - 99: Compatibility with broken MusicXML (against spec. etc.) found in exports

# Copyright and License

Originally Copyright (c) 2010–2016, Reinhold Kainhofer and the GNU Lilypond
project.  The MusicXML files in that suite and edited here have been released
under the MIT License, see LICENSE for more details.
Free for any use as long as this license remains intact.

Developed 2016–2026 by Michael Scott Asato Cuthbert.
