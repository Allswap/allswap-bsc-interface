# Adding Tokens

1. Fork the [AllSwap Dex Interface](https://github.com/Allswap/allswap-bsc-interface/) repository on GitHub
2. Upload your **logo** in a 96\*96px transparent .png format to the `/public/images/coins` directory. Please name the logo as your symbol in uppercase.

3. Add your **token information** using the example format provided below to `allswap.json` in the `/src/constants/token/` directory.

4. Create a **pull request** detailing information about your project, website address, and contact details (telegram)

## Examples

**Logo format:**

`SYRUP.png`

**Token information format:**

```json
{
"name": "AllSwap Token",
"symbol": "ADF",
"address": "0xBce4176a20ca7ad0ff2350567463f5AAa632fad0",
"chainId": 56,
"decimals": 18,
"logoURI": "/images/coins/ADF.png"
},
```

If you're not comfortable with GitHub pull requests, please open a [new issue](https://github.com/Allswap/allswap-bsc-interface/issues/new) requesting to be added.

## Reviews

Once added, tokens are also re-reviewed at regular intervals in order to maintain quality assurance in-line with the below criteria, and may be removed should severe and/or unresolved issues be encountered.

### Criteria

- Volume
- Liquidity
- Community feedback
