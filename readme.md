#### config

```
PlatonRPC: `https://openapi2.platon.network/rpc`
```

ChianID:210425

```
Token Symbol: LAT
```

contractaddress:0xC38Ff5Bb9118465e130Ef53C18a9B00F4497CBE7

````

### e.g.

```javascript
await ArtistMe.createToken(
  "https://gateway.pinata.cloud/ipfs/QmX6iuhes6Q78VAeUFYEYSARDVkEn6qXxaEoiAwoNhamQk",
  parentAddress
);

await ArtistMe.createTokenAndList(
  "https://gateway.pinata.cloud/ipfs/QmX6iuhes6Q78VAeUFYEYSARDVkEn6qXxaEoiAwoNhamQk",
  auctionPrice,
  parentAddress,
  { value: listingPrice }//value here must equal to listingPrice
);
//listingprice ，default is 0
//parentAddress
````
