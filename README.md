We had to copy client files from php-http/guzzle5-adapter and php-http/guzzle7-adapter. They require different version of Guzzle in order to work, so they cannot be required together on this project. Also, we only needed the interfaces.