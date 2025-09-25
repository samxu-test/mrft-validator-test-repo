# Blank Lines in Trailer Block Test

This file demonstrates the Git trailer parsing edge case where blank lines within a trailer block break continuity.

According to Git trailer parsing rules, blank lines break the trailer block, causing subsequent trailer-like content to not be recognized as trailers.

This affects MRFT parsing and should be detected by our validator.