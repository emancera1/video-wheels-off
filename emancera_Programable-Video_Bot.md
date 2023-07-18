# Programable Video Bot Outputs

## Output: help

Programmable Video Bot v0-SNAPSHOT

Running as PID 8 since Fri Mar 10 12:23:12 2023

I understand the follow commands/sids:
 ```
 'ACaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaa 
       Accounts Default Room Settings, if set 

 PAaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaa 
       Participant report including getStats, Room/Protocol track errors, codecs 

 RMaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaa 
       Room summary report 

 CAaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaa [ all | summary (default) ] [ pretty-print ]
       Voice Participant report 

 MTaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaa 
       Track report with bytes/packets sent, rtt, etc. and track events 

 vms [help | ...] 
       Video Media Server report 

 vms2 [-h | ...] 
       Streamer reports 

 recordings [help | ...] 
       Video Recordings report 

 compositions [help | ...] 
       Media Compositions report 

 billing [-h | ...] 
       Storage billing report 

 help 
       Displays this help information'
 ```
##Output:  Accounts Default Room Settings

Account Info
Created On
2023-04-24T18:33:58.934Z
Alias
Video
Modified On
2023-07-17T17:41:36.573Z
Configuration
VS89d337a93513bda1356ff642e11e1b1c
Adhoc Room
enabled
Turn
enabled
Media Region
us1
Record Participants on connect
enabled
Room Timeout
300
Room Type
group
Status Callback URL
https://requestbin.com/
Status Callback Method
POST
Video Codecs
VP8,H264
Account Read Rate Limit
80
Account Write Rate Limit
20
Rooms Concurrent High
2
Participants Concurrent High
4
Concurrent Max Limit
10000
New
1:49
Recently created Rooms
 ```
timestamp                 room sid                            room name                           media region    room type    video codecs
------------------------  ----------------------------------  ----------------------------------  --------------  -----------  --------------
2023-07-18T17:33:30.716Z  RMae6f2fb5e196f2b99678974c2734515f  Roomcomp                            us1             group        H264,VP8
2023-07-18T17:33:29.131Z  RMae6f2fb5e196f2b99678974c2734515f  Roomcomp                            us1             group
2023-07-18T17:06:09.432Z  RMeb8048c42db04254764f7c5d6688995f  RoomA                               us1             group        VP8,H264
2023-07-18T17:06:07.680Z  RMeb8048c42db04254764f7c5d6688995f  RoomA                               us1             group
2023-07-17T22:32:24.249Z  RM58e182659f8c316b27f7c78d90c95b7c  VideoQuickStart                     us1             group        H264,VP8
2023-07-17T22:32:24.246Z  RM58e182659f8c316b27f7c78d90c95b7c  VideoQuickStart                     us1             group
2023-07-17T22:26:28.795Z  RM93e3f651077fcb54192068c98847b889  RM93e3f651077fcb54192068c98847b889  us1             group        H264,VP8
2023-07-17T22:26:28.791Z  RM93e3f651077fcb54192068c98847b889  RM93e3f651077fcb54192068c98847b889  us1             group
2023-07-17T22:26:22.802Z  RMa48422765a6e15f13181701879576210  test                                us1             group        VP8,H264
2023-07-17T22:26:22.798Z  RMa48422765a6e15f13181701879576210  test                                us1             group
2023-07-17T22:22:47.087Z  RM727d727797d4752cfa82654655f452c0  quickstart                          us1             group        H264,VP8
2023-07-17T22:22:47.084Z  RM727d727797d4752cfa82654655f452c0  quickstart                          us1             group
2023-07-17T22:22:29.290Z  RM64095864538f2005f0022486f1d5de84  quickstart                          us1             group        H264,VP8
2023-07-17T22:22:29.286Z  RM64095864538f2005f0022486f1d5de84  quickstart                          us1             group
2023-07-17T22:17:37.222Z  RM0c219cba3d3635f46439a7941504d6a2  RM0c219cba3d3635f46439a7941504d6a2  us1             group        H264,VP8
2023-07-17T22:17:37.219Z  RM0c219cba3d3635f46439a7941504d6a2  RM0c219cba3d3635f46439a7941504d6a2  us1             group
2023-07-17T22:17:30.736Z  RM0a04b514a301f7758f3eb2b6b63c9a08  VideoQuickStart                     us1             group        H264,VP8
2023-07-17T22:17:30.732Z  RM0a04b514a301f7758f3eb2b6b63c9a08  VideoQuickStart                     us1             group
2023-07-17T22:16:07.187Z  RMb29cfd4cb56b548c43178443d62dd761  RMb29cfd4cb56b548c43178443d62dd761  us1             group        H264,VP8
2023-07-17T22:16:07.183Z  RMb29cfd4cb56b548c43178443d62dd761  RMb29cfd4cb56b548c43178443d62dd761  us1             group
2023-07-17T22:15:14.569Z  RMa5c0c59223e366ee55f352d4f6692f7f  test                                us1             group        H264,VP8
2023-07-17T22:15:14.556Z  RMa5c0c59223e366ee55f352d4f6692f7f  test                                us1             group
2023-07-17T22:14:12.006Z  RM4a94846f7722d6c29fd560f5e9034b18  jstest                              us1             group        VP8,H264
2023-07-17T22:14:12.003Z  RM4a94846f7722d6c29fd560f5e9034b18  jstest                              us1             group
2023-07-17T20:56:55.534Z  RM3279dccf2043bea5fafec37f5efb6c02  RM3279dccf2043bea5fafec37f5efb6c02  us1             group        H264,VP8
2023-07-17T20:56:55.531Z  RM3279dccf2043bea5fafec37f5efb6c02  RM3279dccf2043bea5fafec37f5efb6c02  us1             group
2023-07-17T20:50:14.098Z  RM743115066eb8467b69116c28ca235d93  RM743115066eb8467b69116c28ca235d93  us1             group        H264,VP8
2023-07-17T20:50:14.094Z  RM743115066eb8467b69116c28ca235d93  RM743115066eb8467b69116c28ca235d93  us1             group
2023-07-17T20:49:57.670Z  RM442ebdb8482979218ac5afdf189d533b  VideoQuickStart                     us1             group        VP8,H264
2023-07-17T20:49:57.656Z  RM442ebdb8482979218ac5afdf189d533b  VideoQuickStart                     us1             group
2023-07-17T20:46:43.293Z  RM8a2d889894f3901abd9e5b107a3df1e8  RM8a2d889894f3901abd9e5b107a3df1e8  us1             group        H264,VP8
2023-07-17T20:46:43.290Z  RM8a2d889894f3901abd9e5b107a3df1e8  RM8a2d889894f3901abd9e5b107a3df1e8  us1             group
2023-07-17T20:46:27.814Z  RM19b2a3daeb16920837ffa1a93c3c9cf1  Quickstart                          us1             group        H264,VP8
2023-07-17T20:46:27.811Z  RM19b2a3daeb16920837ffa1a93c3c9cf1  Quickstart                          us1             group
2023-07-17T20:37:46.982Z  RM83d232985f9cbe1e4694325c1268cbf1  RM83d232985f9cbe1e4694325c1268cbf1  us1             group        VP8,H264
2023-07-17T20:37:46.979Z  RM83d232985f9cbe1e4694325c1268cbf1  RM83d232985f9cbe1e4694325c1268cbf1  us1             group
2023-07-17T20:37:36.577Z  RM238a0168059b8cb7fe636fb88e2bad4e  test                                us1             group        H264,VP8
2023-07-17T20:37:36.564Z  RM238a0168059b8cb7fe636fb88e2bad4e  test                                us1             group
2023-07-17T20:36:13.224Z  RMf0c744f518b2682d2c3c3d5edccb335a  Room 1                              us1             group        H264,VP8
2023-07-17T20:36:13.221Z  RMf0c744f518b2682d2c3c3d5edccb335a  Room 1                              us1             group
2023-07-17T20:34:06.357Z  RM42a3da9346d6ae541563c96b4fc4c991  RM42a3da9346d6ae541563c96b4fc4c991  us1             group        H264,VP8
2023-07-17T20:34:06.353Z  RM42a3da9346d6ae541563c96b4fc4c991  RM42a3da9346d6ae541563c96b4fc4c991  us1             group
2023-07-17T20:33:59.356Z  RM351f86164eccb53174ffcfd5bc059ecf  Room 1                              us1             group        H264,VP8
2023-07-17T20:33:59.352Z  RM351f86164eccb53174ffcfd5bc059ecf  Room 1                              us1             group
2023-07-17T18:00:28.854Z  RM7a4204f205c0beb1eced53be1bdb40d8  VideoQuickStart                     us1             group        VP8,H264
2023-07-17T18:00:28.851Z  RM7a4204f205c0beb1eced53be1bdb40d8  VideoQuickStart                     us1             group
2023-07-17T17:59:47.840Z  RM68ae438e5c2f6612d22c4b31f0547d88  VideoQuickStart                     us1             group        H264,VP8
2023-07-17T17:59:47.837Z  RM68ae438e5c2f6612d22c4b31f0547d88  VideoQuickStart                     us1             group
2023-07-17T17:52:52.705Z  RMf58462f7fe7bcf903496a03cd7981753  RMf58462f7fe7bcf903496a03cd7981753  us1             group        VP8,H264
2023-07-17T17:52:52.702Z  RMf58462f7fe7bcf903496a03cd7981753  RMf58462f7fe7bcf903496a03cd7981753  us1             group
 ```


