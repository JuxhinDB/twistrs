# CHANGELOG.md

## 0.3.1-beta (2020-10-27)

Security:

  - N/A

Features:

  - Implemented WhoIs lookup.

Fix:

  - N/A

## 0.3.0-beta (2020-10-26)

Security:

  - N/A

Features:

  - N/A

Fix:

  - Updated interface for permutation module to return [`impl Iterator`](https://github.com/JuxhinDB/twistrs/pull/19) which is a breaking change.


## 0.2.2-beta (2020-10-26)

Security:

  - N/A

Features:

  - Implemented new GeoIP cached lookups.

Fix:

  - N/A


## 0.2.1-beta (2020-10-17)

Security:

  - N/A

Features:

  - N/A

Fix:

  - Updated TLD permutation method to only perform TLD replacement due to causing noisy results.

## 0.2.0-beta (2020-10-17)

Security:

  - N/A

Features:

  - Implement HTTP Banner enrichment method.

Fix:

  - N/A

## 0.1.3-beta (2020-10-10)

Security:

  - N/A

Features:

  - Implement TLD permutation mode.
  - Implement Dictionary permutation mode.

Fix:

  - Added domain filtering to avoid looking up dirty/invalid domains.
