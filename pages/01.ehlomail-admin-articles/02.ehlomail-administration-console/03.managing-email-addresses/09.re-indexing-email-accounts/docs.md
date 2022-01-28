---
title: 'Re-indexing a mailbox'
taxonomy:
    category:
        - docs
visible: true
---

Mail messages and attachments are automatically indexed before messages are deposited in a mailbox. Each mailbox has an index file associated with it. This index file is required to retrieve search results from the mailbox.

If a mailbox's index file becomes corrupt or is accidentally deleted, you can re-index the messages in the mailbox. Messages and attachments in all the user's folders are re-indexed.

Re-indexing a mailbox's contents can take some time, depending on the number of messages in the mailbox. Users can still access their mailbox while re-indexing is running, but because searches cannot return results for messages that are not indexed, searches may not find all results.

###Procedure

1.  Select the account and in the gear icon select <span style="font-weight: bold;">Edit</span>.  The selected account opens.

2.  Click <span style="font-weight: bold;">Reindex Mailbox</span> on the account's tool bar. This opens the Reindex dialog.

3.  Click <span style="font-weight: bold;">Start Reindexing</span>.<span class="Important">  

    Caution:</span>  When you click <span style="font-weight: bold;">Start Reindexing</span>, the first action is to delete the existing index file. If re-indexing is cancelled before the re-index process is complete, the user's mailbox is partially indexed and searches may not return the right results.

4.  Click <span style="font-weight: bold;">OK</span>, to close the dialog. Closing the dialog does not stop the re-indexing process. Re-indexing runs in background.

You can check the status of the re-indexing process at any time. Select the account and click <span style="font-weight: bold;">Edit</span>, then click <span style="font-weight: bold;">Reindex Mailbox</span>. A progress bar is displayed.