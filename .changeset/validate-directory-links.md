---
"openwiki": patch
---

Fix internal link validation of directory links: a directory linked without a trailing slash is no longer stamped as a missing file, and a trailing-slash link to a directory that does not exist is now reported.
