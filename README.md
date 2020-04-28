<h1>Proof of Auth and Proof of Work in local blockchain</h1>

<h1> RocketChain<h1>



<h2>Local blockchain: step by step</h2>


1. <p>Create local network and Genesis Block using <code>puppeth</code></p>


![](https://github.com/NinoslavVasic/RocketChain/blob/master/Screenshots1/1_add_rocketchain_puppeth.png)


2. <p> New genesis configuration </p>


![](https://github.com/NinoslavVasic/RocketChain/blob/master/Screenshots1/2_genesis_conf.png)


3. <p> Generate and export json files into specific folder. <p>
   <p> NOTE: only rocketchain.json is needed in further development</p>


![](https://github.com/NinoslavVasic/RocketChain/blob/master/Screenshots1/3_gen_exp_json.png)


4. <p> Using <code>geth</code> create 2 virtual nodes on rocketchain network <p>
   <p>node1</p>


![](https://github.com/NinoslavVasic/RocketChain/blob/master/Screenshots1/4_cre_node1.png)


   <p> node2 </p>

![](https://github.com/NinoslavVasic/RocketChain/blob/master/Screenshots1/5_cre_node2.png)


5. <p> Initialize and tell the nodes to use <code>rocketchain</code> genesis block! </p>

   <p> NOTE: At this point rocketchain.json file should be used to initialize node1 and node2</p>


![](https://github.com/NinoslavVasic/RocketChain/blob/master/Screenshots1/6_init_node1.png)


6. <p> Open separate GitBash to start 'rocketchain' mining node1 <p>

   <p> NOTE: IT IS IMPORTANT TO CONNECT NODES  by entering enode of the node1 when running node2 mining </p>

![](https://github.com/NinoslavVasic/RocketChain/blob/master/Screenshots1/7_minthread_node1.png)

7. <p> Open separate GitBash to start up mining full thread on 'rocketchain' - mining node2 </p>

   <p> NOTE: IT IS IMPORTANT TO CONNECT NODES  by entering enode of the node1 when running node2 mining</p>

![](https://github.com/NinoslavVasic/RocketChain/blob/master/Screenshots1/8_minthread_node2.png)

   <p> For purpose of connecting local blockchain to a digital wallet one have to create it. In this exercise, I used MyCrypto, protected with the mnemonic phrase. It is important to keep the wallet keys in a safe place in order to protect the funds in your wallet.</p>

8. <p>  Chose Kovan network and login to your wallet </p>
   <p> Make sure that Kovan  network is chosen and then login with Mnemonic phrase</p>


![](https://github.com/NinoslavVasic/RocketChain/blob/master/Screenshots1/9_mycrypto.png)

9. <p> Chose wallet to pre-fund </p>

   <p> Unlock the wallet you want to use for pre-funding and click unlock. </p>

![](https://github.com/NinoslavVasic/RocketChain/blob/master/Screenshots1/10_mn_login.png)

10. <p> Wallet info - private key </p>
    <p> After login to your wallet chose wallet info from dropdown menu, copy private key and store it in safe file.  </p>

![](https://github.com/NinoslavVasic/RocketChain/blob/master/Screenshots1/11_wallet_priv_key.png)

11. <p> Set Up Your Custom Node </p>

    <p> Open up MyCrypto, then click Change Network at the bottom left. Click "Add Custom Node", then add the custom network information that you set in the genesis.</p>

    <p>Make sure that you scroll down to choose Custom in the "Network" column to reveal more options like Chain ID.</p>


![](https://github.com/NinoslavVasic/RocketChain/blob/master/Screenshots1/12_add_custom_node.png)

12. <p> RocketChain Network </p>

    <p> On the left bottom side of the screen, click on the "change network" and scroll down to the newly created Rocketchain network.  </p>

![](https://github.com/NinoslavVasic/RocketChain/blob/master/Screenshots1/13_access_rocch.png)

   
   <p> Chose rocketchain network and login with private key which you have previously stored in a safe file.  </p>

![](https://github.com/NinoslavVasic/RocketChain/blob/master/Screenshots1/13.1_my_crypto_login_pk.PNG)



13. <p> Transaction Initiation </p>


![](https://github.com/NinoslavVasic/RocketChain/blob/master/Screenshots1/14_transaction_initiation.PNG)

14. <p> Confirm if everyting is valid before executing transaction and click on the button. </p>

![](https://github.com/NinoslavVasic/RocketChain/blob/master/Screenshots1/15_confirm_transaction.PNG)


15. <p> Confirmation of Executed Transaction </p>

![](https://github.com/NinoslavVasic/RocketChain/blob/master/Screenshots1/16_transaction_confirmation.PNG)



16. <h3> GREAT: Succesfully Executed Transaction <h3>

![](https://github.com/NinoslavVasic/RocketChain/blob/master/Screenshots1/17_succesfull_transaction.PNG)


<footer>
    
Copyright 2020 Columbia Engineering - FinTech Bootcamp NVasic
    
    
</footer>




