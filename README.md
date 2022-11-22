# gmeet-slack-integration-status

A simple repo that shows the extension status code [here](https://yakshag.github.io/gmeet-slack-integration-status/)

Status is updated by one of the maintainers of https://github.com/yakshaG/google-meet-slack-integration

## 200
````
{
    "status": 200,
    "message": "<strong>Google Meet ⇔ Slack is running. Use Ctrl + V to join meeting, Ctrl + Q to exit meeting.</strong><br />Status updates sometimes may not work for back-to-back, super short meetings (< 1min)."
}
````

## 400
````
{
    "status": 400,
    "message": "<strong>Google Meet ⇔ Slack is down for upgradation.</strong> <br /> You can use Google Meet normally, until the extension is automatically upgraded. Check status <a href='https://github.com/yakshaG/google-meet-slack-integration#google-meet--slack-integration' target='_blank'>here</a>."
}
````
