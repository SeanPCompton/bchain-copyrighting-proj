
later...could expand it, ie integrating payment system like ERC-20 tokens for license fees?

From Cyfrin course work adapted
Register Copyright:

Creators can register a new work by providing its name and an IPFS hash pointing to its metadata.
The contract assigns a unique copyrightId and stores the creator’s address as the owner.

The owner can grant a license for the work by specifying the licensee, price, and duration.
Licenses are stored in a list, and an event is emitted for each license.

Copyright ownership can be transferred to another address.

Anyone can query the licenses associated with a specific copyrightId.


Deploy the Contract:

Use Remix, Hardhat to deploy the contract on a testnet?

Register a work with a sample IPFS hash (e.g., metadata.json stored on IPFS).
Grant a license to a test address.
Transfer ownership of a work to another address.
Retrieve licenses for a specific work.

