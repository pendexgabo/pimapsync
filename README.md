# pimapsync


An small tool to copy messages from one IMAP mailbox to another mailbox

It is not meant to be used as a synchronization tool but rather as a one time migration tool. Though, it will check if a message on the destination box exists and skip it if it does. It will also create any missing folders. It should be safe to run it consecutively.

[Original script](http://projects.webmind.be/snippets/copy_imap_mailbox.phps) by Glenn Matthys (glenn@webmind.be) up to version 1.2

## Dependencies


[PHP imap extension](http://www.php.net/manual/es/ref.imap.php)


## Usage


```./pimapsync host1= user1= pass1= host2= user2= pass2= [options]```

## License

Copyright (c) 2012 Gabriel Sosa

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE. 
