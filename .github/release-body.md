# oh-my-claudecode v4.14.5: add Grok Build, full multi-repo workspace, persist ultragoal and

## Release Notes

Release with **3 new features**, **1 security improvement**, **37 other changes** across **42 merged PRs**.

### Highlights

- **feat(team): add Grok Build as a team worker + ask provider (v2, addresses #3156 review)** (#3159)
- **feat(multi-repo): full multi-repo workspace support** (#3130)
- **feat: persist ultragoal and enforce Claude goal activation** (#3102)
- **fix(security): directory-boundary check in isTrustedPrefix (CLI trusted-path)** (#3152)

### New Features

- **feat(team): add Grok Build as a team worker + ask provider (v2, addresses #3156 review)** (#3159)
- **feat(multi-repo): full multi-repo workspace support** (#3130)
- **feat: persist ultragoal and enforce Claude goal activation** (#3102)

### Security & Hardening

- **fix(security): directory-boundary check in isTrustedPrefix (CLI trusted-path)** (#3152)

### Documentation

- **docs: model × agent compatibility / recommendation matrix** (#3094)

### Other Changes

- **Stabilize subagent lock benchmark on CI** (#3190)
- **Fix remaining standalone hook state-root imports** (#3189)
- **Fix standalone SessionStart hook helper packaging** (#3188)
- **Fix post-merge dev CI failures** (#3187)
- **Honor workspace Claude skills during OMC slash execution** (#3186)
- **Publish omc npm CLI alias** (#3183)
- **ci: use gajae self-hosted linux runner** (#3180)
- **Align built-in Opus HIGH default with Claude Opus 4.8** (#3175)
- **Update README Discord invite on dev** (#3170)
- **Throttle repeated pre-tool advisory reminders** (#3167)
- **Reduce false-positive review-gate risk assessment** (#3166)
- **Reduce ralph/ultrawork keyword false positives** (#3165)
- **Fail closed on incomplete plugin cache payloads** (#3161)
- **Make SessionStart update notices user-visible** (#3157)
- **Fix Windows daemon bootstrap imports for psmux wait** (#3154)
- **Fix /team Windows psmux gate guidance** (#3153)
- **Restore portable node resolution for hooks** (#3149)
- **Fix SessionEnd cleanup latency** (#3148)
- **Keep scaling tests off live tmux panes** (#3147)
- **Honor stop_hook_active in persistent mode** (#3141)
- **Harden team worker pane startup delivery** (#3137)
- **Fix project-memory list defaults** (#3135)
- **Fix Codex hook-trust prompt detection for team workers** (#3134)
- **Add opt-in force-agent-delegation preflight (#3095)** (#3097)
- **Fix Windows plugin hook manifest commands** (#3124)
- **Fix Windows plugin hook sh rewrite** (#3118)
- **Fix Windows SessionEnd hook command portability** (#3115)
- **Add HUD update notification visibility toggle** (#3113)
- **Fix update-check cache path consistency** (#3112)
- **Fix native Claude Code version detection on Windows** (#3111)
- **Fix hook shutdown and shell portability regressions** (#3110)
- **Guard destructive worktree cleanup paths** (#3103)
- **Fix unsafe teleport remove fallback** (#3091)
- **Fix plugin cache command wrapper materialization** (#3080)
- **Warn on HUD payload budget pressure** (#3074)
- **Fix omc update Claude plugin registry sync** (#3072)
- **Avoid release-like HUD cache test fixtures** (#3067)

### Stats

- **42 PRs merged** | **3 new features** | **0 bug fixes** | **1 security/hardening improvement** | **37 other changes**

### Install / Update

```bash
npm install -g oh-my-claude-sisyphus@4.14.5
```

Or reinstall the plugin:
```bash
claude /install-plugin oh-my-claudecode
```

**Full Changelog**: https://github.com/Yeachan-Heo/oh-my-claudecode/compare/v4.14.1...v4.14.5

## Contributors

Thank you to all contributors who made this release possible!

@a3lab01create-bit @dodolground @J-Pster @rolldav @Yeachan-Heo
