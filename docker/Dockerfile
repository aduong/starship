FROM rust
RUN apt-get update && apt-get install -y vim
RUN cargo install starship
COPY bashrc /root/.bashrc
COPY starship.toml /root/.config/starship.toml