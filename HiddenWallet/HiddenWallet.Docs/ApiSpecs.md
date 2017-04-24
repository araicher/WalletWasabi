|API | Description    | Request body    | Response body   |
|--- | ---- | ---- | ---- |
|POST /api/v1/wallet/create  | Creates the wallet | password | mnemonic, creationTime |
|POST /api/v1/wallet/recover  | Recovers the wallet | password, mnemonic, creationTime | None |
|POST /api/v1/wallet/load | Loads the wallet and starts syncing | password  | None |
|GET /api/v1/wallet/wallet-exists | Checks if the wallet exists or not | None  | value |
|GET /api/v1/wallet/status | Displays dynamic information on the wallet | None  | walletState, headerHeight, trackingHeight |
|GET /api/v1/wallet/shutdown | Shuts down the syncing | None  | None |