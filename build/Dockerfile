FROM alpine:latest
COPY ./frp_0.31.2_linux_arm.tar.gz /frp.tar.gz
RUN tar -xzvf /frp.tar.gz
RUN mv /frp_0.31.2_linux_arm /frp
WORKDIR /frp
RUN rm -rf frps.ini && rm -rf frpc.ini