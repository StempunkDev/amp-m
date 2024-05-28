# Roadmap

## Version 1.0

- [x] Initialize Readme, Create roadmap
- [ ] Project Configuration + Entrypoint
- [ ] Input handling
  - [ ] Establishment of (user) interface/API-contract version 1
  - [ ] Argument handling
  - [ ] REPL env for agent-mode (as sub-application in UI/as socket-service)
- [ ] State
  - [ ] handle diffable playlist data
  - [ ] handle bindings for different services
  - [ ] version-upgradable persistent storage
    - only "store" non-redundant non-resolvable core-information
    - everything resovable is cached and version-bound
- [ ] API clients
  - [ ] discovery
  - [ ] Read operations
  - [ ] SAFE Write operations
- [ ] Minimal feature set
  - Platforms
    - [ ] Youtube
    - [ ] Spotify
  - [ ] sync between any platform
  - [ ] import/export playlists from/to platforms (into intermediate format)
  - [ ] matching songs across platforms by best-effort
  - [ ] playlist merge
  - [ ] playlist split
  - [ ] modification of playlists with bulk operations
    - [ ] including sort
  - [ ] save modification-set for repeated application (for example "remove invalid -> sort by rating -> sort by artist -> move (title:xyz) pos 1 -> move (title:abc) pos 3")
- [ ] Discord integration
  - [ ] capabilities to post processing updates when running in automated mode