# Usage 

# switchChain(chainID) : 

This Methods Takes An Input of chainID and triggers transaction in Metamask Which Changes the Chain of user Whenever Required and it returns null . 

------------------------

# getPublicEncryptionKey() :

This Method provides you with your metamask wallet's Public key and it returns public Encryption Key .

---------

# connectAccount() : 

This Method Returns the account i.e. is connected with Metamask and takes no Parameters

-----------

# signMessage(InputMsg:string) : 

This method digitally Signatures your msg and it returns meatamsk transaction for signature . 

----------

# getBlockNumber() : 

This Method returns Latest BlockNumber in Hexadecimal Format 

--------


# getchainId() : 

This Method Will Return ChainID of Conneted Metamask Account

-----

# getGasPrice() :

This Method Will Return Actual gas Price in WEI Divide That by 10^19 to get it in ethers . It is average Gas Price for the transaction . 

--------------

# getBalance() :

This Method will Return balance of the connected account in WEI and dividing it by 10^19 it will give in ethers 

---------------

# getBlockinformation(blockNumber) : 
 
This will Return One Object in JSON form Which Contains blocknumber , blockchash and all transactions happended on that particular block and This transactions can be verified on Any Network platform 

---

# getTransactionCountofBlock(blockNumber) :

This will be Return Number of transactions Happened on that block . It retruns Integer Number 

----

# getTransactionInformation(blockNumber, transactionCount) : 

After getting Transaction Count of blocknumber You can get Particular Transaction Information with this . You Have to Enter Transaction Number in Hex Value like 0x0  for 0 , 0x1 for 1 . Number here indicates index of transaction i.e. First , Second and so ... . If you Entered wrong Trnaction it will return Null . 

----

  ### Thanks For Reading >>> !!! 🦞    