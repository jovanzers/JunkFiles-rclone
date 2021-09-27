# JunkFiles-rclone
Junk files list for rclone delete purposes

## How to use
`rclone delete REMOTE:PATH --include-from junk.txt --ignore-case --fast-list -vP`

Add flag `--drive-use-trash=False` if you want to delete permanently.
