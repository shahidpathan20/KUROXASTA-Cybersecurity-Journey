# OSI Model

The **Open Systems Interconnection (OSI) model** is a seven-layer framework for understanding network communication.

Encapsulation means protocol information is added as data moves down the layers so it can be transported and delivered.

| Layer | Name | Main idea |
|---:|---|---|
| 7 | Application | Network services used by applications, such as web and email protocols. |
| 6 | Presentation | Data representation, encoding, compression, and encryption concepts. |
| 5 | Session | Establishes, manages, and ends communication sessions. |
| 4 | Transport | End-to-end transport; TCP provides reliable ordered delivery, while UDP provides datagrams without the same guarantees. |
| 3 | Network | Logical addressing and routing; IP operates here. |
| 2 | Data Link | Local-link communication; Ethernet frames and MAC addresses are examples. |
| 1 | Physical | Transmits bits as electrical, optical, or radio signals. |

Remember bottom to top: **Physical, Data Link, Network, Transport, Session, Presentation, Application**.

[Back to Networking Fundamentals](README.md)