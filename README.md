Quick note, in the http_get.c file, there is a line for WGET_HTTP_HEADER_ADD, "Accept-Encoding", "gzip, deflate",
which added support for bzip2 so the new line of code should look like this: WGET_HTTP_HEADER_ADD, "Accept-Encoding", "gzip, deflate, bzip2",

This has been tested and it is located in examples. It works flawlessly with no issues.
