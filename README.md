# 🦀 Rust RP2040-Zero Template 📟
 Author: marcell.janovszki@gmail.com
#### A template project to base rp2040-zero projects off of.


## Features
- #### Mounts the usb into WSL if the host OS is Windows.

## 📦Pre-requisits
### 💻 OS:
- ### 🪟 Windows + 🐧 WSL
    ---

    1. Install the required target:

        $ `rustup target add thumbv6m-none-eabi`

        <br/>

    2. Install `elf2uf2-rs` to flash your RP2040-Zero

        $ `cargo install elf2uf2-rs`
- ### 🐧 Linux
    1. Update `.cargo/config.toml` with 
    
        `runner = "elf2uf2-rs -d"`

## 🏃‍♂️Run /⚡Flash instructions:
`cargo run --release`