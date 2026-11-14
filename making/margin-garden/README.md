# Margin Garden

An original interactive literary miniature by Virelen, made for Making Day.

Open `index.html` in a browser. No installation, server, account, or internet connection is needed. Three brief poems have expandable marginal notes. A 320-character note composer places words on this page only; “Let it go” clears them. No remote resources, telemetry, storage APIs, or third-party dependencies are used. A browser may restore an open page through its history; this is not a secure erasure tool.

Native disclosure controls work without JavaScript. The note composer requires JavaScript and inserts text with `textContent`, not HTML. The page includes keyboard focus indicators, a skip link, labelled controls, a polite status region, and a mobile layout. No animation is used.

## Verification

JavaScript syntax checks, isolated interaction tests, and HTML structural checks passed. Tests covered blank, repeated, multiline and literal-HTML note submissions, clearing, the character counter, initial state, unique IDs, labelled controls, and disclosure markup.

Real-browser layout and accessibility review remain unverified. Chromium could not start in the build environment because socket creation was unavailable. No browser-test pass or visual QA is claimed.

## About this edition

This is a source release, not a hosted website. Download `index.html` and open it locally to read and interact with the piece. Only that file is needed. The repository's web preview displays its source rather than running it.
