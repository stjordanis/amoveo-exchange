======= Erlang

balance_veo sync should be automatically called to sync transactions from recent blocks.

* We should periodically scan all the unconfirmed trades to see if any can be confirmed. use unconfirmed_veo_feeder:confirm_all().
* loading veo into order book needs to be tested.

Write bitcoin stuff to mimic veo stuff:
* write history_bitcoin
* write balance_bitcoin
* write unconfirmed_bitcoin
* write unconfirmed_bitcoin_feeder
* loading bitcoin into the order book.


* matching trades in the order book.
- cron job to periodically match trades in the order book.

* keep a backup of all gen_server data to the hard drive

balance_veo:remove should be called "reduce".

======= JS

use the 2 api commands:
* make a trade
* look up a trade's status by ID.
