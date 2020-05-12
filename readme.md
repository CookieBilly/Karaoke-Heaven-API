<p align="center">
    <a href="https://discord.gg/8XBTY5M" alt="Discord">
        <img src="https://img.shields.io/discord/700208007530676314" /></a>

![HK Logo](https://i.imgur.com/mOVnnwj.png)
# Api Information:
In order to use this api, most endpoints require an API key. This can be obtained by using the ```-support``` command and asking for an api key with specific scopes depending on your provided reasoning. Most endpoints will not be given access to for security reasons.

All endpoints are HTTPS endpoints, requests should be made to ```https://api.karaoke-heaven.net```.

## Headers
Header Name | Header Content
------------ | -------------
Authorization | Bearer insertyourapikeyhere
Content-Type | Application/json

## Public (no key requirement endpoints):
Endpoint | Description
------------ | -------------
/event/list | lists upcoming events
/event/info/:eventid | get information about an event
/slots/list | get a list of booked slots at current event
/slots/:slotid | Get information about slots
/coins/:userid | Get the coins of a user
