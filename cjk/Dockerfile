FROM debian

RUN apt-get -y update && \
    apt-get -y dist-upgrade && \
	apt-get -y install openjdk-11-jre-headless && \
	apt-get -y install --no-install-recommends chromium chromium-driver chromium-l10n fonts-noto-cjk && \
	rm -rf /var/lib/apt/lists/*
