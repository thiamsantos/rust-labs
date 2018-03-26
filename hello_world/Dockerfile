FROM rust:1.24

WORKDIR /usr/src/myapp
COPY . .
RUN rustc main.rs
CMD ["./main"]