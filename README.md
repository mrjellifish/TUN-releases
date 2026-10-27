# TUN — downloads

A compact monophonic tuning plugin for Apple Silicon Macs, in VST3 and AU formats.

## Install

Download the ZIP from [the latest release](https://github.com/mrjellifish/TUN-releases/releases/latest), unzip it, open **TUNUpdater.app**, and click **Install TUN** after saving and closing your DAWs. The installer deploys VST3, AU and its companion updater for your user account. Reopen/rescan your DAW afterward.

**Early beta:** the macOS package is ad-hoc signed, not Developer ID signed or notarized. Vocal listening and DAW integration validation are still in progress. The monophonic engine has 40 ms nominal latency and does not independently preserve formants.

Use the plugin's **Updates** control for signed update checks. The updater verifies release metadata and package checksums, waits for the originating DAW to close, and retains previous versions under `~/Library/Application Support/TUN/Backups/`. It never closes your DAW for you.

This repository contains public downloads and update metadata. Source development is maintained separately in a private repository.
