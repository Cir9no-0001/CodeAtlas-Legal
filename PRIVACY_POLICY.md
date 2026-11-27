# Privacy Policy

**Last updated: November 2026**

CodeAtlas Extension ("the extension") is a personal, source-available project by Stanley Chen. The source code is publicly viewable but not open source; see the LICENSE file in the repository for permitted use.

## What the extension accesses

- **Your LeetCode session cookie (`LEETCODE_SESSION`)**, read from your browser when you press sync.
- **A GitHub personal access token that you provide**, stored in your browser's local extension storage (`chrome.storage.local`).
- **Basic extension settings**, such as the repository you selected and your sync log, stored in `chrome.storage.local`.

## What happens to it

- The LeetCode cookie is encrypted inside your browser using your repository's public key, then written as a GitHub Actions secret to **your own** GitHub repository. It is sent only to GitHub's API (`api.github.com`) and nowhere else.
- Your GitHub token is used only to call GitHub's API on your behalf.
- The extension has **no CodeAtlas server**. Nothing is sent to the developer, and there are no analytics, advertising or tracking tools.
- Data stored in the extension stays on your device until you remove the extension or clear its data.

## Your control

You can revoke your GitHub token at any time at github.com/settings/tokens, delete the `LEETCODE_SESSION` secret from your repository's settings, or uninstall the extension to remove all locally stored data. Logging out of LeetCode also invalidates the cookie.

## Third parties

Your data is processed by GitHub when you sync, under GitHub's own privacy statement. The extension is not affiliated with or endorsed by LeetCode or GitHub.

## Contact

Questions: stanleycworkmail@gmail.com

## Changes

If this policy changes, the updated version and date will be published in this repository.
