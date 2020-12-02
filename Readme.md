<div align="center">
	<br>
	<br>
	<img src="media/logo.svg" alt="type-fest" height="50">
	<br>
	<br>
	<b>A Rust CLI Program to convert hexadecimal color-code to RGB</b>
	<br>
</div>
<br>
<br>

<div>
	<img src="media/recording.gif" alt="type-fest" height="auto" width="404">
</div>
<br>

## Install

```
$ cargo install hex-rgb
```

## Usage

```sh
$ hex-rgb --help
hex-rgb 0.1.0
Converts hexadecimal color code to RGB

USAGE:
    hex-rgb [FLAGS] <hex-code>

FLAGS:
    -c, --copy       Copy RGB Color to system clipboard
    -d, --debug      Activate debug mode (-d, --debug)
    -h, --help       Prints help information
    -V, --version    Prints version information

ARGS:
    <hex-code>    A valid hexadecimal color code (Eg. "#fafafa" (or) "#fff")
```
