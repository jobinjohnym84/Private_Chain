# Private_Chain

npm install -g truffle  
npm install -g ethereumjs-testrpc  


Create a folder and navigate to that and run; which will create necessar folders and files  

truffle unbox  

Install VS code and open the Folder  

Install necessary plugins for Solidity  

truffle compile -- > this will create the build folder  

truffle migrate -- > Make sure the truffle-config.js is correct. If it is localhost, make sure to run testrpc in a different command prompt. And then run the truffe migrate, whch will deploy the contarct(s)

# Commands
mkdir Node  

cd /ethereum  
cd /private  
./startnode.sh  
geth attach  

in Geth console:  
eth.getBalance('0x139b1627156becdb2efa3ece2415f14de997d5ac')  
eth.getTransactionCount('0x139b1627156becdb2efa3ece2415f14de997d5ac')  
eth.getBlock("latest").gasLimit  
web3.eth.gasPrice  


node api.js    
npm run dev  
lsof -i :3000    

wget url  
mv filename1 filename2  
