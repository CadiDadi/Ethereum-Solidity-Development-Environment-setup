# Environment Setup for Ethereum (Solidity) Smart Contract Development 


1.	NodeJS & NPM - Download & Install - https://nodejs.org/en/ 
2.	NPM globally from Command Line Interface (CLI) (Administrator) > npm install -g npm
3.	Chocolatey (software package manager) https://chocolatey.org/ 
o	on Win10, can install from CLI(Administrator) > @"%SystemRoot%\System32\WindowsPowerShell\v1.0\powershell.exe" -NoProfile -InputFormat None -ExecutionPolicy Bypass -Command "iex ((New-Object System.Net.WebClient).DownloadString('https://chocolatey.org/install.ps1'))" && SET "PATH=%PATH%;%ALLUSERSPROFILE%\chocolatey\bin"
4.	a. Integrated Development Environment (IDE) COMPATIBLE WITH SOLIDITY
o	Visual Studio Core (VSC) - https://code.visualstudio.com/docs?start=true
o	Atom - https://atom.io/ 
       b. Package Extensions for Solidity –  look for Solidity & Ethereum
5.    Windows Build Tools. CLI(Administrator) > npm install -g -production windows-build-tools
6.    Truffle - CLI(Administrator) > npm install -g truffle
o	Truffle  – Ethereum Swiss Army Knife - http://truffleframework.com/ 
o	Truffle Commands (w/ definitions) - http://truffleframework.com/docs/advanced/commands 
7.    Ganache  
a. download & install - https://truffleframework.com/ganache 
b. CLI(Administrator) > npm install -g ganache-cli
8.   Web3.js – CLI(Administrator) > npm install -g web3
9.   ReactJS - CLI(Administrator) > npm install --save react react-dom
o	TUTORIAL - https://reactjs.org/tutorial/tutorial.html
10.   Drizzle -  a collection of front-end libraries that make writing dapp front-ends easier and more predictable. The core of Drizzle is based on a Redux store, so you have access to the spectacular development tools around Redux. We take care of synchronizing your contract data, transaction data and more. Things stay fast because you declare what to keep in sync.
          a. Drizzle: npm install --save drizzle
          b. React Drizzle package: npm install --save drizzle-react
11. Geth - CLI(Administrator) > npm install -g geth


Tutorials to get started
Hello World - https://www.ethereum.org/greeter 
Pet Shop - https://truffleframework.com/tutorials/pet-shop 

Documentation
Ethereum - http://www.ethdocs.org/en/latest/ 
Solidity - https://solidity.readthedocs.io/en/v0.4.24/ 
Truffle - https://truffleframework.com 
