# 1.0.0

- Stable release

# 0.0.25

- Updated: package.json
- Added: new endpoint (one step)

# 0.0.24

- Updated: package.json

# 0.0.23

- Added: new endpoint (settle charge)
- Added: new endpoint (settle carnet parcel)


# 0.0.22

- Added: new endpoint (create charge balance sheet)

# 0.0.21

- Fix: dependencies

# 0.0.20

- Added: new endpoint (update plan)
- Added: new endpoint (create subscription history)

# 0.0.19
- Added: new endpoint (update charge link)

# 0.0.18
- Added: forward `partner-token` header

# 0.0.17
- Added: new endpoint (charge link)
- Updated: docs

# 0.0.16
- Added: new endpoint (cancel carnet)
- Added: new endpoint (cancel parcel)
- Updated: docs

# 0.0.15
- Added: new endpoint (carnet history)
- Added: new endpoint (carnet resend)
- Updated: docs

# 0.0.14
- Added: new endpoint (charge history)
- Added: custom header
- Updated: docs

# 0.0.13
- Added: new endpoint (resend billet)
- Updated: docs

# 0.0.12
- Updated: code examples
- Updated: docs

# 0.0.11

- Refactored: gn-auth - client credentials are now sent within the header
- Refactored: gn-constants/gn-endpoints/gn-sdk - each function now has two arguments: *params* and *body*.
              The *body* is meant to be sent in the request body as usual, whereas the *params* will be mapped to                url params as defined in gn-constants. If the param is not present in the url, it will be sent as a                query string
- Refactored: gn-endpoints - now Gerencianet endpoints are restfull, which means that the sdk must consider sending               also put and delete
- Updated: docs

# 0.0.10

- Updated: gn-constants - added new endpoints
- Refactored: gn-sdk - loop through gn-constants endpoints and create the prototype functions
- Updated: docs

# 0.0.9

- Updated: gn-sdk - added createPlan

# 0.0.8

- Updated: docs
- Updated: getPaymentMethods endpoint now is getPaymentData

# 0.0.7

- Updated: node modules dependencies

# 0.0.6

- Fixed: nock net connection issues

# 0.0.5

- Changed: Gerenciant's urls for production and sandbox
- Added: new endpoints (subscriptions, notifications)

# 0.0.1

- Initial release