##Output: Participant report including getStats, Room/Protocol track errors, codecs 

Participant Analysis for PA72336d73c51accd4aebfb6fd6e8e3fe5
Participant Info
Identity
emancera
RoomSid
RMae6f2fb5e196f2b99678974c2734515f
AccountSid
ACfecd5668dfccc1bcb13195a261f5a305
Account Friendly Name
None
Country
None
City
None
Start Time
2023-07-18T17:33:30.716Z
End Time
2023-07-18T17:37:14.148Z
Date Created
2023-07-18T17:33:30.716Z
Date Update
2023-07-18T17:37:14.148Z
Duration
223
Status
disconnected
Platform Name
None
Platform Version
None
Hardware Device Model
None
Hardware Device Manufacturer
None
Hardware Device Architecture
None
SDK Version
None
Video Codec
None

Participant Summary Report
```
Summary for Room: Roomcomp | RMae6f2fb5e196f2b99678974c2734515f | ACfecd5668dfccc1bcb13195a261f5a305
Topology: group | Adhoc: False | TURN: True | Recording on Connect: True | Video Codecs: H264,VP8 | Media Region: us1 | Audio Only: False | Is V3 Room: False
VMS: VM82054606040e4ad60bec9e68d3c0dfe9
Participants:
P1: PA72336d73c51accd4aebfb6fd6e8e3fe5 | CAd80ee5b58f4b09dec205e8f5aa617287 | emancera | unified | jsdk 2.25.0 | Chrome 114.0.0 
2023-07-18T17:33:30.716Z: P1 sent connect with audio + video tracks
2023-07-18T17:33:30.716Z: P1 sent offer for peer connection id c35578f1-3cdd-4e32-8304-e17818815c5e revision: 1
2023-07-18T17:33:30.716Z: P1 requests active_speaker, network_quality, render_hints, publisher_hints, track_priority, track_switch_off
2023-07-18T17:33:30.716Z: P1 requests video bandwidth profile with active speaker priority: standard, mode as collaboration
2023-07-18T17:33:30.716Z: P1 updated subscribe rules: { include all }
2023-07-18T17:33:30.871Z: P1 received connected
2023-07-18T17:33:30.871Z: P1 received answer for peer connection id c35578f1-3cdd-4e32-8304-e17818815c5e revision: 1
2023-07-18T17:33:30.871Z: P1 received track_priority : 7f35462e-0fcc-4a38-8785-c58f57dd1ecc, active_speaker : 7ad693a5-8022-4d3a-9ab1-0b752a75f957, render_hints : d2abe6c2-13a0-4773-893f-5d1f9daf4cb1, publisher_hints : fc7c89d3-219c-4ce2-8120-86f6bf4e1af2, track_switch_off : 5273e819-f600-48b9-8740-a2db936efa3a, network_quality : 0e448a21-1731-4206-addf-97d84bff7e31
2023-07-18T17:33:30.871Z: P1 is connected with media region us1, signaling region us1, and session timeout 30
2023-07-18T17:33:30.872Z: P1 received offer for peer connection id c35578f1-3cdd-4e32-8304-e17818815c5e revision: 2
2023-07-18T17:33:31.016Z: P1 published video: camera-1689701278120 / MT687afde64d5d654ca8942bf29c840b6f revision: 2 priority: low
2023-07-18T17:33:31.016Z: P1 published audio: 57f47d2c-09bb-41af-86d4-6691116efd34 / MTfdb17797396c2e85bdfb36d73cb302db revision: 2 priority: standard
2023-07-18T17:33:31.029Z: P1 sent answer for peer connection id c35578f1-3cdd-4e32-8304-e17818815c5e revision: 2
2023-07-18T17:33:31.135Z: [ice_connection_state_change] for P1 with state CONNECTED
2023-07-18T17:33:31.323Z: P1 sent ice complete for peer connection id c35578f1-3cdd-4e32-8304-e17818815c5e with no ice candidates (could be in SDP) revision: 1
2023-07-18T17:33:39.023Z: [ice_connection_state_change] for P1 with state COMPLETED
2023-07-18T17:35:11.034Z: P1 received offer for peer connection id c35578f1-3cdd-4e32-8304-e17818815c5e revision: 3
2023-07-18T17:35:11.034Z: P1 subscribed: MTad6e48d68b2805f218ddf610684db65b revision: 1
2023-07-18T17:35:11.034Z: P1 subscribed: MTed8b9ba7cbb31e0e95307a8f82e08e18 revision: 1
2023-07-18T17:35:11.177Z: P1 sent answer for peer connection id c35578f1-3cdd-4e32-8304-e17818815c5e revision: 3
2023-07-18T17:36:51.182Z: P1 sent update with track changes: audio was muted revision: 6
2023-07-18T17:36:51.186Z: P1 published video: camera-1689701278120 / MT687afde64d5d654ca8942bf29c840b6f revision: 3 priority: low
2023-07-18T17:36:51.186Z: P1 published audio: 57f47d2c-09bb-41af-86d4-6691116efd34 / MTfdb17797396c2e85bdfb36d73cb302db revision: 3 priority: standard
2023-07-18T17:37:14.148Z: P1 sent disconnect
2023-07-18T17:37:14.148Z: [participant_disconnected] for P1 
2023-07-18T17:37:14.149Z: P1 received disconnected
2023-07-18T17:37:14.161Z: [group_billing_event] for P1 with bytes sent 36135741, bytes received 83114958, recording time in secs 198
```
No errors found for PA72336d73c51accd4aebfb6fd6e8e3fe5

