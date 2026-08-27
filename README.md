# DJ Tools marketplace

One public catalogue for installing the Music Organiser and Rekordbox plugins in Claude Code or Codex. The djay plugin remains private and is deliberately not listed or downloaded.

## Claude Code

```text
/plugin marketplace add matcluck/dj-tools-marketplace
/plugin install music-organiser@dj-tools
/plugin install rekordbox-skill@dj-tools
```

Invoke the installed skills with:

```text
/music-organiser:music-organiser
/rekordbox-skill:rekordbox-skill
```

## Codex

```text
codex plugin marketplace add matcluck/dj-tools-marketplace
codex plugin add music-organiser@dj-tools
codex plugin add rekordbox-skill@dj-tools
```

Invoke the installed skills with:

```text
$music-organiser:music-organiser
$rekordbox-skill:rekordbox-skill
```

## Plugin sources

- [`matcluck/music-organiser-plugin`](https://github.com/matcluck/music-organiser-plugin) owns metadata inference, library organisation, destination-neutral cue analysis, and destination routing.
- [`matcluck/rekordbox-plugin`](https://github.com/matcluck/rekordbox-plugin) owns Rekordbox collection, cue, playlist, and Pioneer export operations.

The catalogue contains manifests and documentation only. Each runtime fetches the selected plugin directly from its source repository.
