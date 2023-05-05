# musescore

This contains the `broken_score.mscz`. To reproduce, do the following:

1. Open MuseScore 4.
2. Click `Open other`, and open `broken_score.mscz`.
3. Scroll to measure 66-67, and look at the piano part. There is a D♭4 (in bass clef, measure 66, voice 1) and E♭4 (in treble clef, measure 67, voice 2) in the part. (See `x.png` for clarification.)
4. Select these two notes, then add a note anchored line (`Add` -> `Lines` -> `Note anchored line`).
5. Save the file.
6. MuseScore 4 should crash.

I'm not sure if some of these details are necessary to cause the crash, so I'm being specific as possible.
