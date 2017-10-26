# Alien::Zcash

Easily install [Zcash](https://z.cash) via CPAN and specify it as a dependency in Perl applications

# What does this do?

This allows you to tell your favorite CPAN installer to install Zcash, via your
local CPAN mirror. This allows Perl applications to specify that they depend on
an external dependency, Zcash, in a standard way, the Alien::* namespace. Most
likely you will not use this module directly, you just want to do

    cpan Alien::Zcash

to install with the normal CPAN.pm client or:

    cpanm Alien::Zcash

to use the newer, more featureful cpanminus client.

## CPAN distribution dependencies

Currently Alien::Zcash requires at least Perl 5.8.1, and a Linux-based operating
system with at least 4GB of RAM, to fully compile the underlying Zcash daemon,
which is based on Zcash.

For Zcash to work correctly, it will need to make inbound+outbound connections
on the Peer-to-Peer port 8233.

# Installation

To install this module from source code, run the following commands:

    perl Build.PL
    ./Build
    ./Build test
    ./Build install clean

# Who wrote this?

Duke Leto <duke@leto.net>

# Can I Support This Awesome stuff?

Please your ZEC donations to

zcZLVdeNHvbw58ch56RWi92ws8hweLHyxhoT6jniFKd8kkBPXPR5E46YXzAqXhrfagtwRojAtumg4M3kmrHfZPU6m63Rj5z

to support this CPAN module. Thanks!

# Support

After installing, you can find documentation for this module with the
perldoc command:

    perldoc Alien::Zcash

# Copyright

Copyright (c) 2017 by Duke Leto <duke@leto.net>.  All rights reserved.

# License

This package is free software; you can redistribute it and/or
modify it under the same terms as Perl itself, Fuck Yeah!
