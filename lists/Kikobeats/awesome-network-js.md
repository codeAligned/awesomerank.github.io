# Awesome JavaScript Network [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg) ★318](https://github.com/Kikobeats/awesome-network-js) [![Build Status](https://img.shields.io/travis/Kikobeats/awesome-network-js/master.svg?style=flat-square)](https://travis-ci.org/Kikobeats/awesome-network-js) [![Donate](https://img.shields.io/badge/donate-paypal-blue.svg?style=flat-square)](https://paypal.me/kikobeats)

> A 🎩 list of network layer resources written pure JS.

## High level

> Based, at least, in a CLI interface.

* [airpaste ★596](https://github.com/mafintosh/airpaste) – 1-1 network pipe that auto discovers other peers using mdns.
* [blecat ★92](https://github.com/mafintosh/blecat) – 1-1 pipe over bluetooth low energy.
* [deejay ★104](https://github.com/mafintosh/deejay) – Music player that broadcasts to everyone on the same network.
* [dhtkv ★45](https://github.com/maxogden/dhtkv) – CLI for storing arbitrary key/value data in the bittorrent mainline DHT.
* [gun ★4480](https://github.com/amark/gun) – A realtime, decentralized, offline-first, graph database engine.
* [hyperpipe ★89](https://github.com/mafintosh/hyperpipe) – Distributed input/output pipe.
* [instant.io](https://github.com/feross/instant.io) – Streaming file transfer over WebTorrent.
* [ipp-printer ★265](https://github.com/watson/ipp-printer) – Create a printer on your network.
* [peercast ★321](https://github.com/mafintosh/peercast) – Like peerflix but for Chromecast.
* [peerflix ★4223](https://github.com/mafintosh/peerflix) – Streaming torrent client.
* [peervisionary ★37](https://github.com/mafintosh/peervisionary) – Stream p2p content over your local network.
* [peerwiki ★252](https://github.com/mafintosh/peerwiki) – browse all of wikipedia using bittorrent.
* [screencat ★1926](https://github.com/maxogden/screencat) – WebRTC screensharing app.
* [signalhub ★263](https://github.com/mafintosh/signalhub) – Simple signalling server that can be used to coordinate handshaking with webrtc or other fun stuff.
* [torrent-mount](https://github.com/mafintosh/torrent-mount) – Mount a torrent (or magnet link) as a filesystem in real time using torrent-stream and fuse.
* [webcat ★338](https://github.com/mafintosh/webcat) – pipe across the web using WebRTC.
* [websocketd ★7702](https://github.com/joewalnes/websocketd) – Turn any program that uses stdin/stdout into a WebSocket server.
* [webtorrent](https://github.com/feross/webtorrent) – BitTorrent over WebRTC.
* [wifi-triangulate ★45](https://github.com/watson/wifi-triangulate) – Finds your current position on planet earth using the wifi access point.

## Protocols

> Implementation of protocols specs in pure javascript.

* [airswarm ★104](https://github.com/mafintosh/airswarm) – Network swarm that automagically discovers other peers on the network using multicast dns.
* [bittorrent-dht](https://github.com/feross/bittorrent-dht) – BitTorrent DHT protocol implementation.
* [bittorrent-protocol](https://github.com/feross/bittorrent-protocol) – BitTorrent peer wire protocol implementation.
* [bittorrent-swarm](https://github.com/feross/bittorrent-swarm) – BitTorrent "swarm" implementation.
* [bittorrent-tracker](https://github.com/feross/bittorrent-tracker) – BitTorrent tracker (client & server) implementation
* [bonjour ★163](https://github.com/watson/bonjour) – A Bonjour/Zeroconf protocol implementation.
* [castv2 ★335](https://github.com/thibauts/node-castv2) – An implementation of the Chromecast CASTV2 protocol.
* [dht-rpc ★37](https://github.com/mafintosh/dht-rpc) – Make RPC calls over a [Kademlia](https://pdos.csail.mit.edu/~petar/papers/maymounkov-kademlia-lncs.pdf) based DHT.
* [dns-discovery ★117](https://github.com/mafintosh/dns-discovery) – Discovery peers in a distributed system using regular dns and multicast dns.
* [hypercore ★458](https://github.com/mafintosh/hypercore) – A p2p network for distributing and replicating static feeds of binary data.
* [ipfs ★245](https://github.com/ipfs/js-ipfs-api) – The InterPlanetary File System, a new peer-to-peer hypermedia protocol.
* [k-bucket ★62](https://github.com/tristanls/k-bucket) – Kademlia DHT K-bucket implementation as a binary tree.
* [k-rpc](https://github.com/mafintosh/k-rpc) – Implementation of the k-rpc protocol used the BitTorrent DHT. Also see [k-rpc-socket ★17](https://github.com/mafintosh/k-rpc-socket).
* [mdns ★607](https://github.com/agnat/node_mdns) – mdns/zeroconf/bonjour service discovery.
* [multicast-dns ★162](https://github.com/mafintosh/multicast-dns) – Low level multicast-dns implementation.
* [peervision ★84](https://github.com/mafintosh/peervision) – Live p2p streaming protocol.
* [polo ★179](https://github.com/mafintosh/polo) – A zero configuration service discovery module.
* [rtsp-server ★16](https://github.com/watson/rtsp-server) – A low level module for creating RTSP servers.
* [utp-native ★51](https://github.com/mafintosh/utp-native) – micro transport protocol, a network protocol similar to tcp that runs on top of udp.

## Modules

> Do one thing well.

* [airplay-server ★180](https://github.com/watson/airplay-server) – A low level AirPlay server.
* [castnow ★71](https://github.com/xat/chromecast-player) – simple chromecast player.
* [discovery-swarm](https://github.com/mafintosh/discovery-swarm) – A network swarm that uses [discovery-channel](https://github.com/maxogden/discovery-channel) to find peers. Also check [webrtc-swarm ★151](https://github.com/mafintosh/webrtc-swarm).
* [dns-packet](https://github.com/mafintosh/dns-packet) – Abstract-encoding compliant module for encoding / decoding DNS packets. Also see [dns-socket ★46](https://github.com/mafintosh/dns-socket).
* [etcdjs ★47](https://github.com/mafintosh/etcdjs) – Low level etcd v2 client written in Javascript with failover support.
* [geocode-wifi ★24](https://github.com/watson/geocode-wifi) – Get yours latitude/longitude based on your wifi access point.
* [hash-to-port ★21](https://github.com/mafintosh/hash-to-port) – Hash a value to a valid port.
* [ip-packet ★22](https://github.com/mafintosh/ip-packet) – Encode/decode raw ip packets.
* [magnet-uri](https://github.com/feross/magnet-uri) – Parse a magnet URI and return an object of keys/values.
* [network-address ★49](https://github.com/mafintosh/network-address) – Get the local network address of your machine.
* [network-simulator ★39](https://github.com/substack/network-simulator) – Simulate a low-level computer network.
* [rtsp-stream ★31](https://github.com/watson/rtsp-stream) - A transport agnostic RTSP serial multiplexer module for Node.
* [simple-peer ★1020](https://github.com/feross/simple-peer) – Simple WebRTC video/voice and data channels.
* [simple-websocket ★57](https://github.com/feross/simple-websocket) – Simple, EventEmitter API for WebSockets.
* [torrent-discovery](https://github.com/feross/torrent-discovery) – Discover BitTorrent and WebTorrent peers.
* [torrent-stream ★1362](https://github.com/mafintosh/torrent-stream) – The low level streaming torrent engine that peerflix uses.
* [udp-packet ★30](https://github.com/substack/udp-packet) – Encode/decode raw udp packets.