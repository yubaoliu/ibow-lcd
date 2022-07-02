# FROM  yubao/ubuntu16:cuda11.3.0
FROM  yubao/ubuntu18:cuda11.3.0
MAINTAINER yubao.liu.ra@tut.jp

WORKDIR /root/catkin_ws

RUN cd ~/catkin_ws/src \
    # && git clone https://github.91chi.fun/https://github.com/emiliofidalgo/obindex2.git \
    && git clone https://github.com/emiliofidalgo/obindex2.git 

# RUN apt update --no-install-recommends \
# 	&& apt install -y libceres-dev -f

# setup entrypoint
# COPY entrypoint.sh /root/entrypoint.sh
# RUN chmod 755 /root/entrypoint.sh
# ENTRYPOINT ["/root/entrypoint.sh"]

CMD ["bash"]
