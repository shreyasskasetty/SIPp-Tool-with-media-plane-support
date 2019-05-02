SIPP tool has been enhanced with media plane support by incorporating RTP and RTCP channel eshtablishment after the control channel is eshtablished between the end ponts.
The command to run SIPP as a server with this media plane support is      "./sipp -sn uas -rtpsetup" 
The command to run SIPP as a client with this media plane support is        "./sipp -sn uac [ip address of the server] -rtpsetup"

 
To eshtablish multiple parallel calls 				    "./sipp -sn uas -rtpsetup -m [number of calls]"
						    "./sipp -sn uac [ip address of the server] -rtpsetup -m [number of calls]"

The server and client act as the two end points of the parallel call.
