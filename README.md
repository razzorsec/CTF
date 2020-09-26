# Blockchain-HACON2020
Blockchain Challs from HACON2020 CTF

# Hide & Seek

Network: Ropsten Test Network  
Address: 0xD1F1588598352C73E3797d3F28eAFeCb638700bB

# I WannaCry...

Can you find out which wallet has sent the most money to the involved address in the month of August, 2020?  
Address: 12t9YDPgwueZ9NyMgw519p7AA8isjr6SMw  
Flag format: HACSEC{Address}

# Shards

Do you know RazzorSec is there, on most of the social medias?  
Network: Ropsten Test Network  
Address: 0x9b33546A142F163D932ab70258e7AA36fbBa787A  
ABI:  
```[

	{

		"constant": true,

		"inputs": [

			{

				"internalType": "string",

				"name": "_password",

				"type": "string"

			}

		],

		"name": "FeedMeFlag",

		"outputs": [

			{

				"internalType": "string",

				"name": "",

				"type": "string"

			}

		],

		"payable": false,

		"stateMutability": "view",

		"type": "function"

	}

]
```

# Unlock Me
Hint: Find the result.(No Unintended Way)  
Flag Format: HACSEC{result}  
Address: 0xdd42d04096d27274e72b9807cd19cc66c2dbeafc  
ABI:  
```[

	{

		"constant": false,

		"inputs": [],

		"name": "feedme",

		"outputs": [],

		"payable": true,

		"stateMutability": "payable",

		"type": "function"

	},

	{

		"inputs": [],

		"payable": false,

		"stateMutability": "nonpayable",

		"type": "constructor"

	},

	{

		"constant": true,

		"inputs": [],

		"name": "flag",

		"outputs": [

			{

				"internalType": "bytes20",

				"name": "result",

				"type": "bytes20"

			}

		],

		"payable": false,

		"stateMutability": "view",

		"type": "function"

	},

	{

		"constant": true,

		"inputs": [],

		"name": "owner",

		"outputs": [

			{

				"internalType": "address",

				"name": "",

				"type": "address"

			}

		],

		"payable": false,

		"stateMutability": "view",

		"type": "function"

	},

	{

		"constant": true,

		"inputs": [

			{

				"internalType": "address",

				"name": "",

				"type": "address"

			}

		],

		"name": "solved",

		"outputs": [

			{

				"internalType": "bool",

				"name": "",

				"type": "bool"

			}

		],

		"payable": false,

		"stateMutability": "view",

		"type": "function"

	}

]
```
