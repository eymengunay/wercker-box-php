# PHP55

PHP 5.5 wercker box.

## Installed packages
* nodejs
* npm
* bower
* composer
* PHPUnit
* atoum
* capifony

## PHP info output

```
PHP Version => 5.5.11-3+deb.sury.org~precise+1

System => Linux wercker 3.2.0-60-virtual #91-Ubuntu SMP Wed Feb 19 04:13:28 UTC 2014 x86_64
Build Date => Apr 23 2014 12:19:48
Server API => Command Line Interface
Virtual Directory Support => disabled
Configuration File (php.ini) Path => /etc/php5/cli
Loaded Configuration File => /etc/php5/cli/php.ini
Scan this dir for additional .ini files => /etc/php5/cli/conf.d
Additional .ini files parsed => /etc/php5/cli/conf.d/05-opcache.ini,
/etc/php5/cli/conf.d/10-pdo.ini,
/etc/php5/cli/conf.d/20-apcu.ini,
/etc/php5/cli/conf.d/20-curl.ini,
/etc/php5/cli/conf.d/20-gd.ini,
/etc/php5/cli/conf.d/20-intl.ini,
/etc/php5/cli/conf.d/20-json.ini,
/etc/php5/cli/conf.d/20-mcrypt.ini,
/etc/php5/cli/conf.d/20-readline.ini,
/etc/php5/cli/conf.d/20-redis.ini,
/etc/php5/cli/conf.d/20-xdebug.ini

PHP API => 20121113
PHP Extension => 20121212
Zend Extension => 220121212
Zend Extension Build => API220121212,NTS
PHP Extension Build => API20121212,NTS
Debug Build => no
Thread Safety => disabled
Zend Signal Handling => disabled
Zend Memory Manager => enabled
Zend Multibyte Support => provided by mbstring
IPv6 Support => enabled
DTrace Support => enabled

Registered PHP Streams => https, ftps, compress.zlib, compress.bzip2, php, file, glob, data, http, ftp, phar, zip
Registered Stream Socket Transports => tcp, udp, unix, udg, ssl, sslv3, tls
Registered Stream Filters => zlib.*, bzip2.*, convert.iconv.*, string.rot13, string.toupper, string.tolower, string.strip_tags, convert.*, consumed, dechunk, mcrypt.*, mdecrypt.*

This program makes use of the Zend Scripting Language Engine:
Zend Engine v2.5.0, Copyright (c) 1998-2014 Zend Technologies
    with Zend OPcache v7.0.4-dev, Copyright (c) 1999-2014, by Zend Technologies
    with Xdebug v2.2.3, Copyright (c) 2002-2013, by Derick Rethans


 _______________________________________________________________________


Configuration

apc

APC support => Emulated

apcu

APCu Support => disabled
Version => 4.0.2
APCu Debugging => Disabled
MMAP Support => Enabled
MMAP File Mask =>  
Serialization Support => broken
Revision => $Revision: 328290 $
Build Date => Oct 22 2013 08:55:36

Directive => Local Value => Master Value
apc.coredump_unmap => Off => Off
apc.enable_cli => Off => Off
apc.enabled => On => On
apc.entries_hint => 4096 => 4096
apc.gc_ttl => 3600 => 3600
apc.mmap_file_mask => no value => no value
apc.preload_path => no value => no value
apc.rfc1867 => Off => Off
apc.rfc1867_freq => 0 => 0
apc.rfc1867_name => APC_UPLOAD_PROGRESS => APC_UPLOAD_PROGRESS
apc.rfc1867_prefix => upload_ => upload_
apc.rfc1867_ttl => 3600 => 3600
apc.serializer => php => php
apc.shm_segments => 1 => 1
apc.shm_size => 32M => 32M
apc.slam_defense => On => On
apc.smart => 0 => 0
apc.ttl => 0 => 0
apc.use_request_time => On => On
apc.writable => /tmp => /tmp

bcmath

BCMath support => enabled

Directive => Local Value => Master Value
bcmath.scale => 0 => 0

bz2

BZip2 Support => Enabled
Stream Wrapper support => compress.bzip2://
Stream Filter support => bzip2.decompress, bzip2.compress
BZip2 Version => 1.0.6, 6-Sept-2010

calendar

Calendar support => enabled

Core

PHP Version => 5.5.11-3+deb.sury.org~precise+1

Directive => Local Value => Master Value
allow_url_fopen => On => On
allow_url_include => Off => Off
always_populate_raw_post_data => Off => Off
arg_separator.input => & => &
arg_separator.output => & => &
asp_tags => Off => Off
auto_append_file => no value => no value
auto_globals_jit => On => On
auto_prepend_file => no value => no value
browscap => no value => no value
default_charset => no value => no value
default_mimetype => text/html => text/html
disable_classes => no value => no value
disable_functions => no value => no value
display_errors => Off => Off
display_startup_errors => Off => Off
doc_root => no value => no value
docref_ext => no value => no value
docref_root => no value => no value
enable_dl => Off => Off
enable_post_data_reading => On => On
error_append_string => no value => no value
error_log => no value => no value
error_prepend_string => no value => no value
error_reporting => 22527 => 22527
exit_on_timeout => Off => Off
expose_php => On => On
extension_dir => /usr/lib/php5/20121212 => /usr/lib/php5/20121212
file_uploads => On => On
highlight.comment => <font style="color: #FF8000">#FF8000</font> => <font style="color: #FF8000">#FF8000</font>
highlight.default => <font style="color: #0000BB">#0000BB</font> => <font style="color: #0000BB">#0000BB</font>
highlight.html => <font style="color: #000000">#000000</font> => <font style="color: #000000">#000000</font>
highlight.keyword => <font style="color: #007700">#007700</font> => <font style="color: #007700">#007700</font>
highlight.string => <font style="color: #DD0000">#DD0000</font> => <font style="color: #DD0000">#DD0000</font>
html_errors => Off => Off
ignore_repeated_errors => Off => Off
ignore_repeated_source => Off => Off
ignore_user_abort => Off => Off
implicit_flush => On => On
include_path => .:/usr/share/php:/usr/share/pear => .:/usr/share/php:/usr/share/pear
log_errors => On => On
log_errors_max_len => 1024 => 1024
mail.add_x_header => On => On
mail.force_extra_parameters => no value => no value
mail.log => no value => no value
max_execution_time => 0 => 0
max_file_uploads => 20 => 20
max_input_nesting_level => 64 => 64
max_input_time => -1 => -1
max_input_vars => 1000 => 1000
memory_limit => -1 => -1
open_basedir => no value => no value
output_buffering => 0 => 0
output_handler => no value => no value
post_max_size => 8M => 8M
precision => 14 => 14
realpath_cache_size => 16K => 16K
realpath_cache_ttl => 120 => 120
register_argc_argv => On => On
report_memleaks => On => On
report_zend_debug => Off => Off
request_order => GP => GP
sendmail_from => no value => no value
sendmail_path => /usr/sbin/sendmail -t -i  => /usr/sbin/sendmail -t -i 
serialize_precision => 17 => 17
short_open_tag => Off => Off
SMTP => localhost => localhost
smtp_port => 25 => 25
sql.safe_mode => Off => Off
sys_temp_dir => no value => no value
track_errors => Off => Off
unserialize_callback_func => no value => no value
upload_max_filesize => 2M => 2M
upload_tmp_dir => no value => no value
user_dir => no value => no value
user_ini.cache_ttl => 300 => 300
user_ini.filename => .user.ini => .user.ini
variables_order => GPCS => GPCS
xmlrpc_error_number => 0 => 0
xmlrpc_errors => Off => Off
zend.detect_unicode => On => On
zend.enable_gc => On => On
zend.multibyte => Off => Off
zend.script_encoding => no value => no value

ctype

ctype functions => enabled

curl

cURL support => enabled
cURL Information => 7.22.0
Age => 3
Features
AsynchDNS => No
CharConv => No
Debug => No
GSS-Negotiate => Yes
IDN => Yes
IPv6 => Yes
krb4 => No
Largefile => Yes
libz => Yes
NTLM => Yes
NTLMWB => Yes
SPNEGO => No
SSL => Yes
SSPI => No
TLS-SRP => Yes
Protocols => dict, file, ftp, ftps, gopher, http, https, imap, imaps, ldap, pop3, pop3s, rtmp, rtsp, smtp, smtps, telnet, tftp
Host => x86_64-pc-linux-gnu
SSL Version => OpenSSL/1.0.1
ZLib Version => 1.2.3.4

date

date/time support => enabled
"Olson" Timezone Database Version => 0.system
Timezone Database => internal
Default timezone => Europe/Rome

Directive => Local Value => Master Value
date.default_latitude => 31.7667 => 31.7667
date.default_longitude => 35.2333 => 35.2333
date.sunrise_zenith => 90.583333 => 90.583333
date.sunset_zenith => 90.583333 => 90.583333
date.timezone => Europe/Rome => Europe/Rome

dba

DBA support => enabled
Supported handlers => cdb cdb_make db4 inifile flatfile qdbm 

Directive => Local Value => Master Value
dba.default_handler => flatfile => flatfile

dom

DOM/XML => enabled
DOM/XML API Version => 20031129
libxml Version => 2.7.8
HTML Support => enabled
XPath Support => enabled
XPointer Support => enabled
Schema Support => enabled
RelaxNG Support => enabled

ereg

Regex Library => Bundled library enabled

exif

EXIF Support => enabled
EXIF Version => 1.4 $Id$
Supported EXIF Version => 0220
Supported filetypes => JPEG,TIFF

Directive => Local Value => Master Value
exif.decode_jis_intel => JIS => JIS
exif.decode_jis_motorola => JIS => JIS
exif.decode_unicode_intel => UCS-2LE => UCS-2LE
exif.decode_unicode_motorola => UCS-2BE => UCS-2BE
exif.encode_jis => no value => no value
exif.encode_unicode => ISO-8859-15 => ISO-8859-15

fileinfo

fileinfo support => enabled
version => 1.0.5

filter

Input Validation and Filtering => enabled
Revision => $Id: 4d3899e089e6e45b157975ceef2ac7deb6e9d762 $

Directive => Local Value => Master Value
filter.default => unsafe_raw => unsafe_raw
filter.default_flags => no value => no value

ftp

FTP support => enabled

gd

GD Support => enabled
GD Version => 2.1.1-dev
FreeType Support => enabled
FreeType Linkage => with freetype
FreeType Version => 2.4.8
GIF Read Support => enabled
GIF Create Support => enabled
JPEG Support => enabled
libJPEG Version => 8
PNG Support => enabled
libPNG Version => 1.2.46
WBMP Support => enabled
XPM Support => enabled
libXpm Version => 30411
XBM Support => enabled
WebP Support => enabled

Directive => Local Value => Master Value
gd.jpeg_ignore_warning => 0 => 0

gettext

GetText Support => enabled

hash

hash support => enabled
Hashing Engines => md2 md4 md5 sha1 sha224 sha256 sha384 sha512 ripemd128 ripemd160 ripemd256 ripemd320 whirlpool tiger128,3 tiger160,3 tiger192,3 tiger128,4 tiger160,4 tiger192,4 snefru snefru256 gost adler32 crc32 crc32b fnv132 fnv164 joaat haval128,3 haval160,3 haval192,3 haval224,3 haval256,3 haval128,4 haval160,4 haval192,4 haval224,4 haval256,4 haval128,5 haval160,5 haval192,5 haval224,5 haval256,5 

iconv

iconv support => enabled
iconv implementation => glibc
iconv library version => 2.15

Directive => Local Value => Master Value
iconv.input_encoding => ISO-8859-1 => ISO-8859-1
iconv.internal_encoding => ISO-8859-1 => ISO-8859-1
iconv.output_encoding => ISO-8859-1 => ISO-8859-1

intl

Internationalization support => enabled
version => 1.1.0
ICU version => 52.1
ICU Data version => 52.1

Directive => Local Value => Master Value
intl.default_locale => no value => no value
intl.error_level => 0 => 0
intl.use_exceptions => 0 => 0

json

json support => enabled
json version => 1.3.4
JSON-C headers version => 0.11.99
JSON-C library version => 0.11.99

libxml

libXML support => active
libXML Compiled Version => 2.7.8
libXML Loaded Version => 20708
libXML streams => enabled

mbstring

Multibyte Support => enabled
Multibyte string engine => libmbfl
HTTP input encoding translation => disabled
libmbfl version => 1.3.2

mbstring extension makes use of "streamable kanji code filter and converter", which is distributed under the GNU Lesser General Public License version 2.1.

Multibyte (japanese) regex support => enabled
Multibyte regex (oniguruma) version => 5.9.1

Directive => Local Value => Master Value
mbstring.detect_order => no value => no value
mbstring.encoding_translation => Off => Off
mbstring.func_overload => 0 => 0
mbstring.http_input => pass => pass
mbstring.http_output => pass => pass
mbstring.http_output_conv_mimetypes => ^(text/|application/xhtml\+xml) => ^(text/|application/xhtml\+xml)
mbstring.internal_encoding => no value => no value
mbstring.language => neutral => neutral
mbstring.strict_detection => Off => Off
mbstring.substitute_character => no value => no value

mcrypt

mcrypt support => enabled
mcrypt_filter support => enabled
Version => 2.5.8
Api No => 20021217
Supported ciphers => cast-128 gost rijndael-128 twofish arcfour cast-256 loki97 rijndael-192 saferplus wake blowfish-compat des rijndael-256 serpent xtea blowfish enigma rc2 tripledes 
Supported modes => cbc cfb ctr ecb ncfb nofb ofb stream 

Directive => Local Value => Master Value
mcrypt.algorithms_dir => no value => no value
mcrypt.modes_dir => no value => no value

mhash

MHASH support => Enabled
MHASH API Version => Emulated Support

mongo

MongoDB Support => enabled
Version => 1.4.5
SSL Support => enabled
Streams Support => enabled

Directive => Local Value => Master Value
mongo.allow_empty_keys => 0 => 0
mongo.chunk_size => 262144 => 262144
mongo.cmd => $ => $
mongo.default_host => localhost => localhost
mongo.default_port => 27017 => 27017
mongo.is_master_interval => 15 => 15
mongo.long_as_object => 0 => 0
mongo.native_long => 0 => 0
mongo.ping_interval => 5 => 5

openssl

OpenSSL support => enabled
OpenSSL Library Version => OpenSSL 1.0.1 14 Mar 2012
OpenSSL Header Version => OpenSSL 1.0.1 14 Mar 2012

pcntl

pcntl support => enabled

pcre

PCRE (Perl Compatible Regular Expressions) Support => enabled
PCRE Library Version => 8.12 2011-01-15

Directive => Local Value => Master Value
pcre.backtrack_limit => 1000000 => 1000000
pcre.recursion_limit => 100000 => 100000

PDO

PDO support => enabled
PDO drivers =>  

Phar

Phar: PHP Archive support => enabled
Phar EXT version => 2.0.2
Phar API version => 1.1.1
SVN revision => $Id: a5488937a80433d434af6753d3db8517feaf91df $
Phar-based phar archives => enabled
Tar-based phar archives => enabled
ZIP-based phar archives => enabled
gzip compression => enabled
bzip2 compression => enabled
OpenSSL support => enabled


Phar based on pear/PHP_Archive, original concept by Davey Shafik.
Phar fully realized by Gregory Beaver and Marcus Boerger.
Portions of tar implementation Copyright (c) 2003-2009 Tim Kientzle.
Directive => Local Value => Master Value
phar.cache_list => no value => no value
phar.readonly => On => On
phar.require_hash => On => On

posix

Revision => $Id: 1dfa9997ed76804e53c91e0ce862f3707617b6ed $

readline

Readline Support => enabled
Readline library => EditLine wrapper

Directive => Local Value => Master Value
cli.pager => no value => no value
cli.prompt => \b \>  => \b \> 

redis

Redis Support => enabled
Redis Version => 2.2.4

Reflection

Reflection => enabled
Version => $Id: 31d836a7ac92a37b5c580836d91ad4736fe2f376 $

session

Session Support => enabled
Registered save handlers => files user redis 
Registered serializer handlers => php_serialize php php_binary wddx 

Directive => Local Value => Master Value
session.auto_start => Off => Off
session.cache_expire => 180 => 180
session.cache_limiter => nocache => nocache
session.cookie_domain => no value => no value
session.cookie_httponly => Off => Off
session.cookie_lifetime => 0 => 0
session.cookie_path => / => /
session.cookie_secure => Off => Off
session.entropy_file => /dev/urandom => /dev/urandom
session.entropy_length => 32 => 32
session.gc_divisor => 1000 => 1000
session.gc_maxlifetime => 1440 => 1440
session.gc_probability => 0 => 0
session.hash_bits_per_character => 5 => 5
session.hash_function => 0 => 0
session.name => PHPSESSID => PHPSESSID
session.referer_check => no value => no value
session.save_handler => files => files
session.save_path => /var/lib/php5 => /var/lib/php5
session.serialize_handler => php => php
session.upload_progress.cleanup => On => On
session.upload_progress.enabled => On => On
session.upload_progress.freq => 1% => 1%
session.upload_progress.min_freq => 1 => 1
session.upload_progress.name => PHP_SESSION_UPLOAD_PROGRESS => PHP_SESSION_UPLOAD_PROGRESS
session.upload_progress.prefix => upload_progress_ => upload_progress_
session.use_cookies => On => On
session.use_only_cookies => On => On
session.use_strict_mode => Off => Off
session.use_trans_sid => 0 => 0

shmop

shmop support => enabled

SimpleXML

Simplexml support => enabled
Revision => $Id: 363ea1fc44b0b7775e2ec3ce8456530fec6d1660 $
Schema support => enabled

soap

Soap Client => enabled
Soap Server => enabled

Directive => Local Value => Master Value
soap.wsdl_cache => 1 => 1
soap.wsdl_cache_dir => /tmp => /tmp
soap.wsdl_cache_enabled => 1 => 1
soap.wsdl_cache_limit => 5 => 5
soap.wsdl_cache_ttl => 86400 => 86400

sockets

Sockets Support => enabled

SPL

SPL support => enabled
Interfaces => Countable, OuterIterator, RecursiveIterator, SeekableIterator, SplObserver, SplSubject
Classes => AppendIterator, ArrayIterator, ArrayObject, BadFunctionCallException, BadMethodCallException, CachingIterator, CallbackFilterIterator, DirectoryIterator, DomainException, EmptyIterator, FilesystemIterator, FilterIterator, GlobIterator, InfiniteIterator, InvalidArgumentException, IteratorIterator, LengthException, LimitIterator, LogicException, MultipleIterator, NoRewindIterator, OutOfBoundsException, OutOfRangeException, OverflowException, ParentIterator, RangeException, RecursiveArrayIterator, RecursiveCachingIterator, RecursiveCallbackFilterIterator, RecursiveDirectoryIterator, RecursiveFilterIterator, RecursiveIteratorIterator, RecursiveRegexIterator, RecursiveTreeIterator, RegexIterator, RuntimeException, SplDoublyLinkedList, SplFileInfo, SplFileObject, SplFixedArray, SplHeap, SplMinHeap, SplMaxHeap, SplObjectStorage, SplPriorityQueue, SplQueue, SplStack, SplTempFileObject, UnderflowException, UnexpectedValueException

standard

Dynamic Library Support => enabled
Path to sendmail => /usr/sbin/sendmail -t -i 

Directive => Local Value => Master Value
assert.active => 1 => 1
assert.bail => 0 => 0
assert.callback => no value => no value
assert.quiet_eval => 0 => 0
assert.warning => 1 => 1
auto_detect_line_endings => 0 => 0
default_socket_timeout => 60 => 60
from => no value => no value
url_rewriter.tags => a=href,area=href,frame=src,input=src,form=fakeentry => a=href,area=href,frame=src,input=src,form=fakeentry
user_agent => no value => no value

sysvmsg

sysvmsg support => enabled
Revision => $Id: adf1d2d6be849c46eed3c3ee6f1cbebd1448d6e5 $

tokenizer

Tokenizer Support => enabled

wddx

WDDX Support => enabled
WDDX Session Serializer => enabled

xdebug

xdebug support => enabled
Version => 2.2.3
IDE Key => ubuntu

Supported protocols => Revision
DBGp - Common DeBuGger Protocol => $Revision: 1.145 $

Directive => Local Value => Master Value
xdebug.auto_trace => Off => Off
xdebug.cli_color => 0 => 0
xdebug.collect_assignments => Off => Off
xdebug.collect_includes => On => On
xdebug.collect_params => 0 => 0
xdebug.collect_return => Off => Off
xdebug.collect_vars => Off => Off
xdebug.coverage_enable => On => On
xdebug.default_enable => On => On
xdebug.dump.COOKIE => no value => no value
xdebug.dump.ENV => no value => no value
xdebug.dump.FILES => no value => no value
xdebug.dump.GET => no value => no value
xdebug.dump.POST => no value => no value
xdebug.dump.REQUEST => no value => no value
xdebug.dump.SERVER => no value => no value
xdebug.dump.SESSION => no value => no value
xdebug.dump_globals => On => On
xdebug.dump_once => On => On
xdebug.dump_undefined => Off => Off
xdebug.extended_info => On => On
xdebug.file_link_format => no value => no value
xdebug.idekey => no value => no value
xdebug.max_nesting_level => 100 => 100
xdebug.overload_var_dump => On => On
xdebug.profiler_aggregate => Off => Off
xdebug.profiler_append => Off => Off
xdebug.profiler_enable => Off => Off
xdebug.profiler_enable_trigger => Off => Off
xdebug.profiler_output_dir => /tmp => /tmp
xdebug.profiler_output_name => cachegrind.out.%p => cachegrind.out.%p
xdebug.remote_autostart => Off => Off
xdebug.remote_connect_back => Off => Off
xdebug.remote_cookie_expire_time => 3600 => 3600
xdebug.remote_enable => Off => Off
xdebug.remote_handler => dbgp => dbgp
xdebug.remote_host => localhost => localhost
xdebug.remote_log => no value => no value
xdebug.remote_mode => req => req
xdebug.remote_port => 9000 => 9000
xdebug.scream => Off => Off
xdebug.show_exception_trace => Off => Off
xdebug.show_local_vars => Off => Off
xdebug.show_mem_delta => Off => Off
xdebug.trace_enable_trigger => Off => Off
xdebug.trace_format => 0 => 0
xdebug.trace_options => 0 => 0
xdebug.trace_output_dir => /tmp => /tmp
xdebug.trace_output_name => trace.%c => trace.%c
xdebug.var_display_max_children => 128 => 128
xdebug.var_display_max_data => 512 => 512
xdebug.var_display_max_depth => 3 => 3

xml

XML Support => active
XML Namespace Support => active
libxml2 Version => 2.7.8

xmlreader

XMLReader => enabled

xmlwriter

XMLWriter => enabled

Zend OPcache

Opcode Caching => Disabled
Optimization => Disabled
Startup Failed => Opcode Caching is disabled for CLI

Directive => Local Value => Master Value
opcache.blacklist_filename => no value => no value
opcache.consistency_checks => 0 => 0
opcache.dups_fix => Off => Off
opcache.enable => On => On
opcache.enable_cli => Off => Off
opcache.enable_file_override => Off => Off
opcache.error_log => no value => no value
opcache.fast_shutdown => 0 => 0
opcache.file_update_protection => 2 => 2
opcache.force_restart_timeout => 180 => 180
opcache.inherited_hack => On => On
opcache.interned_strings_buffer => 4 => 4
opcache.load_comments => 1 => 1
opcache.log_verbosity_level => 1 => 1
opcache.max_accelerated_files => 2000 => 2000
opcache.max_file_size => 0 => 0
opcache.max_wasted_percentage => 5 => 5
opcache.memory_consumption => 64 => 64
opcache.optimization_level => 0xFFFFFFFF => 0xFFFFFFFF
opcache.preferred_memory_model => no value => no value
opcache.protect_memory => 0 => 0
opcache.restrict_api => no value => no value
opcache.revalidate_freq => 2 => 2
opcache.revalidate_path => Off => Off
opcache.save_comments => 1 => 1
opcache.use_cwd => On => On
opcache.validate_timestamps => On => On

zip

Zip => enabled
Extension Version => $Id: 05dd1ecc211075107543b0ef8cee488dd229fccf $
Zip version => 1.11.0
Libzip version => 0.10.1

zlib

ZLib Support => enabled
Stream Wrapper => compress.zlib://
Stream Filter => zlib.inflate, zlib.deflate
Compiled Version => 1.2.3.4
Linked Version => 1.2.3.4

Directive => Local Value => Master Value
zlib.output_compression => Off => Off
zlib.output_compression_level => -1 => -1
zlib.output_handler => no value => no value

Additional Modules

Module Name
sysvsem
sysvshm
```