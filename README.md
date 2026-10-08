# yt-block-lists

Category lists for the yt-block extension. JSON data only, never code.

- `index.json`: `{ updated, categories: [id, …] }`
- `{id}.json`: `{ id, name, criterion, updated, channels: [{ channelId, title, network, addedReason }] }`

The extension fetches these from `raw.githubusercontent.com/CoreAspectStu/yt-block-lists/main/` and falls back to its bundled copy. Don't edit the JSON here: it is published automatically from `lists/` in the yt-block repo by its Publish lists action, which validates every list first. Changes made here are overwritten on the next publish.
