### Shidded Coin
![Image](https://github.com/shidcoin/SHIDCOIN/raw/main/src/shid_coin.jpg)
<center>
<a target="_blank" href="https://etherscan.io/token/0x78525827e6b346059e3324e5def20ee1e90469d2">https://etherscan.io/token/0x78525827e6b346059e3324e5def20ee1e90469d2</a>
</center>

<link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
<link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.8.1/css/all.css">
<script>document.getElementById("shidded-coin").style.display = "none";</script>


<!-- Add SHID to MetaMask -->
<button class="enableEthereumButton purchase_button addShidStyle w3-button w3-green">Add SHID to MetaMask</button>
<script src="https://cdn.jsdelivr.net/gh/ethereum/web3.js/dist/web3.min.js"></script>
<script type='text/javascript'>
    const ethereumButton = document.querySelector('.enableEthereumButton');
        ethereumButton.addEventListener('click', () => {
        const modifyHtml = (html) => {
          return html.replace('head data-n-head=""', 'head');
        };
        ethereum.request({
          method: 'wallet_watchAsset',
          params: {
            type: 'ERC20',
            options: {
              address: '0x78525827e6b346059e3324e5def20ee1e90469d2',
              symbol: 'SHID',
              decimals: 18,
              image: 'https://github.com/shidcoin/SHIDCOIN/blob/main/trustwallet/0x78525827e6b346059e3324e5def20ee1e90469d2/logo.png?raw=true',
            },
          },
        });
        });
</script>
<style>
.addShidStyle {
    position: fixed;
    right: 100px;
    top: 50px;
}
</style>

---
<!-- Social Platforms -->
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
<center>
    <h6>Social Platforms:</h6>
    <div style="width:100%;">
            <button class="w3-button w3-purple" onclick="window.location.href='https://discord.gg/N8fHVXgU5C'"><i class='fab fa-discord'></i> Discord</button>
            <button class="w3-button w3-red" onclick="window.location.href='https://www.reddit.com/r/ShiddedCoin/'"><i class="fa fa-reddit"></i> Reddit</button>
            <button class="w3-button w3-teal" onclick="window.location.href='https://www.instagram.com/shiddedcoin/'"><i class="fa fa-instagram"></i> Instagram</button>
    </div>
</center>
---

### What is Shidded Coin?

Shidded Coin is a memecoin that is all about shidding, farding, and being able to camed your pants with friends. It can be used to tip content creators, as a gift for strangers, and isn't as cringe as reddit gold.  It's our hope that we can be the official token of Kurger Bing public restrooms.  

---

### Why Invest?

Shidded Coin will allow investors and shitposters an opportunity to build the value of a new meme coin from the ground up and potentially realize capital gains in the form of Ethereum.

---

### What is the total supply of Shidded Coin in circulation?
There were 500 billion coins minted during the genesis of Shidded coin.

---

### Where can I purchase Shidded Coin?
<!-- Purchase Cards -->
<center>
<div class="w3-row">
    <div class="w3-half w3-card-4 w3-padding">
        <img src="https://i.redd.it/ap5cyb8yax071.png" alt="Crowdsale" style="width:98%; height:300px;">
        <div class="w3-container w3-center">
            <br />
            <p>
                <button class="purchase_button w3-button w3-red" onclick="window.location.href='https://shid.diamonds/crowdsale'">Purchase via Crowdsale!</button>
            </p>
        </div>
    </div>
    <div class="w3-half w3-card-4 w3-padding">
        <img src="https://i.redd.it/9euxz0oc5uz61.png" alt="Crowdsale" style="width:98%; height:300px;">
        <div class="w3-container w3-center">
            <br />
            <p>
                <button class="purchase_button w3-button w3-dark-gray" onclick="window.location.href='https://app.uniswap.org/#/swap?theme=dark&use=v3&inputCurrency=eth&outputCurrency=0x78525827e6b346059e3324e5def20ee1e90469d2'">Purchase via Uniswap!</button>
            </p>
        </div>
    </div>
</div>
</center>
<style>
.purchase_button {
  box-shadow: 0 8px 16px 0 rgba(0,0,0,0.2), 0 6px 20px 0 rgba(0,0,0,0.19);
}
</style>
<br clear="all" />

---

### How do I add Shidded Coin to MetaMask

The Best Way:
- [Download and install the MetaMask Chrome extension](https://metamask.io/download)
- Navigate to [shid.diamonds](https://shid.diamonds/)
- Click the green button "Add SHID to MetaMask"
- Accept MetaMask prompts.

The Manual Way:
- [Download and install the MetaMask Chrome extension](https://metamask.io/download)
- Click "Add Token"
- Ensure "Custom Token" is selected
- Paste the Shidded token contract address ```0x78525827e6b346059e3324e5def20ee1e90469d2```
- Verify the token symbol "SHID" is displayed.
- Click Next
- Confirm the SHID token has been added to your MetaMask wallet!

---

### How to increase the value of Shidded Coin?

Tell your friends, share SHID with them, make shidded memes.  Work with crypto jesus John Mcafee, mention Elon Musk a bunch on Twitter.

[Automated Market Makers](https://coinmarketcap.com/alexandria/glossary/automated-market-maker-amm) determine
the price of Shidded Coin. Automated market makers are smart contracts that create a liquidity pool of ERC-20 tokens, 
which are automatically traded by an algorithm rather than an order book. This effectively replaces a traditional limit order-book 
with a system where assets can be automatically swapped against the pool's latest price.

Simply put, the more Shidded Coins purchased, the higher the price goes.

---

### How was Shidded Coin created?

Shidded Coin is an ERC-20 token; it is defined in a smart contract within the Ethereum blockchain. Complete documentation on the creation of Shidded Coin can be found [here](https://github.com/shidcoin/SHIDCOIN/blob/main/docs/shid_creation_steps.md).
[Open Zeppelin's ERC-20 token template](https://github.com/OpenZeppelin/openzeppelin-contracts/blob/master/contracts/token/ERC20/ERC20.sol) was used to generate the Ethereum smart contract. [Open Zeppelin](https://openzeppelin.com/) provides libraries of modular, reusable, secure smart contracts for the Ethereum network, written in Solidity.
Please visit the [SHIDCOIN Github page](https://github.com/shidcoin/shidcoin) for further details.

---

### Support or Contacts

i just shidded and farded and camed my pants
