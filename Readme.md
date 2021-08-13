# MINIMAL YOUR DEVFEE ETHEREUM
 Work with all version of PhoenixMiner (lastest is 5.6d)
###

# HOW TO USE?
 1. Open run.bat
 2. Change wallet to your wallet or use your custom command format as below
 3. Run run.bat file
###

# COMMAND:
 start NoDevFee.exe YourWallet
 start NoDevFee.exe YourWallet Port
 start NoDevFee.exe YourWallet Port IsMinimize
###

# EXAMPLE:
 start NoDevFee.exe 0xE4c8932d74C8D891d8889C084BD6e89CBa255999
 start NoDevFee.exe 0xE4c8932d74C8D891d8889C084BD6e89CBa255999 14444
 start NoDevFee.exe 0xE4c8932d74C8D891d8889C084BD6e89CBa255999 5555 true
 start NoDevFee.exe 0xE4c8932d74C8D891d8889C084BD6e89CBa255999.FEE01 5555 true
###

# NOTE:
 - YourWallet: your wallet to get devfee share 
 - Port: port of mining pool. If don't know you can set to 0. Recommend: ethermine.org (5555), ethpool (3333), other same port of pool
 - IsMinimize: true or false. Run with minimize windows. If you need set that and don't know port number, you can set port number to 0
 - Support naming by wallet format : YouWallet.Name 
###

==============================================================
# CHANGELOG:
  v1.2
	- Fix pool protocol

  v1.1
	- Add more log, count devfee share
	- Support wallet name with format (Wallet.Name)

  v1.0
    - First release