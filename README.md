bitcoin-payment-protoc-php
==========================

Compilation of Bitcoin paymentrequest.proto to PHP.

https://github.com/bitcoin/bips/blob/master/bip-0070/paymentrequest.proto
protoc --plugin=protoc-gen-php=protoc-gen-php.php --php_out=. paymentrequest.proto
