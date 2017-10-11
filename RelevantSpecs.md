# Existing Specifications relevant to HTTPS/WSS in Local Network

This document enumerates existing specifications and drafts relevant to
in local network via HTTP and/or WebSocket over TLS, for the purpose of
exploring a secure and flexible use of TLS in local network.

For details and further discussion, please refer to
[the corresponding issue in GitHub](https://github.com/httpslocal/usecases/issues/7).
Any proposals for addition, clarification and improvement are absolutely welcome.

## Service Discovery

- W3C Second Screen CG
  - [mDNS](https://github.com/webscreens/openscreenprotocol/blob/gh-pages/mdns.md)
    and
    [SSDP](https://github.com/webscreens/openscreenprotocol/blob/gh-pages/ssdp.md)
    in Open Screen Control Protocol: describe deployment of service discovery
    for Open Screen Protocol and their security considerations.
- BBC
  - [Discovery and Pairing Literature Review for MediaScape](https://github.com/bbc/device-discovery-pairing/blob/master/document.md):
    describes a variety of service discovery and device paring mechanisms which
    are widely collected.

## Certificates and PKI

- IETF
  - [Automatic Certificate Management Environment (ACME)](https://tools.ietf.org/html/draft-ietf-acme-acme-07):
    introduces an automation framework of issuing Domain Validated (DV) server certificates,
    developed by [IETF ACME WG](https://datatracker.ietf.org/wg/acme/).
    [Let's Encrypt](https://letsencrypt.org) is widely known as its implementation.
  - [Use of Short-Term Automatically Renewed (STAR) Certificates to Delegate Authority over Web Sites](https://tools.ietf.org/html/draft-ietf-acme-star-00):
    extends ACME to servers behind intermediate nodes such as load balancers, edge servers, etc.

## Local Network Architecture and Domain Name Issues

TBA

## Authentication and Authorization

- IETF
  - [OAuth 2.0 Device Flow for Browserless and Input Constrained Devices](https://tools.ietf.org/html/draft-ietf-oauth-device-flow-06):
    proposes an authorization flow for browserless and input constrained devices
    like smart TV, media console, picture frame, printer, etc.

## Others

TBA