Track Events
 ```
  rev  timestamp                 event           sid                                 id                                    kind
-----  ------------------------  --------------  ----------------------------------  ------------------------------------  ------
    3  2023-07-18T17:33:30.871Z  track_added     MT687afde64d5d654ca8942bf29c840b6f  f783c20e-4155-451a-8fe3-26309d453051  video
    3  2023-07-18T17:33:30.871Z  track_added     MTfdb17797396c2e85bdfb36d73cb302db  fdfaa85d-8236-4758-824b-503a32c441b2  audio
    6  2023-07-18T17:36:51.186Z  track_disabled  MTfdb17797396c2e85bdfb36d73cb302db  fdfaa85d-8236-4758-824b-503a32c441b2  audio
```
Selected active-ice-candidate-pair:
```
No active-ice-candidate-pair published to video-insights
```

Group Room ice events:
```
timestamp                 ice state
------------------------  -----------
2023-07-18T17:33:31.135Z  CONNECTED
2023-07-18T17:33:39.023Z  COMPLETED
```

VSG events for PA72336d73c51accd4aebfb6fd6e8e3fe5
 
```
Room Name: Roomcomp | Sid: RMae6f2fb5e196f2b99678974c2734515f | Account Sid: ACfecd5668dfccc1bcb13195a261f5a305
Call Sid: CAd80ee5b58f4b09dec205e8f5aa617287 | Participant Sid: PA72336d73c51accd4aebfb6fd6e8e3fe5 | Identity: emancera | Signaling Region: us1
2023-07-18T17:33:30.59Z: INITIAL to AUTHENTICATING on event room-info-ws-request
2023-07-18T17:33:30.6Z: AUTHENTICATING to ICING on event authentication-event: {"success":true}
2023-07-18T17:33:30.604Z: ICING to ICED on event ice-event: {"ice_servers":[{"urls":"turn:ashburn.turn.twilio.com:3478?transport=udp","username":"c143de1e9501066c33111d67659fd9a7436882aaa9f5901e5bb0cb17e79079c1"},{"urls":"turns:ashburn.turn.twilio.com:443?transport=tcp","username":"c143de1e9501066c33111d67659fd9a7436882aaa9f5901e5bb0cb17e79079c1"}],"success":true}
2023-07-18T17:33:30.709Z: ICED to CONNECTING on event room-info-ws-request
2023-07-18T17:33:30.719Z: CONNECTING to CONNECTING on event room-info
2023-07-18T17:33:30.873Z: CONNECTING to CONNECTED on event server-connected-event
2023-07-18T17:37:14.148Z: CONNECTED to DISCONNECTING on event room-info-ws-request
2023-07-18T17:37:14.148Z: DISCONNECTING to FINISHED on event connection-closed-event: {"reason":"REMOTE","close_status":-1}
```

##Output: Room Summary Report

Room Info
Room Analysis for RMae6f2fb5e196f2b99678974c2734515f
Room Info
AccountSid
ACfecd5668dfccc1bcb13195a261f5a305
Created On
2023-07-18 17:33:30.716
Ended On
2023-07-18 17:42:26.731
Room Name
Roomcomp
VideoMediaServerSid
VM82054606040e4ad60bec9e68d3c0dfe9
Status Callback
POST https://requestbin.com/
Room Type
group
Unique Participants
2
Unique Identities
2
Turn Enabled
True
Recordings Enabled
True
IsAdhoc
False
Completed via REST API
No
Is V3 Room
False
Media Region
us1
Video Codecs
VP8, H264
Status
completed
Duration (seconds)
536
Maximum Participants
50
Maximum Participant Duration
14400

