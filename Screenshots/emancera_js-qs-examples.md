# JS Video Quickstart

## JS Video Quickstart Default Page -

Room SID: RMb8b3b0f301548cb3b8b978caa546cbf5

![](000_Default_Screen.png)

## Screenshots

### Bandwidth Restrictions

Room SID: RMb8b3b0f301548cb3b8b978caa546cbf5

**Audio**

16k Audio
![](001_BR_Audio_16k.png)

32k Audio
![](001_BR_Audio_32k.png)

64k Audio
![](001_BR_Audio_64k.png)

**Video**

64k Video
![](001_BR_Video_64k.png)

128k Video
![](001_BR_video_128k.png)

256k Video
![](001_BR_video_256k.png)

512k Video
![](001_BR_video_512k.png)

### Local Video Filter

Room SID: RM4396f69606c561f4d862ec01c10b7ea1

![](002_LVF.png)

### Local Video Snapshot

Room SID: RM4396f69606c561f4d862ec01c10b7ea1

![](003_LVS.png)

### Media Device Selection

Room SID: RM4396f69606c561f4d862ec01c10b7ea1

![Default Devices](004_MDS_Default.png)


### Codec Preferences

**Audio Codecs**

ISAC

![ISAC](005_CP_Audio_ISAC.png)

OPUS

![OPUS](005_CP_Audio_Opus.png)

PCMA

![PCMA](005_CP_Audio_PCMA.png)

PCMU

![PCMU](005_CP_Audio_PCMU.png)

**Video Codecs**

H264

![H264](005_CP_Video_H264.png)

VP8

![VP8](005_CP_Video_VP8.png)

VP9

![VP9](005_CP_Video_VP9.png)


### Share Your Screen

Room SID: RM4396f69606c561f4d862ec01c10b7ea1

![Entire Screen Share](006_SS.png)

### Dominant Speaker

Room SID: RM377885cb23c13a73c3c4f3ab251e56d9

Dominant Speaker "Alice"

![Dominant Speaker "Alice"](007_DSD.png)

### Reconnection States and Events

Room SID: RMf1b4bbb7dfef0b77433d428b3e2ae774

Room State Reconnecting
![RSE Reconnecting](008_RSE_Reconnecting.png)

Room State Disconnected
![Reconnect Local](008_RSE_Disconnected.png)


### Network Quality

RMd5e9fc61c6d1eb380a837332c4424d78

LocalParticipant: 1
RemoteParticipant: 3

Alice

![Alice NQ](009_NQ.png)

NQ output

```NQ Stats:
========
{
  "level": 5,
  "audio": {
    "send": 5,
    "recv": 5,
    "sendStats": {
      "bandwidth": {
        "actual": 35520,
        "available": null,
        "level": 5
      },
      "fractionLost": {
        "fractionLost": 0,
        "level": 5
      },
      "latency": {
        "jitter": 0.0041875,
        "rtt": null,
        "level": 5
      }
    },
    "recvStats": {
      "bandwidth": {
        "actual": 110088,
        "available": null,
        "level": 5
      },
      "fractionLost": {
        "fractionLost": 0,
        "level": 5
      },
      "latency": {
        "jitter": null,
        "rtt": 0.0766448974609375,
        "level": 5
      }
    }
  },
  "video": {
    "send": 5,
    "recv": 5,
    "sendStats": {
      "bandwidth": {
        "actual": 1286552,
        "available": null,
        "level": 5
      },
      "fractionLost": {
        "fractionLost": 0,
        "level": 5
      },
      "latency": {
        "jitter": 0.0006777777777777778,
        "rtt": null,
        "level": 5
      }
    },
    "recvStats": {
      "bandwidth": {
        "actual": 3900384,
        "available": 4774574,
        "level": 5
      },
      "fractionLost": {
        "fractionLost": 0,
        "level": 5
      },
      "latency": {
        "jitter": null,
        "rtt": 0.08221944173177083,
        "level": 5
      }
    }
  }
}

```

### Enabling and Disabling Tracks

![Audio track disabled Video track disabled](010_EDT_Disabled_Audio_Disabled_Video.png)

![Audio track disabled Video track enabled](010_EDT_Disabled_Audio_Enabled_Video.png)

![Audio track enabled Video track disabled](010_EDT_Enabled_Audio_Disabled_Video.png)

![Audio track enabled Video track enabled](010_EDT_Enabled_Audio_Disabled_Video.png)


### RemoteParticipant Reconnection States and Events

Room SID: RM5e76c53296d84823c5d0ae839b03a06c

![Default](011_RPRS _Local_Connected_Remote_Connected.png)

![Local Connected and Remote Reconnecting](011_RPRS _Local_Connected_Remote_Reconnecting.png)

![Local Reconnecting and Remote Connected](011_RPRS _Local_Connected_Remote_Reconnecting.png)

### DataTracks

Room SID: RM39e232cbdbc8c0b40f5d64769b8cab02

![DataTracks](012_DT.png)


### Video Track Manual Controls

Room SID: RM81be69fd63ca39208b49aabfe72b8726

![Default](013_VTMC.png)


### Video Track Automatic Controls

![Default Video](014_VTAC_Video_Default.png)

![176x144](014_VTAC_Video_176x144.png)

![640x480](014_VTAC_Video_640x480.png)

![950x540](014_VTAC_Video_950x540.png)
