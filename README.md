# Plasma MVP Implementation in Vyper
This is an experimental implementation of [Minimal Viable Plasma](https://ethresear.ch/t/minimal-viable-plasma/426) in Vyper.
In [our blog post](https://medium.com/@ryuyanakamura/plasma-mvp-implementation-in-vyper-5a3850e5b1b) we explained the motivation and experience of this project.

## Contributing
We welcome any contribution. Please open issue about bugs or proposals. You are welcome to make pull requests.

### Getting Started
Fork this repository and install dependencies with: `npm install`.
You also need to install Vyper. See the [Vyper's docs](https://vyper.readthedocs.io/en/latest/installing-vyper.html).

### Testing
`npm run test`
This execute Truffle's tests. Tests are found in `tests/` directory.

### Building
`npm run build`
Build process is handled by [truper](https://www.npmjs.com/package/truper) and it creates truffle compatible artifacts in `build/contracts` directory.

## Acknowledgements
`root_chain` and `priority_queue` contracts are based on [OmiseGo's MVP implementation](https://github.com/omisego/plasma-mvp). 
We really appreciate them for their work!