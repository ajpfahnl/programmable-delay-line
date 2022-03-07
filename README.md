# Programmable Delay Line

Add the `pdl` folder to your library.

## Some Tidbits
`find pdl/ -name '*.cdslck*'` to see any lock files.

`find pdl/ -name '*.cdslck*' | while read lock_file; do rm "${lock_file}"; done` to remove all lock files.
