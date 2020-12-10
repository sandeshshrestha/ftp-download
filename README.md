# Python website backup

Downloads all the files and folders using FTP.

## Usage

```
ftp-download -s example.com -u USER -d ./download_here -D /download_from_here
```

* '-s' '--server', 'Server url'
* '-u' '--user', 'Login username'
* '-p' '--password', 'Login password'
* '-d' '--local_dir', 'Local directory path'
* '-D' '--server_dir', 'Server directory path'
* '-l' '--log', 'Show process log'
