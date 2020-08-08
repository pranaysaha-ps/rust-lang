FROM rust:alpine3.12
LABEL Name=hello-rust Version=1.0.0 maintainer="saha.pranay25@gmail.com"
WORKDIR /usr/src/app
COPY . .
RUN cargo install --path .
EXPOSE 3000
CMD [ "cargo run" ]