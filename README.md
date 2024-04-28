# uploadlatest
CLI util for uploading screenshots to FTP or Imgur.

## Configuration
Copy uploadlatest.conf.default to ~/.config/uploadlatest.conf

`cp uploadlatest.conf.default ~/.config/uploadlatest.conf`

Configure this file using your favourite editor.

## Imgur Setup
Imgur needs a client ID. You can set this up at https://api.imgur.com/oauth2/addclient

Set authorization type to anonymous usage without user authorization

Set callback URL to imgur.com

Paste the client ID in your config file.

## Usage
After configuration, you can simply use `uploadlatest` to take the latest screenshot from your screenshots directory.

```
Usage: uploadlatest [options]
Options:
  -s, --service <service>   Specify the service (ftp or imgur)
  -h, --help                Display this help message
```
