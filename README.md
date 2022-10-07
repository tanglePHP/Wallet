
![](.meta/Banner.png)

>#### Please be aware that this Examples are in an early development state and the API of the library as well as the "Stardust" protocol is subject to change, it is NOT ready to use in production.

  <a href="https://discord.iota.org/" style="text-decoration:none;"><img src="https://img.shields.io/badge/Discord-9cf.svg?style=social&logo=discord" alt="Discord"></a>
  <a href="https://twitter.com/tanglePHP/" style="text-decoration:none;"><img src="https://img.shields.io/badge/Twitter-@tanglePHP-9cf.svg?style=social&logo=twitter" alt="Twitter"></a> ‖
  <a href="https://www.tanglephp.com/" style="text-decoration:none;"><img src="https://img.shields.io/badge/tanglePHP-grey?style=flat-square&logo=tanglePHP" alt="Shimmer"></a>
  <a href="https://www.iota.org/" style="text-decoration:none;"><img src="https://img.shields.io/badge/IOTA-grey?style=flat-square&logo=iota" alt="IOTA"></a>
  <a href="https://www.shimmer.network/" style="text-decoration:none;"><img src="https://img.shields.io/badge/Shimmer-grey?style=flat-square&logo=shimmer" alt="Shimmer"></a> ‖
  <a href="https://www.php.net/" style="text-decoration:none;"><img src="https://img.shields.io/badge/PHP->= 8.1.x-blue?style=flat-square&logo=php" alt=">PHP 8"></a>
  <a href="https://github.com/iota-community/iota.php/LICENSE" style="text-decoration:none;"><img src="https://img.shields.io/badge/license-Apache--2.0-green?style=flat-square" alt="Apache-2.0 license"></a>

---

# About

**PHP Wallet for Shimmer/IOTA (Stardust)**

_The aim of the this lib is to offer PHP developers an easy way to interact with the Stardust protocol._

---

# Currently possible

#### PHP Wallet for Shimmer/IOTA (Stardust)

- [x] open Wallet
- [x] create Addresses
- [x] check Balance
- [x] transfer Tokens
- [ ] ~~mint, burn, transfer NFTs~~
- [ ] ~~mint, burn, transfer nativeTokens~~

# Requirements

+ PHP 8+
+ PHP Library:
    + [tanglePHP/singlenode-client](https://github.com/tanglePHP/singlenode-client)

# Example

```php
<?php
  // include tanglePHP autoload from tanglePHP/bundle
  require_once("autoload.php");
  // create network connection
  $network = new \tanglePHP\Network\Connect('shimmer:testnet');
  // Open wallet
  $wallet    = new \tanglePHP\Wallet\Run($seedInput, $network->singleNode);
```

---

## Joining the discussion

<a href="https://discord.iota.org/" style="text-decoration:none;"><img src="https://img.shields.io/badge/Discord-9cf.svg?style=social&logo=discord" alt="Discord"></a>
<a href="https://twitter.com/tanglePHP/" style="text-decoration:none;"><img src="https://img.shields.io/badge/Twitter-@tanglePHP-9cf.svg?style=social&logo=twitter" alt="Twitter"></a>

If you want to get involved in the community, need help with getting set up, have any issues or just want to discuss IOTA/Shimmer, feel free to join our
IOTA/Shimmer [Discord](https://discord.iota.org/) and post in the #php channel.

![](.meta/Help_DiscordPhpChannel.png)


___

## Social

> Follow me on  [Twitter @tanglePHP](https://twitter.com/tanglePHP)

> Follow me on [Soonaverse](https://soonaverse.com/space/0xb62ff484cb5f512eb0a110055511b3f4a57467a9/overview)

---

## Donation

It took me a lot of time to develop the **tanglePHP** libs and need to pay for the server every month. If you want to support me or if my work helps you, kindly consider a small
donation.

**IOTA Address:**

```
iota1qpw8lvfgz6gt9u8qtcjmmez3vtqve6fdzqkdaah9wdz9llgvhs3psrtx5xd
```

**Get a cool NFT Animation:**

[Collection](https://soonaverse.com/space/0xb62ff484cb5f512eb0a110055511b3f4a57467a9/collections) |
[Bronze Support](https://soonaverse.com/collection/0x17597da5756e1dc65d733318195bbd951b8eeb89) |
[Silver Support](https://soonaverse.com/collection/0x9d4434ae8ac2e53e532ef4e260b408caadb8c917) |
[Gold Support](https://soonaverse.com/collection/0xfd98a0c6f15a6ce2660c1e3031fa81f1e54e632d) |
[Diamond Support](https://soonaverse.com/collection/0xbb11d1c78249e93fd49992a55dde2605f87ddbdb)

---

### License

The Apache 2.0 license can be found [here](LICENSE).