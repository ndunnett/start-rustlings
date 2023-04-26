FROM rust:bullseye
RUN apt update && apt install -y zsh
ADD rustlings /rustlings
WORKDIR /rustlings
RUN cargo install --force --path .
RUN rustlings lsp
