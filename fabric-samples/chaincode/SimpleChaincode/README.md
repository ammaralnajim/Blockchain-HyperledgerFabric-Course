# Starting The Updated SimpleChaincode Application

1- Start the example use command 
```
cd ~/Blockchain-HyperledgerFabric-Course/fabric-samples/chaincode/SimpleChaincode
```

1.1- Go Example
```
./startFabric.sh golang
```
1.2- Node Example
```
./startFabric.sh node
```
1.3- Java Example
```
./startFabric.sh java
```

2- Clean running Docker containers
```
docker rm -f $(docker ps -aq)
```

EOF

2- Change dir to ( client ) folder and execute below commands 
```
cd client
```
3- Download the deplendencies
```
npm install
```
4- Regester Admin User
```
node registerAdmin.js
```
5- Register User
```
node registerUser.js
```
6- Start Client Application
```
node server.js
```

Start Node-RED in another tab using below command 
node-red

open file (Node-RED ) copy content to clipboard 

open browser and navigate to 
http://127.0.0.1:1880

from node-red interface use import option to import from clipboard 








