# yt-block-lists

Category lists for the yt-block extension. JSON data only, never code.

- `index.json`: `{ updated, categories: [id, …] }`
- `{id}.json`: `{ id, name, criterion, updated, channels: [{ channelId, title, network, addedReason }] }`

The extension fetches these from `raw.githubusercontent.com/CoreAspectStu/yt-block-lists/main/` and falls back to its bundled copy. The source of truth while developing is `lists/` in the yt-block repo; copy changes here to publish them.
