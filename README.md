# acpilot

Homebrew formulae for [acpilot](https://github.com/skamansam/acpilot), written by that
repository's release workflow from `cargo-dist`'s output.

    brew install skamansam/tap/acpilot-cli skamansam/tap/acpilotd

`Formula/` is machine-written: the next release replaces these files, so an edit made
here is an edit that release will erase. The formula is named `acpilot-cli` after the
package; the program it installs is `acpilot`. The daemon is its own formula,
`acpilotd`, because `cargo-dist` ships one archive per program and `acpilot` finds the
daemon beside itself rather than on `PATH`.
