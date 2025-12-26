# Visual Orgish

## Vision

To make GNU Emacs org-mode a first class experience inside Visual Studio Code, without compromising correctness, semantics, or long term interoperability.

Visual Orgish envisions a world where org-mode files are truly editor agnostic. Users should be able to move freely between GNU Emacs and VS Code while working on the same files, with the same meaning, and without loss of capability or intent.

The project exists to ensure that org-mode remains a durable plain text system for thinking, planning, and writing, independent of any single editor.

## Mission

The mission of Visual Orgish is to ensure that GNU Emacs org-mode files can be worked with reliably inside Visual Studio Code.

This project is guided by the following goals:
- Achieve full compatibility with the GNU Emacs org-mode file format
- Faithfully implement org-mode semantics rather than surface level syntax
- Allow seamless editing of org files in VS Code alongside GNU Emacs
- Prevent fragmentation of the org ecosystem by prioritizing compatibility over convenience

Visual Orgish is intentionally focused on working with existing GNU Emacs org-mode files. It does not aim to create a new dialect, subset, or alternative interpretation of org-mode.

This means:
- Org files edited in VS Code must behave the same when opened in GNU Emacs
- Features are added only when their behavior is clearly defined and understood
- Compatibility with the GNU Emacs implementation takes precedence over editor specific shortcuts

Visual Orgish is a clean room implementation guided by org-mode documentation and observed behavior, with the explicit goal of long term parity with the GNU Emacs based reference implementation.

Visual Orgish exists to extend the reach of org-mode, not to redefine it.
