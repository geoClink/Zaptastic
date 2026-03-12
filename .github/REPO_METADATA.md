Repository metadata for GitHub
==============================

Suggested short description
---------------------------
Retro-style SpriteKit top-down shooter built in Swift (iOS).

Suggested topics (keywords)
---------------------------
- swift
- spritekit
- game
- arcade
- ios
- indie-game
- 2d

Exact GitHub CLI commands
-------------------------
Run these from the repository root (requires an authenticated `gh` client):

Set the repository description:

```
gh repo edit --description "Retro-style SpriteKit top-down shooter built in Swift (iOS)."
```

Add topics (run as a single command with multiple flags or multiple commands):

```
gh repo edit --add-topic swift --add-topic spritekit --add-topic game --add-topic arcade --add-topic ios --add-topic indie-game --add-topic 2d
```

Verify the metadata was applied:

```
gh repo view --json description,topics
```

Notes
- If you prefer to set topics via the GitHub API directly, you can use `gh api` to PUT to `/repos/:owner/:repo/topics` with a JSON body. The `gh repo edit --add-topic` command is the simplest when running locally.