Participants Info
```
joined (UTC)             left (UTC)               sid                                 identity    ICE    published    subscribed
-----------------------  -----------------------  ----------------------------------  ----------  -----  -----------  ------------
2023-07-18 17:33:30.717  2023-07-18 17:37:14.148  PA72336d73c51accd4aebfb6fd6e8e3fe5  emancera    YES    YES          YES
2023-07-18 17:35:10.979  2023-07-18 17:37:16.256  PA3622d6cf641ded9cbfc434ade076652b  Erickphone  YES    YES          YES
 ```

1:18
Room Summary Report
 ```
Summary for Room: Roomcomp | RMae6f2fb5e196f2b99678974c2734515f | ACfecd5668dfccc1bcb13195a261f5a305
Topology: group | Adhoc: False | TURN: True | Recording on Connect: True | Video Codecs: H264,VP8 | Media Region: us1 | Audio Only: False | Is V3 Room: False
VMS: VM82054606040e4ad60bec9e68d3c0dfe9
Participants:
P1: PA72336d73c51accd4aebfb6fd6e8e3fe5 | CAd80ee5b58f4b09dec205e8f5aa617287 | emancera | unified | jsdk 2.25.0 | Chrome 114.0.0 
P2: PA3622d6cf641ded9cbfc434ade076652b | CA1a50afccd8f358818f21011575869a10 | Erickphone | unified | jsdk 2.25.0 | Chrome Mobile 114.0.0 
2023-07-18T17:33:29.130Z: [add_labeled_room]
2023-07-18T17:33:29.131Z: [room_created]
2023-07-18T17:33:30.716Z: P1 sent connect with audio + video tracks
2023-07-18T17:33:30.716Z: P1 sent offer for peer connection id c35578f1-3cdd-4e32-8304-e17818815c5e revision: 1
2023-07-18T17:33:30.716Z: P1 requests active_speaker, network_quality, render_hints, publisher_hints, track_priority, track_switch_off
2023-07-18T17:33:30.716Z: P1 requests video bandwidth profile with active speaker priority: standard, mode as collaboration
2023-07-18T17:33:30.716Z: [room_created]
2023-07-18T17:33:30.716Z: P1 updated subscribe rules: { include all }
2023-07-18T17:33:30.717Z: [add_room_recording] with recording rules: { include all }
2023-07-18T17:33:30.869Z: [add_room_recording]
2023-07-18T17:33:30.871Z: P1 received connected
2023-07-18T17:33:30.871Z: P1 received answer for peer connection id c35578f1-3cdd-4e32-8304-e17818815c5e revision: 1
2023-07-18T17:33:30.871Z: P1 received track_priority : 7f35462e-0fcc-4a38-8785-c58f57dd1ecc, active_speaker : 7ad693a5-8022-4d3a-9ab1-0b752a75f957, render_hints : d2abe6c2-13a0-4773-893f-5d1f9daf4cb1, publisher_hints : fc7c89d3-219c-4ce2-8120-86f6bf4e1af2, track_switch_off : 5273e819-f600-48b9-8740-a2db936efa3a, network_quality : 0e448a21-1731-4206-addf-97d84bff7e31
2023-07-18T17:33:30.871Z: P1 is connected with media region us1, signaling region us1, and session timeout 30
2023-07-18T17:33:30.872Z: P1 received offer for peer connection id c35578f1-3cdd-4e32-8304-e17818815c5e revision: 2
2023-07-18T17:33:31.016Z: P1 published video: camera-1689701278120 / MT687afde64d5d654ca8942bf29c840b6f revision: 2 priority: low
2023-07-18T17:33:31.016Z: P1 published audio: 57f47d2c-09bb-41af-86d4-6691116efd34 / MTfdb17797396c2e85bdfb36d73cb302db revision: 2 priority: standard
2023-07-18T17:33:31.029Z: P1 sent answer for peer connection id c35578f1-3cdd-4e32-8304-e17818815c5e revision: 2
2023-07-18T17:33:31.135Z: [ice_connection_state_change] for P1 with state CONNECTED
2023-07-18T17:33:31.323Z: P1 sent ice complete for peer connection id c35578f1-3cdd-4e32-8304-e17818815c5e with no ice candidates (could be in SDP) revision: 1
2023-07-18T17:33:39.023Z: [ice_connection_state_change] for P1 with state COMPLETED
2023-07-18T17:35:10.979Z: P2 sent connect with audio + video tracks
2023-07-18T17:35:10.979Z: P2 sent offer for peer connection id 72ec96bb-ee1e-43b2-b495-4333ad1f5e24 revision: 1
2023-07-18T17:35:10.979Z: P2 requests active_speaker, network_quality, render_hints, publisher_hints, track_priority, track_switch_off
2023-07-18T17:35:10.979Z: P2 requests video bandwidth profile with active speaker priority: standard, mode as collaboration, maximum subscription bandwidth: 2500000
2023-07-18T17:35:10.979Z: P2 updated subscribe rules: { include all }
2023-07-18T17:35:11.030Z: P2 received connected
2023-07-18T17:35:11.030Z: P2 received answer for peer connection id 72ec96bb-ee1e-43b2-b495-4333ad1f5e24 revision: 1
2023-07-18T17:35:11.030Z: P2 received track_priority : e5e48e54-0027-4935-93a2-5bba8181df31, active_speaker : 7aaa0f42-a40c-478a-b00a-5e6a9ac04438, render_hints : 1bbf1934-41f5-413e-9de9-16b3bda5cd60, publisher_hints : 45aa848a-eaa4-4696-b11f-312924ca55bd, track_switch_off : 29c69832-e956-4203-b65d-e3d3eef07ff2, network_quality : 09a673cb-72a8-4956-b487-f40f5ff3a1fe
2023-07-18T17:35:11.030Z: P2 is connected with media region us1, signaling region us1, and session timeout 30
2023-07-18T17:35:11.033Z: P2 received offer for peer connection id 72ec96bb-ee1e-43b2-b495-4333ad1f5e24 revision: 2
2023-07-18T17:35:11.033Z: P2 subscribed: MT687afde64d5d654ca8942bf29c840b6f revision: 1
2023-07-18T17:35:11.033Z: P2 subscribed: MTfdb17797396c2e85bdfb36d73cb302db revision: 1
2023-07-18T17:35:11.034Z: P1 received offer for peer connection id c35578f1-3cdd-4e32-8304-e17818815c5e revision: 3
2023-07-18T17:35:11.034Z: P1 subscribed: MTad6e48d68b2805f218ddf610684db65b revision: 1
2023-07-18T17:35:11.034Z: P1 subscribed: MTed8b9ba7cbb31e0e95307a8f82e08e18 revision: 1
2023-07-18T17:35:11.177Z: P1 sent answer for peer connection id c35578f1-3cdd-4e32-8304-e17818815c5e revision: 3
2023-07-18T17:35:11.259Z: P2 published video: camera-1689701643162 / MTed8b9ba7cbb31e0e95307a8f82e08e18 revision: 2 priority: low
2023-07-18T17:35:11.259Z: P2 published audio: 9f4d9b22-71a3-484e-91c8-3e4472740012 / MTad6e48d68b2805f218ddf610684db65b revision: 2 priority: standard
2023-07-18T17:35:11.376Z: P2 sent answer for peer connection id 72ec96bb-ee1e-43b2-b495-4333ad1f5e24 revision: 2
2023-07-18T17:35:11.407Z: [ice_connection_state_change] for P2 with state CONNECTED
2023-07-18T17:35:11.604Z: P2 sent ice complete for peer connection id 72ec96bb-ee1e-43b2-b495-4333ad1f5e24 with no ice candidates (could be in SDP) revision: 1
2023-07-18T17:35:19.295Z: [ice_connection_state_change] for P2 with state COMPLETED
2023-07-18T17:35:34.611Z: [room_recording_updated_via_api] with recording rules: { exclude all }
2023-07-18T17:35:34.612Z: [room_recording_updated_via_api] with recording rules: { exclude all }
2023-07-18T17:35:45.576Z: P2 sent update with track changes: audio was muted revision: 6
2023-07-18T17:35:45.580Z: P2 published video: camera-1689701643162 / MTed8b9ba7cbb31e0e95307a8f82e08e18 revision: 3 priority: low
2023-07-18T17:35:45.580Z: P2 published audio: 9f4d9b22-71a3-484e-91c8-3e4472740012 / MTad6e48d68b2805f218ddf610684db65b revision: 3 priority: standard
2023-07-18T17:35:49.909Z: P2 sent update with track changes: audio was unmuted revision: 7
2023-07-18T17:35:49.912Z: P2 published video: camera-1689701643162 / MTed8b9ba7cbb31e0e95307a8f82e08e18 revision: 4 priority: low
2023-07-18T17:35:49.912Z: P2 published audio: 9f4d9b22-71a3-484e-91c8-3e4472740012 / MTad6e48d68b2805f218ddf610684db65b revision: 4 priority: standard
2023-07-18T17:35:52.566Z: [room_recording_updated_via_api] with recording rules: { include all }
2023-07-18T17:35:52.567Z: [room_recording_updated_via_api] with recording rules: { include all }
2023-07-18T17:35:58.966Z: [room_recording_updated_via_api] with recording rules: { exclude all }
2023-07-18T17:35:58.969Z: [room_recording_updated_via_api] with recording rules: { exclude all }
2023-07-18T17:36:05.406Z: [room_recording_updated_via_api] with recording rules: { include all }
2023-07-18T17:36:05.407Z: [room_recording_updated_via_api] with recording rules: { include all }
2023-07-18T17:36:32.592Z: P2 sent update with track changes: audio was muted revision: 8
2023-07-18T17:36:32.596Z: P2 published video: camera-1689701643162 / MTed8b9ba7cbb31e0e95307a8f82e08e18 revision: 5 priority: low
2023-07-18T17:36:32.596Z: P2 published audio: 9f4d9b22-71a3-484e-91c8-3e4472740012 / MTad6e48d68b2805f218ddf610684db65b revision: 5 priority: standard
2023-07-18T17:36:51.182Z: P1 sent update with track changes: audio was muted revision: 6
2023-07-18T17:36:51.186Z: P1 published video: camera-1689701278120 / MT687afde64d5d654ca8942bf29c840b6f revision: 3 priority: low
2023-07-18T17:36:51.186Z: P1 published audio: 57f47d2c-09bb-41af-86d4-6691116efd34 / MTfdb17797396c2e85bdfb36d73cb302db revision: 3 priority: standard
2023-07-18T17:36:52.378Z: P2 sent update with track changes: audio was unmuted revision: 9
2023-07-18T17:36:52.382Z: P2 published video: camera-1689701643162 / MTed8b9ba7cbb31e0e95307a8f82e08e18 revision: 6 priority: low
2023-07-18T17:36:52.382Z: P2 published audio: 9f4d9b22-71a3-484e-91c8-3e4472740012 / MTad6e48d68b2805f218ddf610684db65b revision: 6 priority: standard
2023-07-18T17:37:14.148Z: P1 sent disconnect
2023-07-18T17:37:14.148Z: [participant_disconnected] for P1 
2023-07-18T17:37:14.149Z: P1 received disconnected
2023-07-18T17:37:14.150Z: [participant_removed]
2023-07-18T17:37:14.156Z: P2 received offer for peer connection id 72ec96bb-ee1e-43b2-b495-4333ad1f5e24 revision: 3
2023-07-18T17:37:14.156Z: P2 unsubscribed from: MT687afde64d5d654ca8942bf29c840b6f revision: 2
2023-07-18T17:37:14.156Z: P2 unsubscribed from: MTfdb17797396c2e85bdfb36d73cb302db revision: 2
2023-07-18T17:37:14.161Z: [group_billing_event] for P1 with bytes sent 36135741, bytes received 83114958, recording time in secs 198
2023-07-18T17:37:14.293Z: P2 sent answer for peer connection id 72ec96bb-ee1e-43b2-b495-4333ad1f5e24 revision: 3
2023-07-18T17:37:16.256Z: P2 sent disconnect
2023-07-18T17:37:16.256Z: P2 received disconnected
2023-07-18T17:37:16.256Z: [participant_disconnected] for P2 
2023-07-18T17:37:16.258Z: [participant_removed]
2023-07-18T17:37:16.266Z: [group_billing_event] for P2 with bytes sent 9290214, bytes received 47675893, recording time in secs 100
2023-07-18T17:42:26.733Z: [delete_labeled_room]
2023-07-18T17:43:27.241Z: [group_media_client_closed]
2023-07-18T18:14:26.933Z: [room_removed]
```


