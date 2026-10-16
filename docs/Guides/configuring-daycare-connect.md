# How to configure DayCare Connect

There are various settings that you can tweak and change to take control over your DayCare Connect API.

In this guide, we will go over some of the available configuration settings and how they affect the DayCare Connect API.

## General settings

The first section you will notice in your DayCare Connect configuration, is the General Settings section.

Here you can control basic API behaviour like for example timeouts, the base URL and various other general settings.

### General Settings Reference

The following table outlines all of the settings under the General tab:

| Setting | Default Value                  | Required | Description                                                                 |
| ------- | ------------------------------ | -------- | --------------------------------------------------------------------------- |
| BaseUrl | https://my-daycare.connect/api | Yes      | The base URL for your DayCare Connect API to which requests are to be sent. |
|Timeout|60|Yes| The timeout in seconds. An error will be returned to the client when this is exceeded.| 