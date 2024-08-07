<!doctype html>
<html>
    <head>
        <meta charset="utf-8" />
        <meta http-equiv="X-UA-Compatible" content="IE=edge" />
        <script src="https://aframe.io/releases/1.2.0/aframe.min.js"></script>
        <script src="https://unpkg.com/aframe-look-at-component@0.8.0/dist/aframe-look-at-component.min.js"></script>
        <script src="https://cdn.jsdelivr.net/gh/AR-js-org/AR.js@master/aframe/build/aframe-ar-nft.js"></script>
        <script src="https://cdn.jsdelivr.net/gh/aframeextras/aframe-extras@6.1.2/dist/aframe-extras.loaders.min.js"></script>
      </head>

    <body style="margin: 0; overflow: hidden;">
        <a-scene
            embedded
            loading-screen="enabled: false;"
            arjs="sourceType: webcam; debugUIEnabled: false;"
        >
            <a-assets>
                <video
                    src="assets/asset.mp4"
                    preload="auto"
                    id="vid"
                    response-type="arraybuffer"
                    loop
                    crossorigin
                    webkit-playsinline
                    autoplay
                    muted
                    playsinline
                ></video>
            </a-assets>

                <a-video
                    src="#vid"
                    position='0 0.1 0'
                    rotation="-90 0 0"
                    look-at="[gps-camera]"
                    videohandler
                    smooth="true"
                    smoothCount="10"
                    smoothTolerance="0.01"
                    smoothThreshold="5"
                    autoplay="false"
                    scale="1 1 1"
                    gps-entity-place="latitude: 13.819645606712783; longitude: 100.51526580745428;"
                ></a-video>
                <a-video
                    src="#vid"
                    position='0 0.1 0'
                    rotation="-90 0 0"
                    look-at="[gps-camera]"
                    videohandler
                    smooth="true"
                    smoothCount="10"
                    smoothTolerance="0.01"
                    smoothThreshold="5"
                    autoplay="false"
                    scale="1 1 1"
                    gps-entity-place="latitude: 13.819823116986043; longitude: 100.51532822011495;"
                ></a-video>
                <a-video
                    src="#vid"
                    position='0 0.1 0'
                    rotation="-90 0 0"
                    look-at="[gps-camera]"
                    videohandler
                    smooth="true"
                    smoothCount="10"
                    smoothTolerance="0.01"
                    smoothThreshold="5"
                    autoplay="false"
                    scale="1 1 1"
                    gps-entity-place="latitude: 13.819578234153852; longitude: 100.51504953782296;"
                ></a-video>
                <a-video
                    src="#vid"
                    position='0 0.1 0'
                    rotation="-90 0 0"
                    look-at="[gps-camera]"
                    videohandler
                    smooth="true"
                    smoothCount="10"
                    smoothTolerance="0.01"
                    smoothThreshold="5"
                    autoplay="false"
                    scale="1 1 1"
                    gps-entity-place="latitude: 13.819659388010038; longitude: 100.51480739016688;"
                ></a-video>
                <a-video
                    src="#vid"
                    position='0 0.1 0'
                    rotation="-90 0 0"
                    look-at="[gps-camera]"
                    videohandler
                    smooth="true"
                    smoothCount="10"
                    smoothTolerance="0.01"
                    smoothThreshold="5"
                    autoplay="false"
                    scale="1 1 1"
                    gps-entity-place="latitude: 13.819806650578244; longitude: 100.51540427780367;"
                ></a-video>
                <a-video
                    src="#vid"
                    position='0 0.1 0'
                    rotation="-90 0 0"
                    look-at="[gps-camera]"
                    videohandler
                    smooth="true"
                    smoothCount="10"
                    smoothTolerance="0.01"
                    smoothThreshold="5"
                    autoplay="false"
                    scale="1 1 1"
                    gps-entity-place="latitude: 13.819735079608776; longitude: 100.51537918252126;"
                ></a-video>

            <a-camera gps-camera rotation-reader></a-camera>
        </a-scene>
    </body>
</html>
