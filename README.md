pimapsync
=========

An small tool to copy messages from one IMAP mailbox to another mailbox

It is not meant to be used as a synchronization tool but rather as a one time migration tool. Though, it will check if a message on the destination box exists and skip it if it does. It will also create any missing folders. It should be safe to run it consecutively.

[Original script](http://projects.webmind.be/snippets/copy_imap_mailbox.phps) by Glenn Matthys (glenn@webmind.be) up to version 1.2