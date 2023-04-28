# muledump-render

Parses all ROTMG asset files and generates the corresponding Muledump Renders scripts (`constants.js`, `renders.png`, and `sheets.js`).

## Setup

1. Pipfile calls for Python 3.9; however, later versions are also usable if you update this configuration setting.
1. VisualStudio Tools with Python and Desktop Development with C++

## Usage

### Basic Runtime Command Example

```pipenv run python render.py --dest /path/to/output```

Generates output files using default `--source` value and no game version data

### Full Runtime Command Example

```pipenv run python render.py --dest /path/to/output --source /path/to/rotmg-assets --game-version 3.3.7.0.0 --buildhash 4760f3b39eaedba595a78f74d05908a6```

Generates output files using the specified source and game version data

### Runtime Arguments

Supports the following runtime arguments: 

--dest <path> (required)  
The destination path for program output

--source <path>  
The source path or remote URL for ROTMG assets (default: https://assets.muledump.com)

--game-version <string>  
The version number of the game files

--buildhash <string>  
The build hash of the game files

## Support

Jakcodex operates its own Discord server at https://discord.gg/JFS5fqW.

Feel free to join and ask for help getting setup, hear about new updates, offer your suggestions and feedback, or just say hi. We love to hear from the community!

If you encounter a bug, have a feature request, or have any other feedback you can also check out the [issue tracker](https://github.com/jakcodex/muledump/issues) to see if it's already being discussed. If not then you can [submit a new issue](https://github.com/jakcodex/muledump/issues/new).

## Jakcodex License

Copyright 2023 [Jakcodex](https://github.com/jakcodex)

Redistribution and use in source and binary forms, with or without modification, are permitted provided that the following conditions are met:

1. Redistributions of source code must retain the above copyright notice, this list of conditions and the following disclaimer.

2. Redistributions in binary form must reproduce the above copyright notice, this list of conditions and the following disclaimer in the documentation and/or other materials provided with the distribution.

3. Neither the name of the copyright holder nor the names of its contributors may be used to endorse or promote products derived from this software without specific prior written permission.

THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS" AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT HOLDER OR CONTRIBUTORS BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.

