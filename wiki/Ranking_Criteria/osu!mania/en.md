# osu!mania ranking criteria

***Notice: This article is an extension of the [general ranking criteria](/wiki/Ranking_Criteria).***

This set of **osu!mania ranking criteria** lays out [rules and guidelines](/wiki/Ranking_Criteria#general-terms) that [osu!mania](/wiki/Game_mode/osu!mania)-specific [beatmaps](/wiki/Beatmap) must follow in order to progress through the [beatmap ranking procedure](/wiki/Beatmap_ranking_procedure).

## Glossary

### Difficulty names

*Main article: [Difficulty Naming](/wiki/Ranking_Criteria/Difficulty_naming)*

- ![](/wiki/shared/diff/easy-m.png?20211215) Easy
- ![](/wiki/shared/diff/normal-m.png?20211215) Normal
- ![](/wiki/shared/diff/hard-m.png?20211215) Hard
- ![](/wiki/shared/diff/insane-m.png?20211215) Insane
- ![](/wiki/shared/diff/expert-m.png?20211215) Expert

### Common terms

- **BPM**: Tempo of a song measured in beats per minute.
- **Column**: Vertical lines on the playfield where notes are placed. The editor uses `0|1|2|3|4|5|6|7|8|9|10|11|12|13|14|15|16|17` for timestamp labels.`+`
- **Key mode**: The number of columns present in a difficulty.
- **Playstyle**: The particular layout and mapping style used within a key mode. `+`
- **Dynamic playstyle**: A playstyle where the columns don't map 1:1 with the fingers that typically play them. (Subject to change) `+`
- **Island**: A group of columns that require physical repositioning of an entire hand to hit effectively. `+`
- **Island playstyle**: A dynamic playstyle where at least one hand is expected to switch between two or more islands. (e.g. [EZ2AC 14K](https://i.ppy.sh/43e55c5dc6f7be4d08e25697491a9a8c26217a84/68747470733a2f2f63646e2e646973636f72646170702e636f6d2f6174746163686d656e74732f3831383639383833333536323832383832332f313131393738353532303133393038383038362f455a3241435f31344b5f4578616d706c655f4b657962696e64735f76312e312e706e67)). `+`
- **Keysounding**: Hitsounding using samples extremely similar or directly from the song in their respective places. This method of hitsounding usually provides low feedback to the player.
- **Slider velocity**: The speed at which the notes/bar lines move on the playfield. Base slider velocity (1.0x) is based on the user's scroll speed, and additional changes can be made through inherited (green) timing points.
- **Long-term slider velocity**: A slider velocity change lasting more than 4 measures.
- **Musical phrase**: A standalone unit of musical meter that is usually 4 measures long.
- **Short-term slider velocity**: A slider velocity change lasting less than 1/2 of a beat.

### Patterns

- **Anchor**: A pattern that has a relatively high amount of notes in one column compared with another column, usually found within different types of streams.
- **Bracket**: A pattern that involves multiple trills using columns near each other.
- **Chord**: Two or more notes pressed at the same time.
- **Chordstream (Jumpstream, Handstream, Quadstream)**: Streams that mix different types of chords.
- **Grace**: Two or more notes pressed in rapid succession, generally using snaps at or above 1/6.
- **Hand**: Three notes pressed at the same time. Occasionally referred to as a "triple".
- **Jack**: Three or more consecutive notes in the same column, usually pressed at a faster pace than surrounding notes.
- **Jump**: Two notes pressed at the same time. Occasionally referred to as a "double".
- **Jumptrill**: A trill consisting of two alternating jumps.
- **Minijack**: Two consecutive notes in the same column, usually pressed at a faster pace compared to surrounding notes.
- **Release**: The end of a long note which must be released within a certain timing window to score the entirety of the note properly.
- **Roll**: A variation of a stream consisting of notes that go from the first to the last column or last to the first column, usually done in quick succession.
- **Shield**: A note that appears in the same column immediately before the beginning of a long note.
- **Split-jumptrill**: A jumptrill which requires the use of both hands at the same time to be performed correctly (i.e two one-handed trills).
- **Stream**: Constant notes with the same interval for at least one beat that do not repeat to create a minijack.
- **Trill**: More than two notes that alternate between two columns without interruption.

Refer to the [osu!mania Mapping Guide](/wiki/Guides/osu!mania_Mapping_Guide) for more pattern terminology.

## Overall

Overall rules and guidelines apply to every kind of osu!mania difficulty. Rhythm-related rules and guidelines apply to approximately 180 BPM beatmaps with 4/4 time signatures. If your song is drastically faster or slower, some variables might be different, as detailed in [Scaling BPM on the Ranking Criteria](/wiki/Ranking_Criteria/Scaling_BPM).

### Rules

- **The `Auto` mod must be able to achieve the full score (1,000,000) in all difficulties.**
- **Two notes cannot be placed in a single column at the same timestamp.**
- **No column can be left empty.** If you want to use fewer keys, change the number of keys in the Song Setup.
- **There must not be more than 6 notes pressed at any given moment in Insane or lower difficulties.** Using more than 6 notes must also follow a reasonable spread to the next lower difficulty. This rule does not apply to ends of long notes, as they are released, not pressed.
- **Beatmaps can only use 4 to 10, 12, 14, 16, or 18 keys.** Anything else is not supported for the Ranked section.`+`
- **If multiple key modes are present in a single beatmap, the key mode must be denoted in all difficulty names. Otherwise, the key mode must not be denoted.**
- **If multiple playstyles of a single key mode are present in a single beatmap, the playstyle must be denoted using a recognisable marker in all difficulty names of the key mode (e.g. "14K EZ2AC Hard" and "14K DP Hard"). Otherwise, it is optional to denote the playstyle.** `+`
- **Beatmaps using the special N+1 style of mapping must be denoted as such under the `Advanced` tab of song setup in the editor and "N+1" must be added to the tags. For beatmaps containing multiple key modes, difficulties using this style must be denoted using N+1 notation (e.g. using "7K+1" instead of "8K" on difficulty names).**
- **Beatmaps using the special N+2 style of mapping must include "N+2" in the tags. For beatmaps containing multiple key modes, difficulties using this style must be denoted using either using N+2 notation (e.g. using "10K+2" instead of "12K" on difficulty names), OR using a recognisable playstyle marker (e.g. "10K2S" instead of "12K")** `+`
- **For maps using an island playstyle,** notes placed on one island must be treated as occupying all other columns played by the same hand on other islands, which means: `+`
  - Notes played by the same hand on different islands cannot be placed on the same timestamp.`+`
  - Guidelines regarding anchors and jacks also apply to combinations of notes played by the same hand on different islands.`+`
  - This rule may be ignored in cases where one island can be played by both hands, relieving the need to hit notes on different islands with the same hand.`+`
- **If the [drain time](/wiki/Beatmap/Drain_time) of each difficulty is...**
  - **...lower than 2:30**, the lowest difficulty of each included keymode cannot be harder than a Normal, **OR** each keymode must provide a spread starting at least 3 difficulty levels below the highest difficulty.
  - **...between 2:30 and 3:15**, the lowest difficulty of each included keymode cannot be harder than a Hard, **OR** each keymode must provide a spread starting at least 2 difficulty levels below the highest difficulty.
  - **...between 3:15 and 4:00**, the lowest difficulty of each included keymode cannot be harder than an Insane, **OR** each keymode must provide a spread starting at least 1 difficulty level below the highest difficulty.
- On difficulties Insane and harder, a proper spread is defined by relative difficulty gaps similar to those formally defined between lower difficulties.


### Guidelines

- **Every note should correlate to a sound present in the music.** This should be a distinct sound, but can also coherently represent a continuous sound with an indistinguishable start or end. Exceptions in favour of simplification should be made when following the music completely accurately...
  - would be unreasonable to play with full accuracy.
  - would be effectively represented with a consistent, predictable snap.
  - would cause an inappropriate difficulty spike.
- **Long notes should be held for at least 1/12 of a beat.** Faster release timings are unreasonable to play with full accuracy.
- **Avoid using storyboard sampled hitsounds with similar volume to hitsounds on notes.** As storyboarded hitsounds can overwhelm and distort audio feedback from objects in the beatmap, placing hitsounds on a note in the chart should be prioritised. However, storyboarded samples may be used when keysounds are extracted directly from a song and when low difficulties have too few notes to support necessary hitsounds.
- **Do not use keysounds without hitnormal support.** If hitsounds blend perfectly with the song, feedback for hitting notes is minimal. However, when keysounds extracted directly from a song are used as a replacement for a song's audio, they do not need hitnormal support.
- **Avoid using the same hitsound for multiple notes in a chord.** This causes feedback to be louder than necessary. This also applies to active hitsounds and storyboard hitsounds used at the same timestamp.
- **Timing changes should have a unified scroll speed by adjusting slider velocity.** This is done by normalising the scroll speed of all timing sections to the most used one in the beatmap. The number is shown in parentheses after the BPM range in the song selection, e.g. `BPM: 60-160 (130)`. Note that this guideline does not affect the ability to add slider velocity changes which are used to create SV effects.
- **Slider velocity changes should follow the general intensity of the song.**
- **Slider velocity changes should be snapped according to the song's beat structure.** If the song is using a straight beat, 1/4, 1/8, 1/16 should be used. If the song is using a swing beat, 1/6 or 1/12 should be used. If the song has a beat in a different position from what is recommended, snapping to an actual beat always takes priority.
- **Avoid spamming short kiai time segments.** Doing so can be distracting and can negatively affect gameplay.
- **Breaks should only be used when a section of music is extremely calm or silent.** Lower difficulties, especially on higher BPM songs, may use breaks to avoid parts of a song that are unreasonable for new players to play.

## Difficulty-specific

Difficulty-specific rules and guidelines do only apply to the difficulty level they are listed for and therefore *do not apply to **every** osu!mania difficulty*. Rhythm-related rules and guidelines apply to approximately 180 BPM beatmaps. If your song is drastically faster or slower, some variables might be different, as detailed in [Scaling BPM on the Ranking Criteria](/wiki/Ranking_Criteria/Scaling_BPM).

*Key mode-specific guidelines are constructed based on 4 key, 7 key, and 10 key. Any other key modes should apply these guidelines when applicable.* `+`

### ![](/wiki/shared/diff/easy-m.png?20211215) Easy

#### Rules

- **Slider velocity changes that alter the scrolling speed of the beatmap are disallowed.** Slider velocity changes to unify the scroll speed in variable BPM beatmaps are exempt.
- **Scroll normalisation must be done in beatmaps with variable BPM.**
- **For difficulties using more than 10 keys that also use a special N+2 style,** special notes must be treated as being in the same column as normal notes on the same hand, which means:`+`
  - Special and normal notes played by the same hand cannot be placed at the same timestamp.`+`
  - Guidelines regarding anchors and jacks also apply to combinations of special and normal notes.`+`
- **For difficulties using dynamic playstyles,** notes that are placed in one column must be treated as occupying other columns that are typically hit by the same finger, as dictated by the specific playstyle. This means:`+`
  - Notes placed in different columns that are typically played by the same finger cannot be placed on the same timestamp. Such chords require irregular finger movement not suitable for a beginner.`+`
  - Guidelines regarding anchors and jacks also apply to combinations of notes on different columns played by the same finger.`+`
  - This rule may be ignored in cases where one column can typically be played by multiple fingers, relieving the need for irregular finger movement to hit such chords.`+`

#### Guidelines

- **HP and OD values should not be higher than 7.**
- **Note snappings of consecutive 1/4 and higher should not be used.** Slower rhythms are more appropriate for this difficulty level.
- **Long notes should be held for at least one beat.** Faster release timing is too difficult for players of this level.
- **Long note releases should be at least one beat apart from each other.** Smaller gaps between releases require a level of finger independence that players of this difficulty cannot handle.
- **Objects should not be placed during a 1/1 long note's hold duration.** However, using an object at the beginning or end of a long note is fine.
- **Note density should consist of mostly 1/1, occasional 1/2, or slower rhythms.**
- **Avoid using more than 5 consecutive 1/2 notes.**
- **Avoid using chords during consecutive 1/2 note patterns.** However, using a chord to begin or to end a pattern is fine.
- **Avoid chords with more than 2 notes.** This includes long note patterns that involve notes in more than two columns.
- **For difficulties using island playstyles**, either hand should receive a 2-beat pause before switching islands. Faster hand movement is not suitable for players of this difficulty. `+`

Additional guidelines for *10 key Easy* difficulties:`+`

- **It is encouraged to balance consecutive 1/2 patterns across both hands.** This guideline may be relaxed depending on the relative difficulty of the patterns being used. For example, rolling motions are typically simpler to hit than patterns demanding back-and-forth knuckle movement.`+`
- **Patterns involving hitobjects placed during the duration of a long note held by the same hand should be used sparingly.** Such patterns may be difficult for beginners.`+`

### ![](/wiki/shared/diff/normal-m.png?20211215) Normal

#### Rules

If a Normal difficulty is required and used as the *lowest difficulty* of a beatmap, it must also abide by these rules:

- **Slider velocity changes that alter the scrolling speed of the beatmap are disallowed.** Slider velocity changes to unify the scroll speed in variable BPM beatmaps are exempt.
- **Scroll normalisation must be done in beatmaps with variable BPM.**
- **For difficulties using more than 10 keys that also use a special N+2 style,** special notes must be treated as being in the same column as normal notes on the same hand, which means: `+`
  - Special and normal notes played by the same hand cannot be placed at the same timestamp.`+`
  - Guidelines regarding anchors and jacks also apply to combinations of special and normal notes.`+`

#### Guidelines

- **HP and OD values should not be higher than 7.5.**
- **Note snappings of consecutive 1/6 and above should not be used.** Slower rhythms are more appropriate for this difficulty level.
- **Long notes should be held for at least 1/2 of a beat.** Faster release timing is too difficult for players of this level.
- **Long note releases should be at least 1/2 of a beat apart from each other.** Smaller gaps between releases require a level of finger independence that players of this difficulty cannot handle.
- **Objects should not be placed during a 1/2 long note's hold duration.** However, using an object at the beginning or end of a long note is fine.
- **Avoid rhythms faster than 1/2 during a 1/1 long note's hold duration.**
- **Avoid using any form of 1/4 shield pattern.** The coordination required for this pattern is too difficult for players at this level.
- **Note density should consist of mostly 1/1 and 1/2, occasional 1/4, or slower rhythms.**
- **Avoid using more than 5 consecutive 1/4 notes.**
- **Long streams of 1/2 notes should include, at minimum, a 1/1 pause where natural to implement after every musical phrase**, as these can become too physically demanding for players at this level.
- **Avoid using chords during consecutive 1/4 note patterns.** However, using a chord to begin or to end a pattern is fine.
- **Avoid anchors consisting of three or more notes.** While they are easy for players to read, longer anchors are strenuous.
- **Avoid using 1/4 minijacks or other jack patterns.** These patterns are too physically demanding for players at this level.
- **Manipulating slider velocity is discouraged.** Slider velocity should only be changed for sections of music with different intensities and should not be drastically variable throughout the beatmap.
- **Long-term slider velocity changes should be between 0.90x and 1.05x.**
- **For difficulties using dynamic playstyles,** notes that are placed in one column should be treated similarly to occupying other columns that are typically hit by the same finger, as dictated by the specific playstyle. This means:`+`
  - chords involving notes placed in different columns that are typically played by the same finger on the same timestamp should be used very sparingly. Such chords require irregular finger movement to hit, and should only be lightly introduced to players at this level.`+`
  - Guidelines regarding anchors and jacks also apply to combinations of notes on different columns played by the same finger.`+`
  - This guideline may be ignored in cases where one column can typically be played by multiple fingers, relieving the need for irregular finger movement to hit such chords.`+`
- **For difficulties using island playstyles**, either hand should receive a 1/1 pause before switching islands. Faster hand movement is not suitable for players of this difficulty. `+`

Additional guidelines for *4 key Normal* difficulties:

- **Avoid chords with more than 2 notes.** This includes long note patterns that involve notes in more than two columns. However, using a double that is played with the other hand than the long note is fine.

Additional guidelines for *7 key Normal* difficulties:

- **Avoid chords with more than 3 notes.** This includes long note patterns that involve notes in more than three columns. However, using a double that is played with the other hand than the long note is fine.
- **Bracket patterns should be used sparingly.**
- **Long notes played with adjacent keys that are held simultaneously should be released at the same time.** Long notes with multiple release timings require coordination that players of this level cannot reasonably handle.

Additional guidelines for *10 key Normal* difficulties:`+`

- **Avoid chords with more than 4 notes.** When such chords are used, it is encouraged to relax the density of surrounding patterns.`+`
- **1-handed 1/2 bracket patterns should be used sparingly.** This extends to other 1-handed patterns requiring the independent movement of 3 or 4 knuckles.`+`
- **Avoid staggering the releases for long notes held simultaneously by the same hand.** When such patterns are used, it is encouraged to relax the density of surrounding patterns.`+`

### ![](/wiki/shared/diff/hard-m.png?20211215) Hard

#### Guidelines

- **HP and OD values should not be higher than 8.**
- **Note snappings of consecutive 1/8 and higher should not be used.** These can be too physically demanding for players of this level. An exception to this guideline would be the usage of 3 grace notes that are at higher-end snaps (1/8, 1/12 and 1/16) as they are only used to accentuate gracing sounds.
- **Long streams of 1/4 notes should include, at minimum, a 1/2 pause where natural to implement after every musical phrase.** These can be too physically demanding for players of this level.
- **Chords within 1/4 streams should be at least 1/1 beat apart from each other.** More dense usage of chords is too difficult for players of this skill level.
- **Avoid using chords in the middle of 1/6 streams.** However, Using a chord at the beginning or end of a stream is fine.
- **Avoid anchors consisting of five or more notes.** While they are easy for players to read, longer anchors are strenuous.
- **1/4 Jack usage is discouraged.** These can be too physically demanding for players of this level. Minijacks with ample rest time in between may be acceptable.
- **Avoid using more than 9 consecutive notes in a trill.** The coordination and hand balance required for this pattern is too difficult for players at this skill level.
- **Long notes should be held for at least 1/4 of a beat.**
- **Objects directly after short-term slider velocity changes should appear at the beatmap's normal scroll speed.** To do this, short-term slider velocity changes should only be used in empty spaces between notes and should equalise to a distance of 1.0x.
- **Long-term slider velocity changes should be between 0.8x and 1.10x.**
- **Slider Velocity gimmicks should be reactable within 1/2 of a beat or more.**
- **For difficulties using more than 10 keys that also use a special N+2 style,** special notes should be treated similarly to being in the same column as normal notes on the same hand, which means: `+`
  - Patterns involving special and normal notes played simultaneously by the same hand should be used only where very strong musical justification is present.`+`
  - Guidelines regarding anchors and jacks also apply to combinations of special and normal notes.`+`
- **For difficulties using dynamic playstyles,** notes that are placed in one column should be treated similarly to occupying other columns that are typically hit by the same finger, as dictated by the specific playstyle. This means:`+`
  - chords involving notes placed in different columns that are typically played by the same finger on the same timestamp should be used sparingly. Such chords require irregular finger movement to hit.`+`
  - Guidelines regarding anchors and jacks also apply to combinations of notes on different columns played by the same finger.`+`
  - This guideline may be ignored in cases where one column can typically be played by multiple fingers, relieving the need for irregular finger movement to hit such chords.`+`
- **For difficulties using island playstyles**, either hand should receive a 1/2 pause before switching islands. Faster hand movement is not suitable for players of this difficulty. `+`

Additional guidelines for *4 key Hard* difficulties:

- **Avoid chords with more than 3 notes.** This includes long note patterns that involve notes in more than three columns.

Additional guidelines for *7 key Hard* difficulties:

- **Avoid chords with more than 4 notes.** This includes long note patterns that involve notes in more than four columns.
- **Keep chord distance in a chordstream at a 1/1 or higher interval.** Anything denser than that can hurt readability.
- **Occasional hands can be used in streams, so long as they are separated by at least one measure (4 beats).**

Additional guidelines for *10 key Hard* difficulties:`+`

- **It is encouraged to give the hand playing 3 or more notes in a chord a 1/2 break before OR after said chord.** `+`
- **Either hand should have frequent 1/2 breaks in the middle of a long stream.** This guideline may be relaxed depending on the relative difficulty of the streams being used. Streams with lots of rolling motions are typically simpler to hit than streams demanding back-and-forth knuckle movement.`+`
- **Occasional quads can be used in streams, so long as they are separated by at least one measure (4 beats).** This guideline may be relaxed depending on the relative difficulty of the quads being used.`+`

### ![](/wiki/shared/diff/insane-m.png?20211215) Insane

#### Guidelines

- **Avoid unjustified spikes in difficulty.** Difficulty should be representative of the song's intensity.
- **Avoid using split rolls or any kind of complicated 1/8 streams lasting longer than 4 beats.** Streams of this type of snap are hard to execute and should only be used if the song warrants it.
- **Avoid using 1/6 or higher snap long note streams.** These are very hard to hit and release because of their very short length. Use regular notes in place of streams instead.
- **Long-term slider velocity changes should be between 0.70x and 1.10x.**
- **Slider Velocity gimmicks should be reactable within 1/4 of a beat or more when unnormalised and 1/2 of a beat or more when normalised.**
- **For difficulties using more than 10 keys that also use a special N+2 style,** special notes should be treated similarly to being in the same column as normal notes on the same hand, which means: `+`
  - Patterns involving special and normal notes played simultaneously by the same hand should be used only where very strong musical justification is present.`+`
  - Guidelines regarding anchors and jacks also apply to combinations of special and normal notes.`+`
- **For difficulties using dynamic playstyles,** notes that are placed in one column should be treated similarly to occupying other columns that are typically hit by the same finger, as dictated by the specific playstyle. This means:`+`
  - chords involving notes placed in different columns that are typically played by the same finger on the same timestamp should not be overused. Such chords require irregular finger movement to hit.`+`
  - Guidelines regarding anchors and jacks also apply to combinations of notes on different columns played by the same finger.`+`
  - This guideline may be ignored in cases where one column can typically be played by multiple fingers, relieving the need for irregular finger movement to hit such chords.`+`

Additional guidelines for *4 key Insane* difficulties:

- **Avoid using chords in the middle of 1/8 streams.** The density of these patterns is often too difficult for players of this skill level, especially when used on the lowest difficulty of a beatmap. Additionally, ineffective placement of chords may result in inconsistent 1/4 minijack usage. Using a chord at the beginning or end of a stream is fine.
- **Using split-jumptrills for 2+ beats that leads to a hand is discouraged.** Unless a beatmap uses jacks or other complex patterns frequently, this pattern is difficult to hit. If a hand is necessary, delete the note before it that would create the mini jack.
- **Avoid using more than 9-note split-jumptrills.** These are more physically exhausting than other patterns of similar density.

Additional guidelines for *7 key Insane* difficulties:

- **Avoid using 1/4 jacks with 3+ notes in the middle of chordstream.** These require finger independence that is too difficult for players at this level.
- **In the middle of a long chord stream with a chord every...**
  - ...1/1, there should not be more than 3 notes, except at the beginning/end of a stream, when 4 is acceptable.
  - ...1/2, there should not be more than 2 notes.
  - ...1/4, it's recommended to use a single note instead unless there is extremely clear musical justification.
- **Bracket streams should be used sparingly.**

Additional guidelines for *10 key Insane* difficulties:`+`

- **1-handed bracket streams should be used sparingly.** This extends to other 1-handed patterns requiring the independent movement of 3 or 4 knuckles.`+`
- **1/4 jacks should be used in chordstreams sparingly.** When used, it is encouraged to shift note density away from the hand playing said jacks.`+`
- **In the middle of a long chordstream, appropriate sizes and intervals for chords should be informed by the finger dexterity demanded by the chordstream.** A chordstream that demands lots of back-and-forth knuckle movement (e.g. brackets) is significantly more difficult than a chordstream consisting mainly of roll-like patterns, and cannot accomodate larger chords as comfortably.`+`

### ![](/wiki/shared/diff/expert-m.png?20211215) Expert

#### Guidelines

- **Avoid unjustified spikes in difficulty.** Difficulty should be representative of the song's intensity.
- **Long-term slider velocity changes should be between 0.60x and 1.10x.**
- **For difficulties using more than 10 keys that also use a special N+2 style,** patterns involving special and normal notes played simultaneously by the same hand should not be overused. `+`

