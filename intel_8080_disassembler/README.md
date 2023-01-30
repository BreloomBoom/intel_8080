# Intel 8080 Disassembler

Translates hex files into assembly language source for Intel 8080.

# How to Use

Place the ROM you want into the ```roms``` folder.

With your terminal in the ```intel_8080_disassembler``` directory, run the command
```
cargo run > output
```
then type in the name of your ROM.

This will put the assembly into a file called ```output```.