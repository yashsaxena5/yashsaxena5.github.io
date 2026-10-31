# yashsaxena5.github.io

Yash Saxena's engineering portfolio is served from the repository root.

The Cyphra product page is a compiled static export under `/cyphra/`. It contains public marketing assets and direct installer links only; the proprietary browser source is kept in a separate private repository.

Current public downloads and release information:

- The versioned [release history](cyphra/releases/index.html) distinguishes the
  Mac 1.2.3 unsigned developer preview (1.2.2 superseded; 1.2.0 and 1.2.1 withdrawn: new-window crash) and pending
  Windows installer. The old Windows download link returned 404 and was removed
  pending verification by its maintainer.
- macOS developer preview: Cyphra 1.2.3, distributed from `/downloads/`.
  It is ad-hoc signed, **not notarized**, and may be blocked by Gatekeeper.
  Never advise users to bypass macOS security warnings. Earlier Mac previews (1.2.0, 1.2.1) were withdrawn
  because they crash when a site opens a new window. The Apple
  package installs the native browser, verifies Ollama's signed universal
  native runtime, downloads the starter model and tests local generation;
  no Homebrew or app wrapper is used.
