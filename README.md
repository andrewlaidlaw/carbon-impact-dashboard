# Carbon intensity dashboard
This uses [Node-Red](https://nodered.org/) and the [Node-Red dashboard](https://flows.nodered.org/node/node-red-dashboard) node to create a visual dashboard to present data freely available from the [Carbon Intensity API](https://carbon-intensity.github.io/api-definitions/#carbon-intensity-api-v2-0-0) project. It provides at a glance information on the Carbon impact of current electricity generation for the whole United Kingdom.

### Node-Red
The simple included flow generates the dashboard, and presents data that is updated wvery 30 minutes. This may be modified as required for your own use. The dashboard itself can be found at the `/ui` endpoint.