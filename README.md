<div align="center">
  <img src="./img/icon_200x200.png" alt="dark-crystal-icon" width="200" height="200" style="padding-bottom: 0.5em;" />
</div>

<div align="center">
  <h1>Dark Crystal</h1>
  Back up your secrets using the trust in your social network.
</div>

## Code

### Standalone Client
A patchcore application built with Electron and Mutant.

* [dark-crystal-standalone](https://github.com/blockades/dark-crystal-standalone)

### Patchbay Interface Plugin 
A patchbay interface for Patchbay built with reactive JS framework [mutant](https://github.com/mmckegg/mutant).

* [patchbay-dark-crystal](https://github.com/blockades/patchbay-dark-crystal)

### Scuttlebutt API
Our API for validating, building, publishing and reading Dark Crystal records in Scuttlebutt

* [scuttle-dark-crystal](https://github.com/blockades/scuttle-dark-crystal)

### HTTP JSON API 
A HTTP/S JSON API to access our wrapper around Shamir's Secret Shares. Deployed at [https://api.darkcrystal.pw](https://api.darkcrystal.pw).

* [dark-crystal-secrets-api](https://github.com/blockades/dark-crystal-secrets-api)

### Cryptography
Our extension of Shamir's Secret Shares

* [dark-crystal-secrets](https://github.com/blockades/dark-crystal-secrets)

### Schemas / Models
JSON schemas and validation for secure scuttlebutt message types

* [ssb-dark-crystal-schema](https://github.com/blockades/ssb-dark-crystal-schema) - 

## What is Dark Crystal?

Dark Crystal transforms secrets into crystal shards that you can send to trusted friends. If you lose the secret, or something happens to you, your friends can combine the shards to recover the crystal and reveal the secret.

Dark Crystal uses cryptography so that no individual shard reveals anything about your secret on its own. Your secret is only revealed if the people you chose cooperate and put their shards together.

Use Dark Crystal for....

* Passwords
* Cryptocurrency seeds & keys
* Directions to the hidden treasure
* Any other secret in text form

Dark Crystal is a decentralised peer-to-peer app, meaning you exchange shards directly with your friends. No data is sent through a central server. It even works when you're not connected to the internet.

With decentralised and encrypted tools, there's no company or authority who can reset your access. Security is all on you. Using Dark Crystal makes managing your keys and passwords a little bit more forgiving, while still being very secure.

Dark Crystal is built on the Secure Scuttlebutt protocol. Find out more here: www.scuttlebutt.nz

> "In P2P spaces, your friends are the data center. Data get wiped? Resync it from your friends. Lose your private key? Piece together the shards from your friends. That radical interdependence with real people that we trust can remove our dependency on corporate cloud providers. This feels important; an undoing of decades of capitalist efforts to isolate us and separate us from each other. P2P technology can help people reconnect with each other on a human beings level." @noffle

![screencast](img/screencast.gif)
