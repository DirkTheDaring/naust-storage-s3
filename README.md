# naust-storage-s3

S3 and MinIO object-store adapter for the Naust registry ecosystem.

## Overview
- Backend adapter implementing `ObjectStore` from `naust-storage-core`.
- Strict pagination, conditional operations, and key-prefix isolation.
- Deterministic in-memory `S3Client` mock double under the `mock-client` test feature.

## License
MIT
