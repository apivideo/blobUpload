Creating a video uploader with JavaScript and [api.video](https://api.video)

Videos are very large files, and all servers have a limit on filesize upload.  The last thing you want your users to see (after waiting for the file to upload) is a "413: request too large" error.

The fix is to use the HTML 5 File API to slice the video into smaller bits, and to upload each smaller chunk.

In this demo, videos are split into 1 MB chunks, but larger sizes are ok (at APi.video, we suggest staying under 100MB per chunk). 


## Getting started

All HTML5 and vanilla JS.

All you need is a delegated upload token from [api.video](https://api.video). Replace the token parameter in the variable ```url```, nad your own version will be running in no time.

[delegated upload docs](https://docs.api.video/reference#videos-delegated-upload)

## Test it out!

[upload.a.video](https://upload.a.video)