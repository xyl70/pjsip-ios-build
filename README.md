#pjsip-ios-build
Easily build PJSIP with: OpenH264, Opus and G.729 for ios.

## Support - PJSIP 2.6+
--Mac 10.13+
--nasm:2.11.06
--OpenH264:1.6.0

#### Prepare Environment
1. Execute `./prepare-build-system`
2. If everything goes well you should see all the compiled libraries openh264 in the <b>output</b> folder.

## Build PJSIP
execute `./build` is going to create a new folder inside the output named <b>pjsip-build</b>
or execute `./build_no_video` is going to create a new folder inside the output named <b>pjsip-build-on-video</b> 

## Merge static libraries
execute `./lipoFile_h264` is going to create a new folder inside the output named <b>merge</b> on `openh264-build-output/libs`
execute `./lipoFile` is going to create a new new folder inside the output named <b>merge</b> on `pjsip-build/libs`
