## Welcome to SHID coin

<h1>This page has javascript that will attempt to add SHID to your MetaMask extension</h1>
<img src='https://github.com/shidcoin/SHIDCOIN/raw/main/src/SHIDDED.jpeg' />
<br />
<link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
<button class="w3-button w3-green enableEthereumButton">Add SHID to MetaMask</button>


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
      address: '0xc3b78abb13c4aba76d8b370a9f83aeb948c692e7',
      symbol: 'SHID',
      decimals: 18,
      image: 'https://github.com/shidcoin/SHIDCOIN/raw/main/src/SHIDDED.jpeg',
    },
  },
});
});
</script>



















You can use the [editor on GitHub](https://github.com/shidcoin/shidcoin.github.io/edit/main/index.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/shidcoin/shidcoin.github.io/settings/pages). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contacts

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.