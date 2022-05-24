# ❗️VERY IMPORTANT❗️

1) Use png formatted images for logo.
2) Logo image size should be less than 20KB.
3) Do not forget to add commas after curly braces in JSON files. [{...token info...}, {...another token info...}]
4) Insert correct address of token with uppercase letters.

    ❌:`0x4826634fe187ed3ffb64d77c5c1a67ba49cc03de`

    ✅:`0x4826634Fe187Ed3FFb64d77c5C1A67Ba49cc03dE`

# xdc-token-list
The most popular tokens on XinFin Network


## How to add logo and token to suggested list?

- Fork this repo and create a new branch.
- In the `assets` folder, create a new directory and call it as your token address.
- Add logo.png file inside of that directory
- Open `mainnet.tokenlist.json` file and add your token info after the last token description under `"tokens"` key.
- Push your branch and create pull request to the master branch.

---

## Example of editing `mainnet.tokenlist.json` file
- Before:
```
...
"tokens": [
    ...,
    {
      "chainId": 50,
      "address": "0x951857744785E80e2De051c32EE7b25f9c458C42",
      "name": "Wrapped XDC",
      "symbol": "WXDC",
      "decimals": 18
    }
 ]
```
- After:
```
...
"tokens": [
    ...,
    {
      "chainId": 50,
      "address": "0x951857744785E80e2De051c32EE7b25f9c458C42",
      "name": "Wrapped XDC",
      "symbol": "WXDC",
      "decimals": 18
    },
    {
     "chainId": 50,
      "address": "your_token_address",
      "name": "YOUR TOKEN NAME",
      "symbol": "YOUR TOKEN SMBL",
      "decimals": 18
    }
 ]
```

---
If you have a problem with git you can contact @romanow_org
