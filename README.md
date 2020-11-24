# Open mutt on message with fixed Message-ID 

This script attempt to find message with some Message-ID in network and local mailboxes and open mail with mutt. It use mutt  hcache (Tokio cabinet) for fast scan of the imap[s] folders.

You must install Tokio cabinet bin utils. In Debian or Ubuntu:

`apt-get install tokyocabinet-bin`

Copy binary to `$PATH` make executable and use:

`open-mutt-on-message-id '<20180412100605@294551909.5554770.no.ru>'`

I use this script as helper in [https://github.com/petrovag/taskfzf]


