# Changelog

All notable changes to Chromiacast are documented in this file.

## 0.2.0 - 2026-08-30

This release adds:

- paced, observable Cast sender sessions with RTCP feedback, retransmission,
  picture-loss handling, and adaptive playout-delay updates;
- mDNS discovery that preserves stable receiver identities and scoped routes;
- authenticated Cast and bounded local setup product-information queries;
- optional Android TV pairing, persistent client identities, remote state,
  and key control; and
- negotiated integer and rational receiver frame-rate handling.

The crate continues to leave capture, encoding, media-framework integration,
bitrate selection, and local authorization policy to applications.

## 0.1.0 - 2026-08-30

The first public release provides:

- authenticated Google Cast control connections and receiver lifecycle
  management;
- codec-agnostic Cast Streaming negotiation, encrypted RTP transport, RTCP
  feedback, and synchronized audio and video sessions; and
- optional mDNS receiver discovery.

Capture, encoding, media-framework integration, bitrate selection, and local
authorization policy remain application responsibilities.
