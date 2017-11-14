
PlatiGold development tree

PlatiGold is a PoS-based cryptocurrency.

PTG is dependent upon libsecp256k1 by sipa, the sources for which can be found here:
https://github.com/bitcoin/secp256k1


Block Spacing: 60 Seconds
Diff Retarget: Each Blocks
Maturity: 20 Blocks
Stake Minimum Age: 5 Hours

40 MegaByte Maximum Block Size (40X Bitcoin Core)

Port: 11784
RPC Port: 11785

PTG includes an Address Index feature, based on the address index API (searchrawtransactions RPC command) implemented in Bitcoin Core but modified implementation to work with the PTG codebase (PoS coins maintain a txindex by default for instance).

Initialize the Address Index By Running with -reindexaddr Command Line Argument.  It may take 10-15 minutes to build the initial index.

