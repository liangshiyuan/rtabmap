# Image: introlab3it/rtabmap:tango

FROM introlab3it/rtabmap:android-deps

WORKDIR /root/

ADD build.bash /root/build.bash
RUN chmod +x build.bash
RUN /bin/bash -c "./build.bash"

WORKDIR /root/rtabmap-tango/build/app/android/bin
