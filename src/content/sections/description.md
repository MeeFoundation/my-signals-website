---
id: description
enable: true
title: ""
image: "/images/call-to-action.png"
bg_image: "/images/call-to-action-bg.png"
description: MySignals lets people signal their intent, just by browsing or using apps.
button:
  enable: true
  label: "View Full Spec"
  link: "/spec/"
embedVideoId: "rAEjlG6QO8s"
explanation: |
  ##### **MySignals is a handshake process between a person’s agent and a service provider website/app.**
  It's an extensible communications framework that allows developers to define specific kinds of signals (signaltypes) that can be exchanged. It defines a common namespace for these signaltypes and a syntax for passing parameters. During this handshake each side conveys the signaltypes it supports.
  
  **Here are some examples of what can be negotiated between the parties:**
  * **Privacy**: Provide legally binding notice to the service provider that it must respect your right that they “Do Not Sell” your personal information. MySignals provides an alternate implementation of the [Global Privacy Control](https://globalprivacycontrol.org/). 
  * **MyTerms**: Negotiate and digitally sign mutually acceptable contracts related to privacy and data sharing using [IEEE 7012](https://standards.ieee.org/ieee/7012/7192/).
  * **AgeProtect**: Signal the need for an age-appropriate experience from the service provider, and tell them which age verification and consent management endpoints you use.
  * **Identity**: Tell the service provider who you are. Give them a (self-sovereign) digital identifier. 
  * **IdP**: Tell the service provider which IdP (identity provider(s)) you use.  This solves the [NASCAR](https://apicrazy.com/2014/07/22/nascar-problem-in-authorisation-server-selection/) problem.
  * **SIOPv2**: Tell the service provider that your agent supports OpenID SIOPv2 allowing their site/app to display a “Continue with wallet” button for password-less login.
  * **PDN**: Give the service provider your Personal Data Network endpoint to allow your agent to manage the personal information the provider holds about you.
---
