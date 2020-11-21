# Running in Docker Container
`docker build -t hue_react .`

`docker run -d -it -p 8001:80/tcp --name hue_react --restart unless-stopped hue_react`

# philips_hue_react_app
This is a simple ReactJS web application that shows how the Philips Hue API can be used for controlling Philips Hue lights.
<p>
Usage:<br>
Get the IP-address of your Philips Hue bridge and fetch a new username token (see https://developers.meethue.com/documentation/getting-started).<br>
Modify src/config.json with the IP address and the username<br>
Run yarn install<br>
Run yarn start<br>
<p>

![Alt text](https://github.com/LarsBergqvist/philips_hue_react_app/blob/master/screenshot.png?raw=true "A ReactJS app for controlling Philips Hue lights")
