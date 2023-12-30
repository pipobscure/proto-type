# Protocol Type Generator

## Usage

Simply run `npx @pipobscure/proto-type <protocol.json>` in the folder you wish your `.d.ts` files to be generated. `<protocol.json>` is the filename of one or more protocol definition files.

## License

This is a clear rip-off from [Chrome Devtools Protocol](https://github.com/ChromeDevTools/devtools-protocol/tree/master/scripts) as written by Paul Irish. The only real modification is to make it usable more generally for generating types from protocol-definitions outside of Chrome-Devtools.

Since the original was licensed under specific [terms](https://chromium.googlesource.com/chromium/src/+/main/LICENSE) in order to comply it should be clear that the original was copyrighted by "The Chromium Authors". It should be understood that neither Google or any of "The CHromium Authors" are endorsing this in any way and they have made no statements regarding this. 

The full text of the original license is:

> Copyright 2015 The Chromium Authors
>
> Redistribution and use in source and binary forms, with or without
> modification, are permitted provided that the following conditions are
> met:
>
>    * Redistributions of source code must retain the above copyright
> notice, this list of conditions and the following disclaimer.
>    * Redistributions in binary form must reproduce the above
> copyright notice, this list of conditions and the following disclaimer
> in the documentation and/or other materials provided with the
> distribution.
>    * Neither the name of Google LLC nor the names of its
> contributors may be used to endorse or promote products derived from
> this software without specific prior written permission.
>
> THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS
> "AS IS" AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT
> LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR
> A PARTICULAR PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT
> OWNER OR CONTRIBUTORS BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL,
> SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT
> LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE,
> DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY
> THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT
> (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE
> OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.

I believe to have fully complied with that license. Relicense any modifications to the original under identical terms.
