[![badge](https://img.shields.io/twitter/follow/api_video?style=social)](https://twitter.com/intent/follow?screen_name=api_video)

[![badge](https://img.shields.io/github/stars/apivideo/blobUpload?style=social)](https://github.com/apivideo/blobUpload)

[![badge](https://img.shields.io/discourse/topics?server=https%3A%2F%2Fcommunity.api.video)](https://community.api.video)

![](https://github.com/apivideo/API_OAS_file/blob/master/apivideo_banner.png)

<h1 align="center">api.video upload a videoE</h1>

[api.video](https://api.video) is the video infrastructure for product builders. Lightning fast video APIs for integrating, scaling, and managing on-demand & low latency live streaming features in your app.

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
