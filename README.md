# alfred-datadog-dashboards-workflow

An [Alfred](https://www.alfredapp.com/) workflow to search your [Datadog](https://www.datadoghq.com) dashboards and select one to open in your default browser.

![screenshot of alfred-datadog-dashboards-workflow](docs/screenshot.png)

## Installation

Clone this repo and run:

```
bin/install
```

## Configuration

The plugin needs a Datadog API key and Application key. You can find or create one on the ["Integrations" -> "APIs" page](https://app.datadoghq.com/account/settings#api).


![screenshot of alfred-datadog-dashboards-workflow-set-apikey-command](docs/dd-set-apikey.png)
![screenshot of alfred-datadog-dashboards-workflow-set-appkey-command](docs/dd-set-appkey.png)

This command create and update a file `~/.datadogrc`.
