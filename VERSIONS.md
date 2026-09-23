## Standard Notes Protocol and Client Compatibility

The way in which clients encrypt and sync items in Standard Notes is defined by a protocol specification.

Standard Notes accounts created before November 2020, that haven't been upgraded, will be managed using version 003 of the protocol (see the [encryption overview](https://standardnotes.com/help/security/encryption)).
Upgraded accounts, and those created from November 2020 onward, use [version 004](https://github.com/standardnotes/snjs/blob/main/packages/snjs/specification.md).

Third-party clients and libraries marked as `SN version 003 only` will only work with those accounts still using version 003.
