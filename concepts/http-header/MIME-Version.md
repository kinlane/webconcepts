---
layout: page
title:  "HTTP Header Field: MIME-Version"
---

**[RFC 7231: Hypertext Transfer Protocol (HTTP/1.1): Semantics and Content](/specs/IETF/RFC/7231 "The Hypertext Transfer Protocol (HTTP) is an application-level protocol for distributed, collaborative, hypertext information systems. This document defines the semantics of HTTP/1.1 messages as expressed by request methods, request header fields, response status codes, and response header fields, along with the payload of messages (metadata and body content) and mechanisms for content negotiation."):** [HTTP is not a MIME-compliant protocol. However, messages can include a single MIME-Version header field to indicate what version of the MIME protocol was used to construct the message. Use of the MIME-Version header field indicates that the message is in full conformance with the MIME protocol (as defined in RFC 2045). Senders are responsible for ensuring full conformance (where possible) when exporting HTTP messages to strict MIME environments.](http://tools.ietf.org/html/rfc7231#appendix-A.1)

<br/>
<hr/>

<p style="text-align: right">Return to list of all ( <a href="../http-headers">HTTP Header Fields</a> | <a href="../">Web Concepts</a> )</p>