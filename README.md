# jishaku-braille-j

On August 1, 2020, Jishaku's `logout` command was inexplicably reverted to using regular full stop characters
instead of "braille pattern dots-356", affectionately named "Braille J". Gorialis, the author of the repository,
seems unwilling to merge any attempts to rectify this travesty, so this fork restores Jishaku to its former glory
by reinstating the Braille J.

This package is 100% identical to upstream Jishaku except for a single string in the `logout` command.
