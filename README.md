# Bitcoin Private Key Miner

This software will  attempt to create a bitcoin address collision. If a key is found the key will be reported to the pool. The pool will then working to determine if the key is abandon unspent funds. Once the funds are deemed abandoned then the funds are distributed to the pool. 

 

# Install

You can run llminer in Windows or Linux. In order to run using Linux you have to download dotnet core 5.0.  

## For Windows
    c:\..\llminer.exe
    
## For Linux
Requires sudo apt install unzip

    $ wget https://github.com/oneitguy/llminer/releases/download/latest/llminer.zip
    $ unzip llminer.zip    (or  tar -xf llminer.zip) 
    $ dotnet llminer.dll


# Configure

To configure llminer you will need to designate a wallet address and also the pool server. If the address.worker are already in use you will need to 
Example

    "worker": "0xcE3b27807B13f1c68FeC0a67887eea6382C7094C.worker1",
    "server": "https://keymaker.cc/api"

 

##  Whitelist

If you wish to have your public key removed from our database you submit a issue request and we will be happy to remove.   
