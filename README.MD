# SMirror
This is vision of future smart mirror with personalized dashboard.

## Hardware
A two-way mirror, is a mirror that is partially reflective and partially transparent. Perfect for this purpose because lcd display placed behind the mirror is visible and with contrast adjustments can be used for information visualization. Whole dashboard is powered by Raspberry PI 3, which is connected to internet. By default set contains integrated webcamera (use described below).

## Features
### Face recognition (authentication)
SMirror could be used for more users without any annoying logging into own dashboard. Face recognition is supplied natively in system. While standing in front of the mirror integrated webcamera grabs few images of your face and based on that recognizes user and than supplies own content on dashboard.

### Heart rate monitor
SMirror's integrated camera is also used for detecting heart rate based on [bpm project](http://github.com/michalsindelar/bpm) without any need of physical contact.

### Personalized dashboard
User's personalized Dashboard is maintained by Web interface in normal browser. The adjustments are as simple as possible without any complicated improvements directly through mirror and user uses own pc or mobile for settings. In future wide range of widgets will be provided.

#### Widgets
- email integration
- calendar integration
- google maps integration (connected to calendar events)
- forecast
- RSS feeds

## Samples
![Visualization of app notification](docs/vis.png)
