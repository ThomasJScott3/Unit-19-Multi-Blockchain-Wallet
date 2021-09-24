# Unit 19: Multi Blockchain Wallet
<img src="https://github.com/ThomasJScott3/Unit-19-Multi-Blockchain-Wallet/blob/main/images/newtons-coin-cradle.jpg"></img>
<p>
  
Summary & Comments: 
  
  The goal of this poject was to construct a cryptocurrency wallet using python. The primary coins in the wallet were ETH and BTC. PFor testing purposes, I repurposed code from my ether testnet from the last assignment. I also made use of a bitcoin faucet, the link to which was provided by the instructor. I completed this assignments with some caveats. First and foremost, I ditched the .py format in favor of a jupyter notebook. You will find the notebook thoroughly commented throughout. In addition, I did not use the constants in an external python file nor was I able to get the .bat env implementation to work. In order to run my code, you will need to add my mnemonic to your own .env on your machine. In addition, after all my hard work filling the testnet with ETH for the last assignment I decided not to start from scrath. As you examine the screenshots below as well as my code you will hopefully see the method to my madness.

<p>

### BTC Test

<br>

<p align="center"><img src="https://github.com/ThomasJScott3/Unit-19-Multi-Blockchain-Wallet/blob/main/images/Faucet1.PNG"></img?</p>

<p>

  First, I top off your wallet with a bitcoin faucet provided by the instructor. As an added incentive to review my code, I am not linking it here.

<p>
  
<img src="https://github.com/ThomasJScott3/Unit-19-Multi-Blockchain-Wallet/blob/main/images/BTC_test.PNG"></img>

<p>

  Next, I moved funds from one account in my wallet to the other.

<br>

### ETH Test

<br>
  
<p align="center"><img src="https://github.com/ThomasJScott3/Unit-19-Multi-Blockchain-Wallet/blob/main/images/MyCrypto2.PNG"></img?</p>

<br>

  First, I repurposed the ETH I mined for the last assignment to fund my empty ETH account for this assignment.
  
<br>

<p align="center"><img src="https://github.com/ThomasJScott3/Unit-19-Multi-Blockchain-Wallet/blob/main/images/MyCrypto2b.PNG"></img></p>

<br>
  
  Using web3 in my code, check to see whether your new account has received payment.
  
<br>
  
  <p align="center"><img src="https://github.com/ThomasJScott3/Unit-19-Multi-Blockchain-Wallet/blob/main/images/MyCrypto3.PNG"></img></p>
  
<br>
  
  Next, I teed up the account I emptied at the end of the last assignment to receive funds from the one I just created.
  
<br>
  
  <p align="center"><img src="https://github.com/ThomasJScott3/Unit-19-Multi-Blockchain-Wallet/blob/main/images/MyCrypto3b.PNG"></img></p>

<br/>
  
  I executed the transaction in python and reviewed the results on both ends. Your output in python and MyCrypto should match.

<p>

  <p align="center"><img src="https://github.com/ThomasJScott3/Unit-19-Multi-Blockchain-Wallet/blob/main/images/MyCrypto4.PNG"></img></p>
  
<p>
  
  Save for the placement of the decimal place, the two numbers align.

<br>
  
### End of Report
