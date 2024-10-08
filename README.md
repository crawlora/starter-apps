### Sample crawlora app

This is the sample crawlora app that is used to publish and update app for crawlora dashboard.



## documentation

[app publish documentation](https://apidoc.crawlora.com/operation/operation-applicationcontroller_create)

## Update

in case if you want to update an existing app add `app_id` in `crawlora.json`


```json
# crawlora.json
{
    "env":{
        "key":"value"
    },
    "entrypoint": "./.dist/index.js",
    "function": "default",
    "screenshot_files": ["./assets/screenshot_1.png", "./assets/screenshot_2.png", "./assets/screenshot_3.png", "./assets/screenshot_4.png"],
    "logo_file": "./assets/logo.png",
    "banner_file": "./assets/banner.png",
    "title": "Google Links searches app starter",
    "short_description": "Get google links quickly",
    "version":"1.0.0",
    "documentation_file": "./documentation.md",
    "input_file": "./input.json",
    "app_id": "3636e627-4e2c-4293-acb2-1c2e4d856b87"
}
````