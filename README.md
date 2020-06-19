<p align="center">
    <img src="https://github.com/iRayanKhan/Assets-Repo/blob/master/Chamberlain-Plugin-Branding.png?raw=true" alt="BrandingLogo" width="400” maxHeight="91" />
</p>

[![npm](https://badgen.net/npm/v/homebridge-chamberlain/latest)](https://www.npmjs.com/package/homebridge-chamberlain)
[![npm](https://badgen.net/npm/dt/homebridge-chamberlain)](https://www.npmjs.com/package/homebridge-chamberlain)
[![verified-by-homebridge](https://badgen.net/badge/homebridge/verified/purple)](https://github.com/homebridge/homebridge/wiki/Verified-Plugins)



# Installation
0) Install Homebridge:   ```sudo npm i -g homebridge --unsafe-perm```
1) Download this plugin: ```sudo npm i -g homebridge-chamberlain```
2) Add the [config parameters](https://github.com/iRayanKhan/homebridge-chamberlain/blob/master/config-example.MD) to your [config.json](https://github.com/nfarina/homebridge/blob/master/config-sample.json) file.
3) Run the plugin without the ```deviceID``` field to generate your deviceID's
4) Add the ```deviceID's```

# Issues
If you experience any issues, please check the [common issues page](https://github.com/iRayanKhan/homebridge-chamberlain/wiki/Common-Issues) before opening an issue.

# Development

This starts a server on http://localhost:8000/ you can change the port by running mock-json-server data.json --port=3000.

```bash
npm run mock
```

Inspiration from:
[pymyq](https://github.com/arraylabs/pymyq/blob/master/pymyq/)
