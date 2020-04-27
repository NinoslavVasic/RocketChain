<h1>RocketChain - Proof of Auth and Proof of Work in local blockchain</h1>


<h2>Simplified manual how to create local blockchain</h2>


<h3>Create local network and Genesis Block using <code>puppeth</code></h3>


![](https://github.com/NinoslavVasic/RocketChain/blob/master/Screenshots1/1_add_rocketchain_puppeth.png)


<h2>New genesis configuration</h2>


![](https://github.com/NinoslavVasic/RocketChain/blob/master/Screenshots1/2_genesis_conf.png)


<h2>Generate and export json files into specific folder.   NOTE: only rocketchain.json is needed in further development</h2>


![](https://github.com/NinoslavVasic/RocketChain/blob/master/Screenshots1/3_gen_exp_json.png)


<h2>Using <code>geth</code> create 2 virtual nodes on rocketchain network</h2>

<h2>node1</h2>


![](https://github.com/NinoslavVasic/RocketChain/blob/master/Screenshots1/4_cre_node1.png)

<h2>NOTE:  node2</h2>

![](https://github.com/NinoslavVasic/RocketChain/blob/master/Screenshots1/5_cre_node2.png)


<h2>Initialize and tell the nodes to use <code>rocketchain</code> genesis block!</h2>

<h2>NOTE: At this point rocketchain.json file should be used to initialize node1 and node2</h2>


![](https://github.com/NinoslavVasic/RocketChain/blob/master/Screenshots1/6_init_node1.png)


<h2>Open separate GitBash to start 'rocketchain' mining node1</h2>

<h3>NOTE: IT IS IMPORTANT TO CONECT NODES  by entering enode of the node1 when running node2 mining</h3>

![](https://github.com/NinoslavVasic/RocketChain/blob/master/Screenshots1/7_minthread_node1.png)

<h2>Open separate GitBash to start up mining full thread on 'rocketchain' - mining node2</h2>

<h3>NOTE: IT IS IMPORTANT TO CONECT NODES  by entering enode of the node1 when running node2 mining</h3>

![](https://github.com/NinoslavVasic/RocketChain/blob/master/Screenshots1/8_minthread_node2.png)


<h2>Chose Kovan network and login to your wallet</h2>
<p> Make sure that Kovan st network is chosen and then login with Mnemonic phrase</p>


![](https://github.com/NinoslavVasic/RocketChain/blob/master/Screenshots1/9_mycrypto.png)

<h2>Chose wallet to pre-fund</h2>

<p> Unlock the wallet you want to use for pre-funding and click unlock. </p>

![](https://github.com/NinoslavVasic/RocketChain/blob/master/Screenshots1/10_mn_login.png)

<h2>Wallet info - private key</h2>
<p> After login to your wallet chose wallet info from dropdown menu, copy private key and store it in safe file.  </p>

![](https://github.com/NinoslavVasic/RocketChain/blob/master/Screenshots1/11_wallet_priv_key.png)

<h2>Set Up Your Custom Node</h2>
<p> Open up MyCrypto, then click Change Network at the bottom left:  </p>

<p>Click "Add Custom Node", then add the custom network information that you set in the genesis.</p>

<p>Make sure that you scroll down to choose Custom in the "Network" column to reveal more options like Chain ID:</p>


![](https://github.com/NinoslavVasic/RocketChain/blob/master/Screenshots1/12_add_custom_node.png)

<h2>RocketChain Network </h2>
<p> Chose rocketchain network and login with private key which you have previously stored in a safe file.  </p>


![](https://github.com/NinoslavVasic/RocketChain/blob/master/Screenshots1/13_access_rocch.png)


<h2>Transaction Initiation</h2>


![](https://github.com/NinoslavVasic/RocketChain/blob/master/Screenshots1/14_transaction_initiation.PNG)

<h2>Confirm if everyting is valid before executing transaction and click on the button. </h2>

![](https://github.com/NinoslavVasic/RocketChain/blob/master/Screenshots1/15_confirm_transaction.PNG)


<h2>Confirmation of Executed Transaction/h2>

![](https://github.com/NinoslavVasic/RocketChain/blob/master/Screenshots1/16_transaction_confirmation.PNG)



<h2>GREAT: Succesfully Executed Transaction</h2>

![](https://github.com/NinoslavVasic/RocketChain/blob/master/Screenshots1/17_succesfull_transaction.PNG)






