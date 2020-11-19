## Standard Notes Protocol and Client Compatibility

The way in which clients encrypt and sync items in Standard Notes is defined by a protocol specification.  

Standard Notes accounts created before November 2020, that haven't been upgraded, will be managed using [version 003](https://docs.standardnotes.org/specification/encryption#version-003) of the protocol.  
Upgraded accounts, and those created from November 2020 onward will be using [version 004](https://github.com/standardnotes/snjs/blob/004/specification.md).

Third-party clients and libraries marked as `SN version 003 only` will only work with those accounts still using version 003.
