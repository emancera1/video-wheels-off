# JS Video Quickstart

## JS Video Quickstart Default Page - 

Room SID: RMb8b3b0f301548cb3b8b978caa546cbf5

![](RMb8b3b0f301548cb3b8b978caa546cbf5-qs-20230626-01.png)

## Examples

### Bandwidth Restrictions

Room SID: RMb8b3b0f301548cb3b8b978caa546cbf5

**Audio**

16k Audio
![](RMb8b3b0f301548cb3b8b978caa546cbf5-qs-bw-audio-16k.png)

32k Audio
![](RMb8b3b0f301548cb3b8b978caa546cbf5-qs-bw-audio-32k.png)

64k Audio
![](RMb8b3b0f301548cb3b8b978caa546cbf5-qs-bw-audio-64k.png)

**Video**

64k Video
![](RMb8b3b0f301548cb3b8b978caa546cbf5-qs-bw-video-64k.png)

128k Video
![](RMb8b3b0f301548cb3b8b978caa546cbf5-qs-bw-video-128k.png)

256k Video
![](RMb8b3b0f301548cb3b8b978caa546cbf5-qs-bw-video-256k.png)

512k Video
![](RMb8b3b0f301548cb3b8b978caa546cbf5-qs-bw-video-512k.png)

### Snapshot

Room SID: RMc16436b36dca406ee5ffb72ceea449f1

![](qs-snapshot.png)

### Codecs

Room SID: RMc16436b36dca406ee5ffb72ceea449f1

Note: made sure to `Disconnect from Room` and set the codec each time

**Audio Codecs**

ISAC

![ISAC](RM-codec-audio-ISAC.png)

OPUS

![OPUS](RM-codec-audio-opus.png)

PCMA

![PCMA](RM-codec-audio-pcma.png)

PCMU

![PCMU](RM-codec-audio-pcmu.png)

**Video Codecs**

H264

![H264](RM-codec-video-h264.png)

VP8

![VP8](RM-codec-video-vp8.png)

VP9

![VP9](RM-codec-video-vp9.png)

### Dominant Speaker

Room SID: RM2d3318ffd0d8b96b7523557aefd71774

![Alice is speaking](RM-dominant-speaker.png)

### Network Quality

RM060cc22c0de4663477fd7400b5fd14bf

LocalParticipant: 1
RemoteParticipant: 3

Alice

![Alice NQ](RM-NQ-LP1-RP3.png)

NQ output

```
NQ Stats:
========
{
  "level": 5,
  "audio": {
    "send": 5,
    "recv": 5,
    "sendStats": {
      "bandwidth": {
        "actual": 39904,
        "available": null,
        "level": 5
      },
      "fractionLost": {
        "fractionLost": 0,
        "level": 5
      },
      "latency": {
        "jitter": 0.0066458333333333335,
        "rtt": null,
        "level": 5
      }
    },
    "recvStats": {
      "bandwidth": {
        "actual": 39888,
        "available": null,
        "level": 5
      },
      "fractionLost": {
        "fractionLost": 0,
        "level": 5
      },
      "latency": {
        "jitter": null,
        "rtt": 0.1093902587890625,
        "level": 5
      }
    }
  },
  "video": {
    "send": 5,
    "recv": 5,
    "sendStats": {
      "bandwidth": {
        "actual": 1541632,
        "available": null,
        "level": 5
      },
      "fractionLost": {
        "fractionLost": 0,
        "level": 5
      },
      "latency": {
        "jitter": 0.0014222222222222223,
        "rtt": null,
        "level": 5
      }
    },
    "recvStats": {
      "bandwidth": {
        "actual": 1597568,
        "available": 3252010,
        "level": 5
      },
      "fractionLost": {
        "fractionLost": 0,
        "level": 5
      },
      "latency": {
        "jitter": null,
        "rtt": 0.0377197265625,
        "level": 5
      }
    }
  }
}
```

RM993241457b0358ead0156a755edc180a

LocalParticipant: 1
RemoteParticipant: 2

Charlie

![Charlie NQ](RM-NQ-LP1-RP2.png)

