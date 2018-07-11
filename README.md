# Environment Setup for Ethereum (Solidity) Smart Contract Development 
</br>
When I was getting started with Ethereum (Solidity) Smart Contract Development, it took me a while to figure out how to get everything I needed set up. I hope this will help someone else:
</br>
<h4>Tools to Install</h4>
1.	NodeJS & NPM - Download & Install - https://nodejs.org/en/ </br>
2.	NPM globally from Command Line Interface (CLI) (Administrator) > npm install -g npm</br>
3.	Chocolatey (software package manager) https://chocolatey.org/ </br>
&nbsp;&nbsp;&nbsp;&nbsp;--one option for Windows10, install from CLI(Administrator) > @"%SystemRoot%\System32\WindowsPowerShell\v1.0\powershell.exe" -NoProfile -InputFormat None -ExecutionPolicy Bypass -Command "iex ((New-Object System.Net.WebClient).DownloadString('https://chocolatey.org/install.ps1'))" && SET "PATH=%PATH%;%ALLUSERSPROFILE%\chocolatey\bin"</br>
4.	a. Integrated Development Environment (IDE) COMPATIBLE WITH SOLIDITY</br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Two suggestions:</br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;-	Visual Studio Core (VSC) - https://code.visualstudio.com/docs?start=true</br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;-	Atom - https://atom.io/ </br>
&nbsp;&nbsp;&nbsp;     b. Package Extensions for Solidity –  look for Solidity & Ethereum</br>
5.    Windows Build Tools. CLI(Administrator) > npm install -g -production windows-build-tools</br>
6.    Truffle - CLI(Administrator) > npm install -g truffle</br>
&nbsp;&nbsp;&nbsp;&nbsp;-	Truffle  – Ethereum Swiss Army Knife - http://truffleframework.com/ </br>
&nbsp;&nbsp;&nbsp;&nbsp;-	Truffle Commands (w/ definitions) - http://truffleframework.com/docs/advanced/commands </br>
7.    Ganache </br> 
&nbsp;&nbsp;&nbsp;&nbsp;a. download & install - https://truffleframework.com/ganache </br>
&nbsp;&nbsp;&nbsp;&nbsp;b. CLI(Administrator) > npm install -g ganache-cli</br>
8.   Web3.js – CLI(Administrator) > npm install -g web3</br>
9.   ReactJS - CLI(Administrator) > npm install --save react react-dom</br>
&nbsp;&nbsp;&nbsp;&nbsp;-	TUTORIAL - https://reactjs.org/tutorial/tutorial.html</br>
10.   Drizzle -  a collection of front-end libraries that make writing dapp front-ends easier and more predictable. The core of Drizzle is based on a Redux store, so you have access to the spectacular development tools around Redux. We take care of synchronizing your contract data, transaction data and more. Things stay fast because you declare what to keep in sync.</br>
&nbsp;&nbsp;&nbsp;&nbsp;a. Drizzle: npm install --save drizzle</br>
&nbsp;&nbsp;&nbsp;&nbsp;b. React Drizzle package: npm install --save drizzle-react</br>
11. Geth - CLI(Administrator) > npm install -g geth
</br>
<h4>Browser Tools </h4>
1.	Remix - http://remix.ethereum.org </br>
2.	MetaMask – plugin for - Chrome, Firefox, Brave(pre-installed in Brave)
</br>
<h4>Tutorials to get started</h4>
Hello World - https://www.ethereum.org/greeter </br>
Pet Shop - https://truffleframework.com/tutorials/pet-shop 
</br>
<h4>Documentation</h4>
Ethereum - http://www.ethdocs.org/en/latest/ </br>
Solidity - https://solidity.readthedocs.io/en/v0.4.24/ </br>
Truffle - https://truffleframework.com </br>
