[Fairy-Stockfish](https://github.com/fairy-stockfish/Fairy-Stockfish) is a chess variant engine by [Fabian Fichter](https://github.com/ianfab) derived from [Stockfish](https://github.com/official-stockfish/Stockfish) supporting various regional, historical, and modern chess variants as well as games with user-defined rules. Besides the core engine the project is accompanied by several repositories for development, testing, and integration. This landscape of Fairy-Stockfish projects is summarized below. See the [project website](https://fairy-stockfish.github.io) for more information.

### Core
* Fairy-Stockfish: [fairy-stockfish/Fairy-Stockfish](https://github.com/fairy-stockfish/Fairy-Stockfish)
* Fairy-Stockfish website: [fairy-stockfish/fairy-stockfish.github.io](https://github.com/fairy-stockfish/fairy-stockfish.github.io) ([website](https://fairy-stockfish.github.io/))
* Documentation of chess variant standards: [fairy-stockfish/chess-variant-standards](https://github.com/fairy-stockfish/chess-variant-standards) ([website](https://fairy-stockfish.github.io/chess-variant-standards/))

### Websites and user interfaces
* Fairy-Stockfish playground in the browser: [ianfab/fairyground](https://github.com/ianfab/fairyground) ([website](https://fairyground.vercel.app/))
* Fairy-Stockfish WASM demo: [ianfab/fairy-stockfish-nnue-wasm-demo](https://github.com/ianfab/fairy-stockfish-nnue-wasm-demo) ([website](https://fairy-stockfish-nnue-wasm.vercel.app/))
* Opening book generator in the browser: [ianfab/bookgen-wasm](https://github.com/ianfab/bookgen-wasm) ([website](https://bookgen-wasm.vercel.app/))
* Minimalistic offline Fairy-Stockfish GUI: [fairy-stockfish/FairyFishGUI](https://github.com/fairy-stockfish/FairyFishGUI) (deprecated)

### Bindings and ports
* python binding: [fairy-stockfish/Fairy-Stockfish](https://github.com/fairy-stockfish/Fairy-Stockfish#python) ([pypi](https://pypi.org/project/pyffish))
* javascript binding: [fairy-stockfish/Fairy-Stockfish](https://github.com/fairy-stockfish/Fairy-Stockfish#javascript) ([npm](https://www.npmjs.com/package/ffish))
* WASM port: [fairy-stockfish/fairy-stockfish.wasm](https://github.com/fairy-stockfish/fairy-stockfish.wasm) ([npm](https://www.npmjs.com/package/fairy-stockfish-nnue.wasm))

### NNUE
* Releases with built-in NNUE: [fairy-stockfish/Fairy-Stockfish-NNUE](https://github.com/fairy-stockfish/Fairy-Stockfish-NNUE)
* Variant NNUE training: [fairy-stockfish/variant-nnue-pytorch](https://github.com/fairy-stockfish/variant-nnue-pytorch)
* Training data generator: [fairy-stockfish/variant-nnue-tools](https://github.com/fairy-stockfish/variant-nnue-tools)

### Testing
* Distributed testing: [ianfab/fishtest](https://github.com/ianfab/fishtest)
* Variant-agnostic local testing: [ianfab/variantfishtest](https://github.com/ianfab/variantfishtest)
* Testing for bughouse based on pyffish: [fairy-stockfish/fairyfishtest](https://github.com/fairy-stockfish/fairyfishtest)
* Local tuning: [ianfab/spsa](https://github.com/ianfab/spsa)

### Utilities for testing and development
* Opening book generator: [fairy-stockfish/bookgen](https://github.com/fairy-stockfish/bookgen)
* Opening books: [ianfab/books](https://github.com/ianfab/books)
* Cutechess binaries for fishtest: [ianfab/FishCooking](https://github.com/ianfab/FishCooking)
* Helper script for code modification: [ianfab/fishutils](https://github.com/ianfab/fishutils)
