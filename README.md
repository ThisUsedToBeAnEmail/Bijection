# NAME

Bijection - Bijection of an integer.
========================
[![Build Status](https://travis-ci.org/ThisUsedToBeAnEmail/Bijection.svg?branch=master)](https://travis-ci.org/ThisUsedToBeAnEmail/Bijection)
[![Coverage Status](https://coveralls.io/repos/ThisUsedToBeAnEmail/Bijection/badge.svg?branch=master)](https://coveralls.io/r/ThisUsedToBeAnEmail/Bijection?branch=master)
[![CPAN version](https://badge.fury.io/pl/Bijection.svg)](https://metacpan.org/pod/Bijection)


# VERSION

Version 0.03

# SYNOPSIS

Quick summary of what the module does.

Perhaps a little code snippet.

        use Bijection qw/biject inverse/;

        my $int = 1;
        my $string = biject($int);
        inverse($string) == $int;

        ....

        use Bijection qw/all/;

        bijection_set(reverse @Bijection::ALPHA[9 .. $#Bijection::ALPHA]);

        my $int = 2;
        my $string = biject($int);
        inverse($string) == $int;

# EXPORT

## biject

## inverse

## bijection\_set

# AUTHOR

lnation, `<thisusedtobeanemail at gmail.com>`

# BUGS

Please report any bugs or feature requests to `bug-bijection at rt.cpan.org`, or through
the web interface at [http://rt.cpan.org/NoAuth/ReportBug.html?Queue=Bijection](http://rt.cpan.org/NoAuth/ReportBug.html?Queue=Bijection).  I will be notified, and then you'll
automatically be notified of progress on your bug as I make changes.

# SUPPORT

You can find documentation for this module with the perldoc command.

    perldoc Bijection

You can also look for information at:

- RT: CPAN's request tracker (report bugs here)

    [http://rt.cpan.org/NoAuth/Bugs.html?Dist=Bijection](http://rt.cpan.org/NoAuth/Bugs.html?Dist=Bijection)

- AnnoCPAN: Annotated CPAN documentation

    [http://annocpan.org/dist/Bijection](http://annocpan.org/dist/Bijection)

- CPAN Ratings

    [http://cpanratings.perl.org/d/Bijection](http://cpanratings.perl.org/d/Bijection)

- Search CPAN

    [http://search.cpan.org/dist/Bijection/](http://search.cpan.org/dist/Bijection/)

# ACKNOWLEDGEMENTS

# LICENSE AND COPYRIGHT

Copyright 2018 lnation.

This program is free software; you can redistribute it and/or modify it
under the terms of the the Artistic License (2.0). You may obtain a
copy of the full license at:

[http://www.perlfoundation.org/artistic\_license\_2\_0](http://www.perlfoundation.org/artistic_license_2_0)

Any use, modification, and distribution of the Standard or Modified
Versions is governed by this Artistic License. By using, modifying or
distributing the Package, you accept this license. Do not use, modify,
or distribute the Package, if you do not accept this license.

If your Modified Version has been derived from a Modified Version made
by someone other than you, you are nevertheless required to ensure that
your Modified Version complies with the requirements of this license.

This license does not grant you the right to use any trademark, service
mark, tradename, or logo of the Copyright Holder.

This license includes the non-exclusive, worldwide, free-of-charge
patent license to make, have made, use, offer to sell, sell, import and
otherwise transfer the Package with respect to any patent claims
licensable by the Copyright Holder that are necessarily infringed by the
Package. If you institute patent litigation (including a cross-claim or
counterclaim) against any party alleging that the Package constitutes
direct or contributory patent infringement, then this Artistic License
to you shall terminate on the date that such litigation is filed.

Disclaimer of Warranty: THE PACKAGE IS PROVIDED BY THE COPYRIGHT HOLDER
AND CONTRIBUTORS "AS IS' AND WITHOUT ANY EXPRESS OR IMPLIED WARRANTIES.
THE IMPLIED WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR
PURPOSE, OR NON-INFRINGEMENT ARE DISCLAIMED TO THE EXTENT PERMITTED BY
YOUR LOCAL LAW. UNLESS REQUIRED BY LAW, NO COPYRIGHT HOLDER OR
CONTRIBUTOR WILL BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, OR
CONSEQUENTIAL DAMAGES ARISING IN ANY WAY OUT OF THE USE OF THE PACKAGE,
EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.
