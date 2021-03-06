# Whois server list

This list is a manual and generated compilation of whois servers.

Sources are:

* [XML] The existing whois-server-list
* [IANA] [IANA](http://www.iana.org/domains/root/db)
* [PSL] [Public Suffix List](https://publicsuffix.org/list/effective_tld_names.dat)
* [WHOIS_RB] [Ruby Whois](https://github.com/weppos/whois/blob/master/data/tld.json)
* [MD_WHOIS] [Marco d'Itri's Whois list](https://raw.githubusercontent.com/rfc1036/whois/next/tld_serv_list)
* [PHOIS] [php-whois](https://raw.githubusercontent.com/regru/php-whois/master/src/Phois/Whois/whois.servers.json)
* [PHP_WHOIS] [phpWhois](https://raw.githubusercontent.com/phpWhois/phpWhois/master/src/whois.servers.php)

You can find the latest list online at http://whois-server-list.github.io/whois-server-list/3.0/whois-server-list.xml

We do also provide an online <a href="http://whois-api.domaininformation.de/">Whois API</a> which uses this list.

# IDN

Queries for IDN domain names should be done in the ACE representation.

# Contribution

If you want to change anything to the list feel free to submit a pull request.
Please include a `<source>XML</source>` to your contributed elements, otherwise
they would get lost during next compilation. E.g.:

    <whoisServer host="whois.example.net">
        <source>XML</source>
    </whoisServer>

# License and author

Markus Malkusch <markus@malkusch.de> is the author of this project. This project is free and under the WTFPL.
However as this is a merged list out of differently licensed works, I have to put this project under all
those licenses. These are the licenses and its corresponding sources:

| Source    | License |
|-----------|---------|
| XML       | WTFPL   |
| MD_WHOIS  | GPL-2   |
| WHOIS_RB  | MIT     |
| PHP_WHOIS | GPL-2   |
| PHOIS     | MIT     |


## Donations

If you like this project and feel generous donate a few Bitcoins here:
[1335STSwu9hST4vcMRppEPgENMHD2r1REK](bitcoin:1335STSwu9hST4vcMRppEPgENMHD2r1REK)

[![Build Status](https://travis-ci.org/whois-server-list/whois-server-list.svg?branch=master)](https://travis-ci.org/whois-server-list/whois-server-list)

