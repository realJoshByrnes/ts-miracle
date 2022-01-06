ts-miracle - a Typescript Sega Master System emulator
--------------------------------------------------

ts-miracle is a fork of the Javascript based [Miracle by Matt Godbolt](https://github.com/mattgodbolt/Miracle).

**Goals of TS-Miracle:**
* Make emulation possible on limited devices such as the PS5
* Add typings to the entire Javascript codebase.
* Modernize the code. Miracle was written some time ago and features a lot of deprecated code.

**As per the original Miracle README.md:**

Requires `make`, `perl` and `python` to build.  Place ROMs in the `roms` directory as
`romname.sms` and then run `make` to build the emulation script files and the ROM data.

z80 emulation and test are based on rev 1071 of http://svn.matt.west.co.tt/svn/jsspec/trunk

Miracle can be taken for a spin at http://xania.org/miracle/miracle.html
