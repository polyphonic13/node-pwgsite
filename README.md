### NPM Set Up
install dependencies
`npm install`

### Set Local Environment to Devel
export NODE_ENV=development

### Local Server
run local (localhost:9000)
`nodemon`

### Local Database
local mongo 
./mongod --dbpath ~/Documents/code/projects/polyworksio/data/

./mongo util
use ghost

### Connect ot EC2: 
ssh -i "polyair01-east.pem" ec2-user@ec2-52-22-60-79.compute-1.amazonaws.com

### Start EC2 Server
sudo forever start bin/www

### Copying to EC2: 
scp -i "polyair01-east.pem"  [-r] <tgt> ec2-user@ec2-52-22-60-79.compute-1.amazonaws.com:/home/ec2-user/