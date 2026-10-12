# vso-tcpping

Concurrent TCP connect latency prober in Perl. Core modules only, no CPAN installs.

    perl bin/vso-tcpping -c 10 -i 1 -t 3 example.com:443 1.1.1.1:53
    perl bin/vso-tcpping --json github.com:22

Reports sent, ok, loss%, min/avg/max and jitter per target. Exit code 1 if any target never answered.
