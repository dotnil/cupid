1.0.0 / 2016-12-??
==================

A complete rewritten of the original cupid@0.1:

 * New: use `DEBUG=cupid` to toggle log behaviours
 * New: use liquid-node as the default templating engine
 * New: a src/target structure for better planet source and target management
 * New: use feed.postSelector option to fetch full articles of the feed

Other changes:

 * Remove: cupid-server, because it is a bit unnecessary
 * Refactor: a much cleaner planet.json
 * Refactor: a much more robust and faster `cupid-build`
