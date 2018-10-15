## Why Hello?
Its 2018, WebRTC is natively supported in all desktop & mobile browsers but still most major players (Hangouts, skype, Appear.in etc) ask you to download app to use their service. 

## Hello
Hello is a video chat app that works in most major desktop & mobile browsers. No Signup. No Downloads. Just video chat. 

Hello use a WeBRTC for video communication and a socket.io server that serves as a signaling server. It uses WebRTC mesh when more people is added to the user, it means each video stream in a group call is a separate P2P connection. There is no hard limit on the no. of people in the group video call, but the quality of the call will decrease when more than 5 people join the call.

### Credits:
[https://github.com/anoek/webrtc-group-chat-example](https://github.com/anoek/webrtc-group-chat-example)

------------------
If you are here for checking the p2p video call w/o signaling server, head over to the `gh-pages` branch. And check out the demo here [https://vasanthv.github.io/hello/](https://vasanthv.github.io/hello/).
