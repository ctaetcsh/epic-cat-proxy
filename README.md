# Epic Cat Proxy
Simple proxy site made totally for the meme.

## Setup Instructions
1. `git clone https://github.com/ctaetcsh/epic-cat-proxy.git`
2. `cd epic-cat-proxy`
3. `npm install`
4. `node server.js`
5. Go to `localhost`

## Configuration
ECP can be configured by editing `config.json`:
* Port: Default is `80`, can be changed if needed
* Prefix: Default is `/alloy/`, change not recommended
* Blocked Hosts: Default array just has `block.test`, which is only used for testing. Should be changed to a production ready list of bad domains.