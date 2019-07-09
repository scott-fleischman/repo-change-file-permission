# repo-change-file-permission
A repository for testing the GitHub API for comparing commits when a file only changes permissions.

## Example
https://api.github.com/repos/scott-fleischman/repo-change-file-permission/compare/80fdf8f83fcd8181411919fbf47394b878c591a0...77a95bbebeb78f4fb25c6a10c3c940b6fe1caa27

Notice: `"sha": null`.

```json
    "files": [
        {
            "sha": null,
            "filename": "echo-script",
            "status": "modified",
            "additions": 0,
            "deletions": 0,
            "changes": 0,
            "blob_url": "https://github.com/scott-fleischman/repo-change-file-permission/blob/77a95bbebeb78f4fb25c6a10c3c940b6fe1caa27/echo-script",
            "raw_url": "https://github.com/scott-fleischman/repo-change-file-permission/raw/77a95bbebeb78f4fb25c6a10c3c940b6fe1caa27/echo-script",
            "contents_url": "https://api.github.com/repos/scott-fleischman/repo-change-file-permission/contents/echo-script?ref=77a95bbebeb78f4fb25c6a10c3c940b6fe1caa27"
        }
    ]
```
