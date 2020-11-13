# Contracts

List of compiled ENS smart contracts

## How to install

```
npm install --save '@ensdomains/contracts'

```

## How to use

```
import { abi as ensContract } from 'ensdomain-contracts/abis/ens/ENS.json'
import { abi as reverseRegistrarContract } from 'ensdomain-contracts/abis/ens/ReverseRegistrar.json'
import { abi as oldResolverContract } from 'ensdomain-contracts/abis/ens-022/PublicResolver.json'
import { abi as resolverContract } from 'ensdomain-contracts/abis/resolver/Resolver.json'
import { abi as testRegistrarContract } from 'ensdomain-contracts/abis/ens/TestRegistrar.json'
import { abi as dnsRegistrarContract } from 'ensdomain-contracts/abis/dnsregistrar/DNSRegistrar.json'
import { abi as legacyAuctionRegistrarContract } from 'ensdomain-contracts/abis/ens/HashRegistrar'
import { abi as deedContract } from 'ensdomain-contracts/abis/ens/Deed'
import { abi as permanentRegistrarContract } from 'ensdomain-contracts/abis/ethregistrar/BaseRegistrarImplementation'
import { abi as permanentRegistrarControllerContract } from 'ensdomain-contracts/abis/ethregistrar/ETHRegistrarController'
import { abi as bulkRenewalContract } from 'ensdomain-contracts/abis/ethregistrar/BulkRenewal'
```


## How to add new contract

1. `yarn add --dev PACKAGENAME`
2. Add the package into `copy.rb`
3. Run `yearn pub` which runs `copy.rb` and publish the repo
