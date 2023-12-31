
# Image to ASCII Rust

This is a Rust program that converts an image into ASCII art.

![alt text](https://github.com/iamvasanth07/img-to-ascii-rust/blob/8d7cb8098b6e60f6ce08591c055ea82e942399c8/images/RustASCII.jpg)

## Prerequisites

- Rust (https://www.rust-lang.org/tools/install)
- OpenCV (https://opencv.org/releases/)

## Usage

1. Clone the repository:

    ```shell
    git clone https://github.com/iamvasanth07/img-to-ascii-rust.git
    ```

2. Navigate to the project directory:

    ```shell
    cd img-to-ascii-rust
    ```

3. Build the project:

    ```shell
    cargo build --release
    ```

4. Run the program with an image file as an argument:

    ```shell
    cargo run --release -- <image>
    ```

    Replace `<image>` with the path to your image file.

5. The ASCII art will be saved to a text file with the same name as the image file, but with a `.txt` extension.

## Example

Suppose you have an image named 'example.jpg'. To convert it into ASCII art, you would run:
```shell
cargo run --release -- example.jpg
```
