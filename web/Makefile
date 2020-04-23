build:
	mkdir build || true
	cp -r ../../jitsi-meet/interface_config.js rootfs/defaults/
	cp -r ../../jitsi-meet/base.html build/
	cp -r ../../jitsi-meet/body.html build/
	cp -r ../../jitsi-meet/connection_optimization build/
	cp -r ../../jitsi-meet/css build/
	cp -r ../../jitsi-meet/favicon.ico build/
	cp -r ../../jitsi-meet/fonts build/
	cp -r ../../jitsi-meet/head.html build/
	cp -r ../../jitsi-meet/images build/
	cp -r ../../jitsi-meet/index.html build/
	cp -r ../../jitsi-meet/interface_config.js build/
	cp -r ../../jitsi-meet/lang build/
	cp -r ../../jitsi-meet/libs build/
	cp -r ../../jitsi-meet/logging_config.js build/
	cp -r ../../jitsi-meet/plugin.head.html build/
	# cp -r ../../jitsi-meet/robots.txt build/
	# cp -r ../../jitsi-meet/scripts build/
	cp -r ../../jitsi-meet/sounds build/
	cp -r ../../jitsi-meet/static build/
	cp -r ../../jitsi-meet/title.html build/
	docker build $(BUILD_ARGS) -t $(JITSI_REPO)/web .

.PHONY: build
