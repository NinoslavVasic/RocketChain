<h1>Proof of Auth and Proof of Work in local blockchain</h1>

<h1> <strong>RocketChain</strong> <h1>

<p>__________________________________________________________</p>

<h2>Local blockchain: step by step</h2>

<ol>
<h3>Create local network and Genesis Block using <code>puppeth</code></h3>
</ol>

<p><img src="https://github.com/NinoslavVasic/RocketChain/blob/master/Screenshots1/1_add_rocketchain_puppeth.png" alt="" title="" /></p>

<ol>
<h3> New genesis configuration </h3>
</ol>

<p><img src="https://github.com/NinoslavVasic/RocketChain/blob/master/Screenshots1/2_genesis_conf.png" alt="" title="" /></p>

<ol>
<h3>Generate and export json files into specific folder. <h3>
</ol>


<p><img src="https://github.com/NinoslavVasic/RocketChain/blob/master/Screenshots1/3_gen_exp_json.png" alt="" title="" /></p>

<p><ol>
<h3> Using <code>geth</code> create 2 virtual nodes on rocketchain network <h3>
</ol>


<p><img src="https://github.com/NinoslavVasic/RocketChain/blob/master/Screenshots1/4_cre_node1.png" alt="" title="" /></p>

<h4> node2 </h4>

<p><img src="https://github.com/NinoslavVasic/RocketChain/blob/master/Screenshots1/5_cre_node2.png" alt="" title="" /></p>

<p><ol>
<h3> Initialize and tell the nodes to use <code>rocketchain</code> genesis block! <h3>
</ol>


<p><img src="https://github.com/NinoslavVasic/RocketChain/blob/master/Screenshots1/6_init_node1.png" alt="" title="" /></p>

<p><ol>
<h3> Open separate GitBash to start 'rocketchain' mining node1 <h3>
</ol>


<p><img src="https://github.com/NinoslavVasic/RocketChain/blob/master/Screenshots1/7_minthread_node1.png" alt="" title="" /></p>

<p><ol>
<p><h3> Open separate GitBash to start up mining full thread on 'rocketchain' - mining node2 <h3></p>

<p><p><h4> NOTE: IT IS IMPORTANT TO CONNECT NODES  by entering enode of the node1 when running node2 mining</h3></p></li>
</ol>
<img src="https://github.com/NinoslavVasic/RocketChain/blob/master/Screenshots1/8_minthread_node2.png" alt="" title="" /></p>

<p> For purpose of connecting local blockchain to a digital wallet one have to create it. In this exercise, I used MyCrypto, protected with the mnemonic phrase. It is 
       important to keep the wallet keys in a safe place in order to protect the funds in your wallet.</p>

<p><ol>
<h3>  Chose Kovan network and login to your wallet <h3>
</ol>


<p><img src="https://github.com/NinoslavVasic/RocketChain/blob/master/Screenshots1/9_mycrypto.png" alt="" title="" /></p>

<p><ol>
<h3> Chose wallet to pre-fund <h3>
</ol>


<p><img src="https://github.com/NinoslavVasic/RocketChain/blob/master/Screenshots1/10_mn_login.png" alt="" title="" /></p>

<p><ol>
<h3> Wallet info - private key <h3></p>

<p> After login to your wallet chose wallet info from dropdown menu, copy private key and store it in safe file.  </p>

<p></li>
</ol>
<img src="https://github.com/NinoslavVasic/RocketChain/blob/master/Screenshots1/11_wallet_priv_key.png" alt="" title="" /></p>

<p><ol>
<p><h3> Set Up Your Custom Node <h3></p></p>

<p> Open up MyCrypto, then click Change Network at the bottom left. Click "Add Custom Node", then add the custom network information that you set in the genesis.</p>

<p>Make sure that you scroll down to choose Custom in the "Network" column to reveal more options like Chain ID.</p>

<p></li>
</ol>
<img src="https://github.com/NinoslavVasic/RocketChain/blob/master/Screenshots1/12_add_custom_node.png" alt="" title="" /></p>

<p><ol>
<p><h3> RocketChain Network <h3></p></p>

<p> On the left bottom side of the screen, click on the "change network" and scroll down to the newly created Rocketchain network.  </p>

<p></li>
</ol>
<img src="https://github.com/NinoslavVasic/RocketChain/blob/master/Screenshots1/13_access_rocch.png" alt="" title="" /></p>

<pre><code>&lt;p&gt; Chose rocketchain network and login with private key which you have previously stored in a safe file.  &lt;/p&gt;
</code></pre>

<p><img src="https://github.com/NinoslavVasic/RocketChain/blob/master/Screenshots1/13.1_my_crypto_login_pk.PNG" alt="" title="" /></p>

<p><ol>
<h3> Transaction Initiation <h3>
</ol>
<img src="https://github.com/NinoslavVasic/RocketChain/blob/master/Screenshots1/14_transaction_initiation.PNG" alt="" title="" /></p>

<p><ol>
<h3> Confirm if everyting is valid before executing transaction and click on the button. <h3>
</ol>
<img src="https://github.com/NinoslavVasic/RocketChain/blob/master/Screenshots1/15_confirm_transaction.PNG" alt="" title="" /></p>

<p><ol>
<h3> Confirmation of Executed Transaction <h3>
</ol>
<img src="https://github.com/NinoslavVasic/RocketChain/blob/master/Screenshots1/16_transaction_confirmation.PNG" alt="" title="" /></p>

<p><ol>
<h3> GREAT: Succesfully Executed Transaction <h3>
</ol>
<img src="https://github.com/NinoslavVasic/RocketChain/blob/master/Screenshots1/17_succesfull_transaction.PNG" alt="" title="" /></p>

<p></footer></p>

<pre><code>&lt;br&gt;

&lt;div id="footer"&gt;

    Copyright 2020 Columbia FinTech Bootcamp NVasic


&lt;/div&gt;
</code></pre>

<p></body>
</html></p>

