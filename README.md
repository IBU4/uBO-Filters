# uBO-Filters

Personal uBlock Origin filters for Firefox only.

Published for personal synchronization and reference. Not intended for third-party use or public distribution.

No support or compatibility guarantees are provided. Use at your own risk.

# How These Filters Work

These filters target ad-tech at its execution points rather than relying solely on network blocking.

Using uBlock Origin's HTML filtering, they remove matching tracking, fingerprinting, advertising, and anti-adblock components before the browser parses them.

Importantly, HTML filtering does not prevent subsequent dynamic loading or execution through other code paths. This intentional limitation helps preserve website functionality.

Selective response rewriting, compatibility scriptlets, and carefully designed exclusions further minimize unintended breakage.

This is not a standalone filter list. Other standard uBlock Origin filter lists must remain enabled to handle subsequent network requests and residual tracking.

The objective is to prevent unwanted code from executing at its source while preserving legitimate website functionality.
