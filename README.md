# (Partially) Secure Oblivious Random Access Memory

Secure Function Evaluation

## Garbled Circuit-based SORAM

#### Functions

* Function list


# Improvement Proposal Overview Title

> Boilerplate Improvement Proposal Project Git Repo `README` file

## Overview

*This is the overview explanation of the *proposal* project/improvement. Explain the purpose of the improvement.*

### Tested Against:
<!-- You can find specific versioning information used here at https://gist.github.com/sambacha/116b0dfc5c99cc8905545d63002b8f94 -->

| Version | Build | Date <br>(yyyy-mm-dd) |
| :---: | :---: | :---: |
| Version 0.6.4 | MDc6UmVsZWFzZTI0MzgwNTQ3 | 2020-03-10T15:26:16Z |



## Functions

*ORAM Functions for 
Click to see file details:

<details>
  <summary>EvalGC</summary>
  <br>

  GCTreeBasedORAM.decrypt

 
  <hr>
</details>

<details>
  <summary>ReplaceGC</summary>
  <br>

    GCTreeBasedORAM.decrypt_label_update

  <hr>
</details>

<details>
  <summary>UpdateGC</summary>
  <br>

  GCTreeBasedORAM.redeploy

  Image example of the **Rendered** FreeMarker file (if applicable)

  <hr>
</details>




<details>
  <summary>GCTreeBasedORAM.update_nodes</summary>
  <br>

  GCTreeBasedORAM.redeploy

  Image example of the **Rendered** FreeMarker file (if applicable)

  <hr>
</details>

<details>
  <summary>GCTreeBasedORAM.read_branch</summary>
  <br>

  Read ORAM Branch from node

  <hr>
</details>

## How to Deploy

```javascript
require('chai/register-should');
const PrivateKeyProvider = require("@truffle/hdwallet-provider");
const privateKey = "";
const privateKeyProvider = new PrivateKeyProvider(privateKey, "<URL>");


module.exports = {
	// See <http://truffleframework.com/docs/advanced/configuration>
	// for more about customizing your Truffle configuration!
	networks: {
		ropsten: {
			provider: privateKeyProvider,
			network_id: "3"
		}
	}
	compilers: {
		solc: {
			version: "0.5.16"
		}
	}
};
```

| Method              | Trigger                 |
| ------------------- |:----------------------- |
| Truffle | On creation of a Production Release. <br> Deployed to mainnet `chainid: 1` |
| Web3 Provider | On commit to branch with pattern `build/development`. <br> Deployed to `testnet` `ropsten`

## Change Log

*Store details about the releases of your improvement in the Change Log*

[Improvement Change Log](CHANGELOG.md)

## Other Information

*Explanation of other details about the project that may not have been included in the Overview.*


  [SORAM paper](https://lib.dr.iastate.edu/cgi/viewcontent.cgi?article=1264&context=cs_techreports)


## License

Semaphore
SPDX-License-Identifier: MIT 