```
NQ Stats:
========
{
  "level": 5,
  "audio": {
    "send": 5,
    "recv": 5,
    "sendStats": null,
    "recvStats": null
  },
  "video": {
    "send": 5,
    "recv": 5,
    "sendStats": null,
    "recvStats": null
  }
}
```

RM0df1dcd152d7f770cd23bdba2254e3ac

LocalParticipant: 1
RemoteParticipant: 1

Mak

![Mak NQ](RM-NQ-LP1-RP1.png)

```
NQ Stats:
========
null
```

RM538c1a15e9ccfd1be9c28d619008034c

LocalParticipant: 2
RemoteParticipant: 0

Bob (no stats, local only)

![DL NQ](RM-NQ-LP2-RP0.png)

```
NQ Stats:
========
{
  "level": 5,
  "audio": {
    "send": 5,
    "recv": 5,
    "sendStats": null,
    "recvStats": null
  },
  "video": {
    "send": 5,
    "recv": 5,
    "sendStats": null,
    "recvStats": null
  }
}
```

RM4a0576ff72b263e1ac950347ef3b99f5

LocalParticipant: 3
RemoteParticipant: 3

Mak

![Mak and DL NQ](RM-NQ-LP3-RP3.png)

Local stats:
```
NQ Stats:
========
{
  "level": 5,
  "audio": {
    "send": 5,
    "recv": 5,
    "sendStats": {
      "bandwidth": {
        "actual": null,
        "available": null,
        "level": 5
      },
      "fractionLost": {
        "fractionLost": null,
        "level": 5
      },
      "latency": {
        "jitter": null,
        "rtt": null,
        "level": 5
      }
    },
    "recvStats": {
      "bandwidth": {
        "actual": null,
        "available": null,
        "level": 5
      },
      "fractionLost": {
        "fractionLost": null,
        "level": 5
      },
      "latency": {
        "jitter": null,
        "rtt": null,
        "level": 5
      }
    }
  },
  "video": {
    "send": 5,
    "recv": 5,
    "sendStats": {
      "bandwidth": {
        "actual": null,
        "available": null,
        "level": 5
      },
      "fractionLost": {
        "fractionLost": null,
        "level": 5
      },
      "latency": {
        "jitter": null,
        "rtt": null,
        "level": 5
      }
    },
    "recvStats": {
      "bandwidth": {
        "actual": null,
        "available": null,
        "level": 5
      },
      "fractionLost": {
        "fractionLost": null,
        "level": 5
      },
      "latency": {
        "jitter": null,
        "rtt": null,
        "level": 5
      }
    }
  }
}
```

### Remote Participant Reconnection States

Room SID: **RM380436988dcd936028e784e516774a2c**

![Reconnect Default](RM-reconnect-01.png)

![Reconnect Local](RM-reconnect-02.png)

### Video Track Manual Controls

Room SID: RM8d9dc47968e9fe6b96d33abfe533ee62

Default State

![Default State](RM-VTMC-01.png)

Errors in console

![Errors](RM-VTMC-02.png)

### Local Filter

Room SID: none

![Why errors?](RM-local-filter-errors.png)

### Media Device Selection

Room SID: RM823456977e1bf006c03c3c8ab874faae

![Default view](RM823456977e1bf006c03c3c8ab874faae-preview-media-01.png)

![Other participant view](RM823456977e1bf006c03c3c8ab874faae-preview-media-02.jpeg)

### Share Your Screen

![GH Repo share](RM-screen-share.png)

### Reconnection States and Events

![Default](RM-reconnect-states-01.png)

![Connected](RM-reconnect-states-02.png)

![Reconnected](RM-reconnect-states-03.png)

![Disconnected](RM-reconnect-states-04.png)

### Enabling and Disabling Tracks

![Audio track disabled](RM-track-disable-audio.png)

![Video track disabled](RM-track-disable-video.png)

### DataTracks

![messaging in DataTracks](RM-data-track.png)

### Video Track Automatic Controls

![Default view](RM-VTAC-default.png)

![Hiding video](RM-VTAC-hide.png)

![Resize to 640x480](RM-VTAC-640x480.png)

![Resize to 176x144](RM-VTAC-176x144.png)
