# Hull Editor releases

Download files for the optional Code OSS editor in Hull Desktop's editor mode.
Hull Desktop fetches these on demand and checks each file's size and SHA-256
before using it. There is nothing to install by hand.

This repository holds release files only: no source code and no issue tracker.

## What the files are

Each release is a build of the Code - OSS web server (`reh-web`), made with
[VSCodium](https://github.com/VSCodium/vscodium)'s build scripts and a small
set of Hull patches. It is named "Hull Editor" and is meant to run only inside
Hull Desktop.

| File | Platform |
|---|---|
| `hull-editor-reh-web-darwin-arm64-<version>.tar.gz` | macOS, Apple silicon |

Each archive has a matching `.sha256` file.

## Licence

Code - OSS and VSCodium are released under the MIT licence; see
[LICENSE.txt](./LICENSE.txt). Notices for bundled third-party components are in
[ThirdPartyNotices.txt](./ThirdPartyNotices.txt).

Hull Editor is not affiliated with or endorsed by Microsoft or the VSCodium
project. "Visual Studio Code" is a trademark of Microsoft Corporation.
