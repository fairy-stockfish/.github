[Fairy-Stockfish](https://github.com/ianfab/Fairy-Stockfish) is a chess variant engine by [Fabian Fichter](https://github.com/ianfab) derived from [Stockfish](https://github.com/official-stockfish/Stockfish) supporting various regional, historical, and modern chess variants as well as games with user-defined rules. Besides the core engine the project is accompanied by several repositories for development, testing, and integration. This landscape of Fairy-Stockfish projects is summarized below. See the [project website](https://fairy-stockfish.github.io) for more information.

### Core
* Fairy-Stockfish: https://github.com/ianfab/Fairy-Stockfish
* Fairy-Stockfish website: https://github.com/fairy-stockfish/fairy-stockfish.github.io ([website](https://fairy-stockfish.github.io/))
* Documentation of chess variant standards: https://github.com/fairy-stockfish/chess-variant-standards ([website](https://fairy-stockfish.github.io/chess-variant-standards/))

### Websites and user interfaces
* Fairy-Stockfish playground in the browser: https://github.com/ianfab/fairyground ([website](https://fairyground.vercel.app/))
* Fairy-Stockfish WASM demo: https://github.com/ianfab/fairy-stockfish-nnue-wasm-demo ([website](https://fairy-stockfish-nnue-wasm.vercel.app/))
* Opening book generator in the browser: https://github.com/ianfab/bookgen-wasm ([website](https://bookgen-wasm.vercel.app/))
* Minimalistic offline Fairy-Stockfish GUI: https://github.com/fairy-stockfish/FairyFishGUI

### Bindings and ports
* python binding: https://github.com/ianfab/Fairy-Stockfish#python ([pypi](https://pypi.org/project/pyffish))
* javascript binding: https://github.com/ianfab/Fairy-Stockfish#javascript ([npm](https://www.npmjs.com/package/ffish))
* WASM port: https://github.com/fairy-stockfish/fairy-stockfish.wasm ([npm](https://www.npmjs.com/package/fairy-stockfish-nnue.wasm))

### NNUE
* Releases with built-in NNUE: https://github.com/fairy-stockfish/Fairy-Stockfish-NNUE
* Variant NNUE training: https://github.com/fairy-stockfish/variant-nnue-pytorch
* Training data generator: https://github.com/fairy-stockfish/variant-nnue-tools

### Testing
* Distributed testing: https://github.com/ianfab/fishtest ([website](http://www.variantfishtest.org:6543/tests))
* Variant-agnostic local testing: https://github.com/ianfab/variantfishtest
* Testing for bughouse based on pyffish: https://github.com/ianfab/fairyfishtest
* Local tuning: https://github.com/ianfab/spsa

### Utilities for testing and development
* Opening book generator: https://github.com/fairy-stockfish/bookgen
* Opening books: https://github.com/ianfab/books
* Cutechess binaries for fishtest: https://github.com/ianfab/FishCooking
* Helper script for code modification: https://github.com/ianfab/fishutils
