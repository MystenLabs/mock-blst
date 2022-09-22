# Mocked BLST - DO NOT USE

This is a fork of BLST with expensive operations turned into no-ops.

This exists in order to speed up https://github.com/MystenLabs/sui simulator tests,
which otherwise spend a large fraction of their time doing crypto operations
(which always succeed).

**If you use this as a crypto package in any kind of production code you
will have NO SECURITY WHATSOEVER and you may cause ARBITRARILY BAD THINGS to happen,
up to and including the collapse of industrial civilization.**