No errors found for RMae6f2fb5e196f2b99678974c2734515f

No downsampling for Room sid: RMae6f2fb5e196f2b99678974c2734515f.

No rtt found for Room sid: RMae6f2fb5e196f2b99678974c2734515f. Missing insights

No send/receive bandwidth found for Room sid: RMae6f2fb5e196f2b99678974c2734515f. (Group Room only)

No track information published to insights by the SDKs in RMae6f2fb5e196f2b99678974c2734515f

No local tracks were lost for Room sid: RMae6f2fb5e196f2b99678974c2734515f

No remote tracks were lost for Room sid: RMae6f2fb5e196f2b99678974c2734515f


# Media-Recordings bot Outputs

##Output: Help

Hello, this is the Media Recordings bot and I can offer the following things!
        1. Compositions insights: type ```compositions -h``` for more info
        2. Recordings metadata: type ```recordings -h``` for more info
        3. Billing audit: type ```billing -h``` for more info
 Hope you enjoy the ride, and don't forget that I am case sensitive! :smiley:
 
 
 ##Output: compositions --account-sid ACfecd5668dfccc1bcb13195a261f5a305

```
   -----------------------------------------------------
   | Compositions for ACfecd5668dfccc1bcb13195a261f5a305 |
    -----------------------------------------------------
   | CJ4efffabb3c09cde307d4f9f38dcb9025                  |
   | CJ9f0528c788506bb190142004dcd56969                  |
   | CJ481da800957d75dce05c8eda385934aa                  |
   | CJ719ff3defd4986675ab5c1fda466e1f9                  |
   | CJ88b152e7c2dd59e72741a487e024069f                  |
    -----------------------------------------------------
```
        
 ##Output: compositions --account-sid ACfecd5668dfccc1bcb13195a261f5a305 --room-sid RMae6f2fb5e196f2b99678974c2734515f
     
