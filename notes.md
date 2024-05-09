Deploy:
    docs.plantproxy.com
    linked to Cloudflare page:
    https://dash.cloudflare.com/b7e7dd41650391e6a029c101c2029b37/pages/view/plantproxy-docs

Start local server:
    
    # first force rebuild
    hugo --gc --ignoreCache && hugo server --logLevel debug --disableFastRender -p 1313 --noHTTPCache --disableFastRender --ignoreCache -v

Update all Hugo modules to latest:

    hugo mod get -u

Update Hextra to latest:

    hugo mod get -u github.com/imfing/hextra

Organisation:
All images in root folder `/static`, same level as `/content`. Refer to image relative to the folder, like `![](/images/image.png)` if file is `/static/images/image.png`.

Docs:

[https://imfing.github.io/hextra/docs/](https://imfing.github.io/hextra/docs/)

Relevant sources:
https://iphone-tricks.com/tutorial/11057-how-to-use-nfc-on-iphone

Open browser preview tab in vcode:
    Open the palette (Ctrl + Shift + P)
    Select "Simple Browser: Show"
    Enter web address
