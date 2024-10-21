# multi-platform

An example of multi-platform JavaScript package distributed via GitHub

You can check how it works via:
`npm add larixer/multi-platform#1.0.0`

Go into `node_modules` and verify that user-facing `multi-platform` package is installed and native package `multi-platform-{os}-{cpu}` for your current platform package is installed. Provided OSes: [`linux`, `darwin`, `win32`]. Provided CPUs: [`x64`].

Note, that 4 branches are used for distribution, each branch is tagged with each package release. Branch for user-facing package is `main`. 3 other branches are used for native packages: `linux-x64`, `darwin-x64` and `win32-x64`.
