# Folderwise Bookmark Search

A standalone Manifest V3 Chrome extension page that can search inside one bookmark folder or show global matches grouped by folder. It does not replace Chrome's built-in `chrome://bookmarks` page.

## Install locally

1. Open Chrome and go to `chrome://extensions`.
2. Enable **Developer mode**.
3. Select **Load unpacked**.
4. Choose this folder: `bookmark-folder-search-extension`.
5. Click the extension icon to launch Folderwise in a new tab.

Chrome's normal `chrome://bookmarks` page will continue to open the built-in Bookmark Manager.

## Features

- Search by bookmark title, URL, or folder path.
- Select a folder and search only inside it.
- Include or exclude subfolders in folder search.
- Search all bookmarks and keep results grouped by their parent folder.
- Sort by relevance, title, or newest.
- Select individual bookmarks, select all visible results, copy, cut, paste into a selected folder, or delete from buttons or keyboard shortcuts.

## Notes

This extension reads and edits your Chrome bookmarks with the Bookmarks API, but its interface is separate from Chrome's built-in Bookmark Manager.
