# "MVP" 

[Metaplex documentation ](https://docs.metaplex.com/guides/archived/candy-machine-v2/getting-started)

~~~ 
[Requirements]
solana-cli>latest version
git clone https://github.com/metaplex-foundation/deprecated-clis.git ~/deprecated-clis
~~~

## [commands]
~~~
[set enviroment to mainnet]
solana config set --url https://api.mainnet-beta.solana.com
[upload colection]
ts-node gh_metaplex-foundation_metaplex/js/packages/cli/src/candy-machine-v2-cli.ts upload -e mainnet-beta -k /root/.config/solana/devnet_1.json -cp config.json -c nft_app_test assets/
[verify upload]
ts-node gh_metaplex-foundation_metaplex/js/packages/cli/src/candy-machine-v2-cli.ts verify_upload -e mainnet-beta -k /root/.config/solana/devnet_1.json -c nft_app_test assets/
[mint token]
ts-node gh_metaplex-foundation_metaplex/js/packages/cli/src/candy-machine-v2-cli.ts mint_one_token -e mainnet-beta -k /root/.config/solana/devnet_1.json -c nft_app_test assets/
~~~
## [collections deployed]
~~~
collection_1#
<storage: nft.storage>
  Candy machine address:  DmQoBUcsNUBQqSfTzShV1r41zBnNnzXJzk26FbmWz3TW
  Collection metadata address:  AvRk3pqqhYf7gHfRV3tyvGxS9E1iyj3nZVDWkpLm1LhR
  Collection metadata authority:  BUoLxaTAr9aprnAR4cygkqSfR3DoBJEmHTZc16KoUEBT
  Collection master edition address:  HXptu25Mqssqsr6T25JT7FDkv9jK4zkeMZUMHaYz1Xqd
  Collection mint address:  HAVjmfi8ccRqk4eWF6UnS7YaXegSpDkrB9ebUA8XNtXv
  Collection PDA address:  8XnQdK3ySRJqBRzHVSkbJ8NgxUyQuvvZxmej5eAbmLCR
  Collection authority record address:  AfUbJffVWhNWL5nzq9sKSdkJNKG1WvB23f4aVmot9T4v
  Collection:  {
    collectionMetadata: 'AvRk3pqqhYf7gHfRV3tyvGxS9E1iyj3nZVDWkpLm1LhR',
    collectionPDA: '8XnQdK3ySRJqBRzHVSkbJ8NgxUyQuvvZxmej5eAbmLCR',
    txId: '5DYoAqkb7TBsWzty9YusmpScSZ1oqjds445w7bnKkmGVrp3CvoaUNF6MQNimuNpHvx1ceeKonFndShgBRhse873R'
  }
~~~
__[mint token account]__ `Hn8GMLSHnqHxrMpJtUwZGsbKXRjFFdYNNCXcpNJo9c9N`
[solscan link](https://solscan.io/token/Hn8GMLSHnqHxrMpJtUwZGsbKXRjFFdYNNCXcpNJo9c9N#trades)

~~~
collection_2#
<storage: awsS3Bucket>
  Candy machine address:  wMy8tT9TFdLFd8Vdc8iZatCztsSpZzo95JwZzt9z28q
  Collection metadata address:  6hCPHUasHwKgvrNLPNauXe8cy9MnEMdZ1AC6WfFhWSQN
  Collection metadata authority:  BUoLxaTAr9aprnAR4cygkqSfR3DoBJEmHTZc16KoUEBT
  Collection master edition address:  Hs373oDPka5aq3jtzULAJM98LpMFsqydnYVeTJjTkU7U
  Collection mint address:  DeYG2qF64DD3XKoCbQuq5Mi51szemXGEAgwUVcg6NEv7
  Collection PDA address:  GBFTn1eqeU9naEPUWfEYB1rgeyx8VFLToTnBZmqdbZZp
  Collection authority record address:  AtgxPv3GpdwnuGJmdwUyuRtVasw7k8aN2CAuwbcGgJQD
  Collection:  {
    collectionMetadata: '6hCPHUasHwKgvrNLPNauXe8cy9MnEMdZ1AC6WfFhWSQN',
    collectionPDA: 'GBFTn1eqeU9naEPUWfEYB1rgeyx8VFLToTnBZmqdbZZp',
    txId: 'Mt6TNt6ssrM97F6MyLtREv8hiC5xPbhVinfCxkxoAWqWwBSyuphznvyfamNrJFgJ9N7ePfUYSc39vJBsiG49EYT'
  }
~~~
__[mint token acount]__ `HzfHMnaFckdkZFu9kxfQC7zpTNZEAe3bTZfL4nNMso85`
  [solscan link](https://solscan.io/token/HzfHMnaFckdkZFu9kxfQC7zpTNZEAe3bTZfL4nNMso85#trades)  
