# go-imap-deleter

Delete older messages from an IMAP server.

Command-line flags:

| Flag  | Default  | Description |
|-------|----------|-------------|
| -s    | IMAP server name  | (read from console) |
| -p    | IMAP port address | 993                 |
| -u    | IMAP user name    | (read from console) |
| -P    | IMAP password     | (read from console) |
| -f    | Comma-separated list of folders | INBOX,INBOX.Drafts,INBOX.Sent,INBOX.Spam,INBOX.Trash | 
| -m    | Delete messages older than this amount of months | 24 | 
