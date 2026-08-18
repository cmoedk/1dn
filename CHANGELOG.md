# Changelog

What's new in **One Dude Nation**, newest first. Format follows
[Keep a Changelog](https://keepachangelog.com/en/1.1.0/); versions follow
[Semantic Versioning 2.0.0](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [1.0.0-beta.3] - 2026-08-18 14:12
### Added

- Settings → Credits: who made the game, and the music it plays.
- When a run ends, the rest of the World Cup is played out and the result is shown: who won the final, how
  it was won, and who scored the goal or penalty that settled it.

### Changed

- Qualifying for the World Cup is announced on the qualifier's own screen now, under "Congratulations!",
  and the finals open when you press "Go to World Cup".
- The crowd goes up louder when you score. An opponent's goal is unchanged.
- A penalty shootout warns you before a kick you have to score, and the screen shakes for any kick that
  settles the tie either way.
- Tapping the screen during a replay holds the picture, and tapping again lets it go. Double-tapping still
  skips.
- A goal rewatched from a match's events or from your Goals now plays the crowd going up with it. The
  replay that opens the moment you score still doesn't — the crowd has just done that.
- Starting a new game fills the shirt name and nation name in with your last run's, ready to change.
- Going out at the World Cup finals now says you failed to win it, rather than that you failed to qualify
  for it.
- "Add to Home Screen" only shows on phones and tablets now, where there is a home screen to add it to.

### Fixed

- Opening a group from the World Cup hub showed an empty screen. It now shows that group's table, its
  matches and what it takes to go through.
- World Cup group matches now warn you when a place in the top two is on the line, the way qualifying
  matches always have.
- Reaching the World Cup's Round of 32 is congratulated the moment your last group match ends, instead of
  a screen later. Going out at the group stage lands there too.
- Losing a World Cup knockout tie now ends the run on the bracket it was played on, instead of dropping you
  back to the group tables.

## [1.0.0-beta.2] - 2026-08-18 11:05
### Changed

- Returning to the game loads faster — it no longer re-downloads what hasn't changed.
- The front page shows the version number in the bottom-right corner.

## [1.0.0-beta.1] - 2026-08-18

First beta.

### Changed

- The site always loads over HTTPS.

### Fixed

- OFC final: both legs of a tie are shown from the start, instead of the second appearing only once the
  first had been played.
- A warning now shows before the second leg of a confederation final, naming what a defeat there actually
  costs — the direct World Cup place, not the run.
