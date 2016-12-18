# PHP compiled extensions for Windows
Set of additional precompiled DLL extensions for offical version of PHP for Windows like XAMP or WAMP or version downloaded from php.net

## Steps to install
1. Look at your PHP version, VC (visual C version), and thread safe status in your phpinfo
2. Select the corresponding directory:
  example: PHP-5.6-VC11-NTS => php version 5.6.* VC11 (visual studio 2012) no thread safe
           PHP-5.6-VC11     => php version 5.6.* VC11 (visual studio 2012) thread safe
3.  select the architecture of your PHP version x64 or x32
4. Select your extention
5. Copy the dll file to your PHP 'ext' directory
6. Enable the extension by adding `extension=php_{extension}.dll` to `php.ini`
* Restart your server if any
