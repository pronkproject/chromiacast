# Changelog

All notable changes to Chromiacast are documented in this file.

## 0.1.0 - 2026-08-30

The first public release provides:

- authenticated Google Cast control connections and receiver lifecycle
  management;
- codec-agnostic Cast Streaming negotiation, encrypted RTP transport, RTCP
  feedback, retransmission, and synchronized audio and video sessions;
- optional mDNS discovery with stable device identities and scoped endpoints;
- bounded receiver product-information queries;
- optional Android TV pairing, persistent client identities, remote state,
  and key control; and
- observable flow-control statistics, key-frame requests, transport failures,
  and adaptive playout-delay updates.

Capture, encoding, media-framework integration, bitrate selection, and local
authorization policy remain application responsibilities.