```
 ----------------------------------------------------------
| Compositions for room RMae6f2fb5e196f2b99678974c2734515f |
 ----------------------------------------------------------
| CJ4efffabb3c09cde307d4f9f38dcb9025                       |
| CJ9f0528c788506bb190142004dcd56969                       |
 ----------------------------------------------------------
 ```


 ##Output: recordings --account-sid ACfecd5668dfccc1bcb13195a261f5a305 --room-sid RMae6f2fb5e196f2b99678974c2734515f



Media-Recordings bot
APP 
Recordings metadata report
         ```
    ---------------------------------------------------------------
   | Metadata of RT498b6d52c1e27d4d23f0b872f36ee72a                |
    ---------------------------------------------------------------
   | AccountSid               | ACfecd5668dfccc1bcb13195a261f5a305 |
   | Codec                    | vp8                                |
   | ContainerFormat          | mkv                                |
   | DateCreated              | 2023-07-18T17:36:06.475Z           |
   | DateDeleted              | -                                  |
   | DateUpdated              | 2023-07-18T17:37:14.524Z           |
   | Duration                 | 68                                 |
   | ParticipantSid           | PA72336d73c51accd4aebfb6fd6e8e3fe5 |
   | RoomSid                  | RMae6f2fb5e196f2b99678974c2734515f |
   | HostedByTwilio           | True                               |
   | MediaExternalLocation    | -                                  |
   | MediaRegion              | us1                                |
   | Offset                   | 246951210780                       |
   | Sid                      | RT498b6d52c1e27d4d23f0b872f36ee72a |
   | Size                     | 21086514                           |
   | SourceSid                | MT687afde64d5d654ca8942bf29c840b6f |
   | Status                   | completed                          |
   | Type                     | video                              |
   | RoomType                 | group                              |
   | InternalBillForBandwidth | false                              |
   | Encrypted                | No                                 |
    ---------------------------------------------------------------
    ---------------------------------------------------------------
   | Metadata of RT4ca8e924919502a5b6abadea0b6e293a                |
    ---------------------------------------------------------------
   | AccountSid               | ACfecd5668dfccc1bcb13195a261f5a305 |
   | Codec                    | vp8                                |
   | ContainerFormat          | mkv                                |
   | DateCreated              | 2023-07-18T17:36:06.147Z           |
   | DateDeleted              | -                                  |
   | DateUpdated              | 2023-07-18T17:37:16.598Z           |
   | Duration                 | 71                                 |
   | ParticipantSid           | PA3622d6cf641ded9cbfc434ade076652b |
   | RoomSid                  | RMae6f2fb5e196f2b99678974c2734515f |
   | HostedByTwilio           | True                               |
   | MediaExternalLocation    | -                                  |
   | MediaRegion              | us1                                |
   | Offset                   | 246951210780                       |
   | Sid                      | RT4ca8e924919502a5b6abadea0b6e293a |
   | Size                     | 21961345                           |
   | SourceSid                | MTed8b9ba7cbb31e0e95307a8f82e08e18 |
   | Status                   | completed                          |
   | Type                     | video                              |
   | RoomType                 | group                              |
   | InternalBillForBandwidth | false                              |
   | Encrypted                | No                                 |
    ---------------------------------------------------------------
    ---------------------------------------------------------------
   | Metadata of RT1f797890596f285396bd02deeda8497a                |
    ---------------------------------------------------------------
   | AccountSid               | ACfecd5668dfccc1bcb13195a261f5a305 |
   | Codec                    | opus                               |
   | ContainerFormat          | mka                                |
   | DateCreated              | 2023-07-18T17:36:06.131Z           |
   | DateDeleted              | -                                  |
   | DateUpdated              | 2023-07-18T17:37:16.453Z           |
   | Duration                 | 70                                 |
   | ParticipantSid           | PA3622d6cf641ded9cbfc434ade076652b |
   | RoomSid                  | RMae6f2fb5e196f2b99678974c2734515f |
   | HostedByTwilio           | True                               |
   | MediaExternalLocation    | -                                  |
   | MediaRegion              | us1                                |
   | Offset                   | 246951210780                       |
   | Sid                      | RT1f797890596f285396bd02deeda8497a |
   | Size                     | 153408                             |
   | SourceSid                | MTad6e48d68b2805f218ddf610684db65b |
   | Status                   | completed                          |
   | Type                     | audio                              |
   | RoomType                 | group                              |
   | InternalBillForBandwidth | false                              |
   | Encrypted                | No                                 |
    ---------------------------------------------------------------
    ---------------------------------------------------------------
   | Metadata of RTada52a0bb4093bb256c066177b7bf255                |
    ---------------------------------------------------------------
   | AccountSid               | ACfecd5668dfccc1bcb13195a261f5a305 |
   | Codec                    | opus                               |
   | ContainerFormat          | mka                                |
   | DateCreated              | 2023-07-18T17:36:05.919Z           |
   | DateDeleted              | -                                  |
   | DateUpdated              | 2023-07-18T17:37:14.452Z           |
   | Duration                 | 46                                 |
   | ParticipantSid           | PA72336d73c51accd4aebfb6fd6e8e3fe5 |
   | RoomSid                  | RMae6f2fb5e196f2b99678974c2734515f |
   | HostedByTwilio           | True                               |
   | MediaExternalLocation    | -                                  |
   | MediaRegion              | us1                                |
   | Offset                   | 246951210780                       |
   | Sid                      | RTada52a0bb4093bb256c066177b7bf255 |
   | Size                     | 142564                             |
   | SourceSid                | MTfdb17797396c2e85bdfb36d73cb302db |
   | Status                   | completed                          |
   | Type                     | audio                              |
   | RoomType                 | group                              |
   | InternalBillForBandwidth | false                              |
   | Encrypted                | No                                 |
    ---------------------------------------------------------------
    ---------------------------------------------------------------
   | Metadata of RTc8f09c6f2183770e306c2c25093fe509                |
    ---------------------------------------------------------------
   | AccountSid               | ACfecd5668dfccc1bcb13195a261f5a305 |
   | Codec                    | opus                               |
   | ContainerFormat          | mka                                |
   | DateCreated              | 2023-07-18T17:35:53.263Z           |
   | DateDeleted              | -                                  |
   | DateUpdated              | 2023-07-18T17:35:59.096Z           |
   | Duration                 | 6                                  |
   | ParticipantSid           | PA72336d73c51accd4aebfb6fd6e8e3fe5 |
   | RoomSid                  | RMae6f2fb5e196f2b99678974c2734515f |
   | HostedByTwilio           | True                               |
   | MediaExternalLocation    | -                                  |
   | MediaRegion              | us1                                |
   | Offset                   | 246951210780                       |
   | Sid                      | RTc8f09c6f2183770e306c2c25093fe509 |
   | Size                     | 9903                               |
   | SourceSid                | MTfdb17797396c2e85bdfb36d73cb302db |
   | Status                   | completed                          |
   | Type                     | audio                              |
   | RoomType                 | group                              |
   | InternalBillForBandwidth | false                              |
   | Encrypted                | No                                 |
    ---------------------------------------------------------------
    ---------------------------------------------------------------
   | Metadata of RTc86fc7bc876369fff4dc87c2801929f2                |
    ---------------------------------------------------------------
   | AccountSid               | ACfecd5668dfccc1bcb13195a261f5a305 |
   | Codec                    | vp8                                |
   | ContainerFormat          | mkv                                |
   | DateCreated              | 2023-07-18T17:35:53.259Z           |
   | DateDeleted              | -                                  |
   | DateUpdated              | 2023-07-18T17:35:59.162Z           |
   | Duration                 | 6                                  |
   | ParticipantSid           | PA3622d6cf641ded9cbfc434ade076652b |
   | RoomSid                  | RMae6f2fb5e196f2b99678974c2734515f |
   | HostedByTwilio           | True                               |
   | MediaExternalLocation    | -                                  |
   | MediaRegion              | us1                                |
   | Offset                   | 246951210780                       |
   | Sid                      | RTc86fc7bc876369fff4dc87c2801929f2 |
   | Size                     | 1800642                            |
   | SourceSid                | MTed8b9ba7cbb31e0e95307a8f82e08e18 |
   | Status                   | completed                          |
   | Type                     | video                              |
   | RoomType                 | group                              |
   | InternalBillForBandwidth | false                              |
   | Encrypted                | No                                 |
    ---------------------------------------------------------------
    ---------------------------------------------------------------
   | Metadata of RTc17c1f1da5822b2c9f9247a66b8b2ab8                |
    ---------------------------------------------------------------
   | AccountSid               | ACfecd5668dfccc1bcb13195a261f5a305 |
   | Codec                    | vp8                                |
   | ContainerFormat          | mkv                                |
   | DateCreated              | 2023-07-18T17:35:53.227Z           |
   | DateDeleted              | -                                  |
   | DateUpdated              | 2023-07-18T17:35:59.252Z           |
   | Duration                 | 6                                  |
   | ParticipantSid           | PA72336d73c51accd4aebfb6fd6e8e3fe5 |
   | RoomSid                  | RMae6f2fb5e196f2b99678974c2734515f |
   | HostedByTwilio           | True                               |
   | MediaExternalLocation    | -                                  |
   | MediaRegion              | us1                                |
   | Offset                   | 246951210780                       |
   | Sid                      | RTc17c1f1da5822b2c9f9247a66b8b2ab8 |
   | Size                     | 1814756                            |
   | SourceSid                | MT687afde64d5d654ca8942bf29c840b6f |
   | Status                   | completed                          |
   | Type                     | video                              |
   | RoomType                 | group                              |
   | InternalBillForBandwidth | false                              |
   | Encrypted                | No                                 |
    ---------------------------------------------------------------
    ---------------------------------------------------------------
   | Metadata of RT24131d95c1158ed00008990778ee69d9                |
    ---------------------------------------------------------------
   | AccountSid               | ACfecd5668dfccc1bcb13195a261f5a305 |
   | Codec                    | opus                               |
   | ContainerFormat          | mka                                |
   | DateCreated              | 2023-07-18T17:35:53.103Z           |
   | DateDeleted              | -                                  |
   | DateUpdated              | 2023-07-18T17:35:59.059Z           |
   | Duration                 | 6                                  |
   | ParticipantSid           | PA3622d6cf641ded9cbfc434ade076652b |
   | RoomSid                  | RMae6f2fb5e196f2b99678974c2734515f |
   | HostedByTwilio           | True                               |
   | MediaExternalLocation    | -                                  |
   | MediaRegion              | us1                                |
   | Offset                   | 246951210780                       |
   | Sid                      | RT24131d95c1158ed00008990778ee69d9 |
   | Size                     | 24571                              |
   | SourceSid                | MTad6e48d68b2805f218ddf610684db65b |
   | Status                   | completed                          |
   | Type                     | audio                              |
   | RoomType                 | group                              |
   | InternalBillForBandwidth | false                              |
   | Encrypted                | No                                 |
    ---------------------------------------------------------------
    ---------------------------------------------------------------
   | Metadata of RTd4189147a980919990f085b7c51ea41a                |
    ---------------------------------------------------------------
   | AccountSid               | ACfecd5668dfccc1bcb13195a261f5a305 |
   | Codec                    | opus                               |
   | ContainerFormat          | mka                                |
   | DateCreated              | 2023-07-18T17:35:12.294Z           |
   | DateDeleted              | -                                  |
   | DateUpdated              | 2023-07-18T17:35:34.736Z           |
   | Duration                 | 23                                 |
   | ParticipantSid           | PA3622d6cf641ded9cbfc434ade076652b |
   | RoomSid                  | RMae6f2fb5e196f2b99678974c2734515f |
   | HostedByTwilio           | True                               |
   | MediaExternalLocation    | -                                  |
   | MediaRegion              | us1                                |
   | Offset                   | 246951210780                       |
   | Sid                      | RTd4189147a980919990f085b7c51ea41a |
   | Size                     | 15793                              |
   | SourceSid                | MTad6e48d68b2805f218ddf610684db65b |
   | Status                   | completed                          |
   | Type                     | audio                              |
   | RoomType                 | group                              |
   | InternalBillForBandwidth | false                              |
   | Encrypted                | No                                 |
    ---------------------------------------------------------------
    ---------------------------------------------------------------
   | Metadata of RT2534a09136b2b29ea3ad0c6de8887d8e                |
    ---------------------------------------------------------------
   | AccountSid               | ACfecd5668dfccc1bcb13195a261f5a305 |
   | Codec                    | vp8                                |
   | ContainerFormat          | mkv                                |
   | DateCreated              | 2023-07-18T17:35:12.254Z           |
   | DateDeleted              | -                                  |
   | DateUpdated              | 2023-07-18T17:35:34.830Z           |
   | Duration                 | 23                                 |
   | ParticipantSid           | PA3622d6cf641ded9cbfc434ade076652b |
   | RoomSid                  | RMae6f2fb5e196f2b99678974c2734515f |
   | HostedByTwilio           | True                               |
   | MediaExternalLocation    | -                                  |
   | MediaRegion              | us1                                |
   | Offset                   | 246951210780                       |
   | Sid                      | RT2534a09136b2b29ea3ad0c6de8887d8e |
   | Size                     | 4672572                            |
   | SourceSid                | MTed8b9ba7cbb31e0e95307a8f82e08e18 |
   | Status                   | completed                          |
   | Type                     | video                              |
   | RoomType                 | group                              |
   | InternalBillForBandwidth | false                              |
   | Encrypted                | No                                 |
    ---------------------------------------------------------------
    ---------------------------------------------------------------
   | Metadata of RT63f097f6c5f6b0db498d50d361b14d76                |
    ---------------------------------------------------------------
   | AccountSid               | ACfecd5668dfccc1bcb13195a261f5a305 |
   | Codec                    | opus                               |
   | ContainerFormat          | mka                                |
   | DateCreated              | 2023-07-18T17:33:31.862Z           |
   | DateDeleted              | -                                  |
   | DateUpdated              | 2023-07-18T17:35:34.792Z           |
   | Duration                 | 123                                |
   | ParticipantSid           | PA72336d73c51accd4aebfb6fd6e8e3fe5 |
   | RoomSid                  | RMae6f2fb5e196f2b99678974c2734515f |
   | HostedByTwilio           | True                               |
   | MediaExternalLocation    | -                                  |
   | MediaRegion              | us1                                |
   | Offset                   | 246951210780                       |
   | Sid                      | RT63f097f6c5f6b0db498d50d361b14d76 |
   | Size                     | 71455                              |
   | SourceSid                | MTfdb17797396c2e85bdfb36d73cb302db |
   | Status                   | completed                          |
   | Type                     | audio                              |
   | RoomType                 | group                              |
   | InternalBillForBandwidth | false                              |
   | Encrypted                | No                                 |
    ---------------------------------------------------------------
    ---------------------------------------------------------------
   | Metadata of RT568a6c9b96493706a5845e7459efc979                |
    ---------------------------------------------------------------
   | AccountSid               | ACfecd5668dfccc1bcb13195a261f5a305 |
   | Codec                    | vp8                                |
   | ContainerFormat          | mkv                                |
   | DateCreated              | 2023-07-18T17:33:31.862Z           |
   | DateDeleted              | -                                  |
   | DateUpdated              | 2023-07-18T17:35:35.755Z           |
   | Duration                 | 123                                |
   | ParticipantSid           | PA72336d73c51accd4aebfb6fd6e8e3fe5 |
   | RoomSid                  | RMae6f2fb5e196f2b99678974c2734515f |
   | HostedByTwilio           | True                               |
   | MediaExternalLocation    | -                                  |
   | MediaRegion              | us1                                |
   | Offset                   | 246951210780                       |
   | Sid                      | RT568a6c9b96493706a5845e7459efc979 |
   | Size                     | 36564639                           |
   | SourceSid                | MT687afde64d5d654ca8942bf29c840b6f |
   | Status                   | completed                          |
   | Type                     | video                              |
   | RoomType                 | group                              |
   | InternalBillForBandwidth | false                              |
   | Encrypted                | No                                 |
    ---------------------------------------------------------------
        ```
