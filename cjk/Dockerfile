FROM debian

RUN apt-get -y update && \
    apt-get -y dist-upgrade && \
	apt-get -y install openjdk-11-jre-headless && \
	apt-get -y install --no-install-recommends chromium chromium-driver chromium-l10n locales fonts-noto-cjk && \
	rm -rf /var/lib/apt/lists/* && \
	sed -i '/UTF-8/s/# \(zh\|ja\|ko\|en_US\)_/\1_/' /etc/locale.gen && \
	locale-gen
