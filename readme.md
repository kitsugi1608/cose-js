## 1st step
### npm install
#
## 2nd step
### ./gen-csca-dsc.sh 
#
## 3rd step
### Enter your message in the "message" property of the "JSON" object in the JSON object named message.json 
#
## 4th step
### cat message.json | node cose_sign.js > message.b45
#
## 5th step
### cat message.b45 | node cose_verify.js