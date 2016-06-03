FROM kalilinux/kali-linux-docker 
RUN echo deb http://mirrors.ustc.edu.cn/kali kali-rolling main non-free contrib > /etc/apt/sources.list \
        && apt-get update \
        && apt-get install -y metasploit-framework \
        && rm -rf /var/lib/apt/lists/*
