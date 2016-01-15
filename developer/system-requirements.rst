.. index::
single: Requirements

System Requirements
===================

OroCommerce requires PHP 5.4.9 or newer and can be installed using any combination of the supported operating systems,
web-servers and databases from the list below.

Supported Operating Systems
---------------------------
* Linux x86, x86-64
* Windows 7 and 8
* Mac OS X 10.9 and above

Supported Web Servers
---------------------
* Apache 2.2.x
* Nginx
* Lighttpd

Supported Database Management Systems
-------------------------------------
* MySQL 5.1 and above
* PostgreSQL/EnterpriseDB 9.1 and above

PHP Configuration
-----------------
* PHP 5.4.9 and above (5.4.11+ is recommended)
* PHP Command Line Interface
* Required PHP Extensions:
    * ctype
    * fileinfo
    * GD 2.0 and above
    * intl
    * JSON
    * Mcrypt
    * PCRE 8.0 and above
    * SimpleXML
    * Tokenizer
    * `xml <http://php.net/manual/en/xml.installation.php>`_
    * `xmlreader <http://php.net/manual/en/xmlreader.installation.php>`_
    * `zip <http://php.net/manual/en/zip.installation.php>`_
* PHP Settings:
    * date.timezone must be set
    * detect_unicode must be disabled in php.ini
    * memory_limit should be at least 512M
    * xdebug.scream must be disabled in php.ini
    * xdebug.show_exception_trace must be disabled in php.ini
* Other Requirements:
    * ICU library 4.4 and above
    * mcrypt_encrypt() should be available

Optional Recommendations
------------------------
* PHP Extensions:
    * xml module enabled
    * libxml
    * iconv
    * mbstring
    * posix
* PHP Configuration:
    * xdebug.max_nesting_level above 100 in php.ini
* Node.js (for JS minification)

Supported Browsers
==================
    * Mozilla Firefox 43 and above
    * Google Chrome 47 and above
    * Microsoft Internet Explorer 11 and above
    * Safari 5 and above
    * Opera 34 and above
