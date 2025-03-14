# Btcbf

## **Description**

A fast and efficient bitcoin private key brute force written in python. The method is based on the generation of random private keys and their corresponding public address; then searching each through a list of addresses with a positive balance.

It is fast because the number of loops is multiplied by the number of addresses available in the list. It means if your CPU processes 500 loops per second; and 10000 addresses are in the list 5milion possibilities are checked per second(My tiny 2.9GHz dual-core CPU has the rate of 1000its/s, using a list of 10k addresses means 10milion possibilities are checked per second!). However, there are 2^128 possibilities to check; so not fast enough anyway. Also, no API and internet connection is needed!

## **Also can be used as wallet generator!**

Just type "gen" and a secure wallet is printed for you. The reason to use this method instead of the available websites and online wallets? Because you enter your email, use internet connections, etc. Your email can be hacked, your online wallet can be vulnerable to attacks, and many other ways that make them risky. Use my tool to generate a wallet offline in order to remain safe.   

## The Goal
The main goal is to prove bitcoin is secure. At least until the day that Quantum computers start working against it!:innocent:

## **Requirements**

  The "address.txt" file containing a list of public addresses(Add as many as positive balance addresses possible to this file; this increases your chance of success, find more addresses [here](https://bitinfocharts.com/top-100-richest-bitcoin-addresses.html) ).
  
```$ pip install -r requirements.txt```  


## **Usage**

```$ python Btcbf.py```  
  "What do you want to do? <<options: [gen]: generate wallet address and private key, [brute]: brute force bitcoin, [exit]: exit>>" Type your desired action and follow instructions.(I love to interact with my code:slightly_smiling_face:)
  
### While brute
If any key is found; a text file named "foundkey.txt" containing the found private key and public address is saved.

### While gen
An address with its corresponding private key is printed.

### While exit
Exits!

## **Donation**

Make my BTC address a good option to be on the list!:cowboy_hat_face:


>BTC: 13r5Xr3D1j1RgwVt6KToXn8h9vqYb49eNx

>ETH: 0x25A296248f9F4a5e2343Dd19faF1b49594746620

>BCH: qq0ns64247xhqxjzv8cnjw7hl4scuc0jryzu37p4s9


## Latest Release
Link to latest release(v.1.0.0): [link](https://github.com/vlnahp/Btcbf/releases/download/v.1.0.0/Btcbf.zip)
