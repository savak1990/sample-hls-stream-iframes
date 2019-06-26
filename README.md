# sample-hls-stream-iframes
Sample hls stream generated with Apple hls tools. In order to stream it you need stream server with support of http range request. https://github.com/danvk/RangeHTTPServer python server can be used to stream this.

```bash
python3 -m RangeHTTPServer 8000
```