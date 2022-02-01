# FIDO2


# Prio Art
## Browser
For the browser, there is [WAX](https://hex.pm/packages/wax_) which already implements Webauthn.
## CLI
* For the cli, we need a way to read the usb key. Yubikey does have a library for that here 
  <https://github.com/Yubico/python-fido2> but we need a way to implement this for elixir.
* This is also a good explanation about [webauthn](https://developers.yubico.com/WebAuthn/).
* There is also a c implementation for the host side.
* WAX already has a rest api implementation <https://github.com/tanguilp/wax_api_rest>

# What is FIDO2
FIDO2 is a set of specifications. It is not one authentication methode but rather describes a group of specifications to authenticate with applications and how to talk to "Security Keys".

It consists of these specifications.

- WebAuthn
Is an API for the browser to implement FIDO2.
- UAF
Provides passwordless authentication.
- U2F
2FA also called FIDO U2F is the predecessor to webauthn
source: https://fidoalliance.org/specifications/


## UAF



# Model


# Authentication

## Normal login
  * For the normal login we need a new codepath at the file <lib/hexpm_web/controllers/auth_helpers.ex>. 
  
  

