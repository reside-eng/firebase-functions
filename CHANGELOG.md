- Fixes error when last argument to logger methods is `null`. (#716)
- Adds eight new available regions:
  - `us-west2`
  - `us-west3`
  - `us-west4`
  - `europe-west6`
  - `asia-northeast2`
  - `northamerica-northeast1`
  - `southamerica-east1`
  - `australia-southeast1`
- No longer throw errors for unrecognized regions (deploy will error instead).
- Fixes error where `snap.ref` in database functions did not work when using the Emulator Suite (#726)
