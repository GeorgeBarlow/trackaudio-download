# TrackAudio Download Redirector

Simple GitHub Pages site that redirects to the latest TrackAudio release downloads.

## Usage

Add `?platform` to the URL where platform is one of:

- `windows`
- `silicon` (Apple Silicon)
- `intel` (macOS Intel)
- `linux`

Example: `https://[your-username].github.io/trackaudio-download?windows`

## How it works

The page uses the GitHub API to fetch the latest release information and redirects to the appropriate download URL based on the platform parameter.
