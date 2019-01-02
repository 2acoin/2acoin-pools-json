# 2acoin-pool-list ![](./2acoin_logo.png)

The goal of this repository is to have a central list of pools for 2ACoin (https://www.2acoin.org) mining.  

If you run a pool, please submit a Pull Request against *v1/2acoin-pools.json* to get added.

This list can be consumed in your application so you'll always have an up-to-date list of pools. To consume the list, just use the following URL: [https://raw.githubusercontent.com/2acoin/2acoin-pools-json/master/v1/2acoin-pools.json](https://raw.githubusercontent.com/2acoin/2acoin-pools-json/master/v1/2acoin-pools.json)

## Contributing

Please add your pool to the list in **alphabetical order**, named using CamelCase.domain style, and **include trailing slashes** for the `url` and `api` values.

**e.g.**

    {
        "name" : "MyPool.com",  
        "url" : "https://arms.mypool.com/",  
        "api" : "https://arms.mypool.com/api/",  
        "type" : "node.js"  
    },


### Possible values for 'type'
 - forknote
 - forknote-alt
 - node.js
 - other
