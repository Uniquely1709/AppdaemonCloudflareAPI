# AppdaemonCloudflareAPI
Connects via API to your Cloudflare account and fetches data from one specified zone. 
For each record in your dns settings this app will create a sensor in Home Assistant which includes basic information about the record. 

![Preview](https://github.com/dolphinxjd/AppdaemonCloudflareAPI/blob/main/cloudflare.png?raw=true)

The really intresting information require at least Cloudflare Pro, which i dont have. Therefore I didn't implement these, because currently I don't have the possibility to test it. 

To make this work, you have to replace the api_token, global_token, zone and email address. You can get all these information from your [Dashboard](dash.cloudflare.com).

The timer defines time beteween each update in minutes. Default value is every hour.

### "requests" python-package in Appdaemon required!
## only works with appdaemon 4.0.4 or later !!!
