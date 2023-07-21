## Local Squid Proxy setup
- docker-compose up -d
- access like http://127.0.0.1:8080
- basic auth user: test
- basic auth pw: test

## Please using the LTS 18.x Node.JS
curl -fsSL https://deb.nodesource.com/setup_18.x | sudo -E bash - &&\
sudo apt-get install -y nodejs

## Node test script
- Install dependencies: npm install -save node-fetch@2 https-proxy-agent
- node test.mjs
