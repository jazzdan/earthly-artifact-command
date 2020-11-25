## Repro steps
1. Clone this repo and `cd` in to it
2. `earth --artifact +no-artifact/foo /tmp/stuff`

### What I would expect to happen
I would expect to get some error that says that foo doesn't exist

### What happens instead
The command appears to succeed, but there's nothing in `/tmp/stuff`