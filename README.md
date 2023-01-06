# ipfs-interfaces <!-- omit in toc -->

[![ipfs.tech](https://img.shields.io/badge/project-IPFS-blue.svg?style=flat-square)](https://ipfs.tech)
[![Discuss](https://img.shields.io/discourse/https/discuss.ipfs.tech/posts.svg?style=flat-square)](https://discuss.ipfs.tech)
[![codecov](https://img.shields.io/codecov/c/github/ipfs/js-ipfs-interfaces.svg?style=flat-square)](https://codecov.io/gh/ipfs/js-ipfs-interfaces)
[![CI](https://img.shields.io/github/actions/workflow/status/ipfs/js-ipfs-interfaces/js-test-and-release.yml?branch=master\&style=flat-square)](https://github.com/ipfs/js-ipfs-interfaces/actions/workflows/js-test-and-release.yml?query=branch%3Amaster)

> TypeScript interfaces used by IPFS internals

## Table of contents <!-- omit in toc -->

- [Structure](#structure)
- [Packages](#packages)
- [API Docs](#api-docs)
- [License](#license)
- [Contribute](#contribute)

## Structure

- [`/packages/interface-blockstore`](./packages/interface-blockstore) An interface for storing and retrieving blocks
- [`/packages/interface-blockstore-tests`](./packages/interface-blockstore-tests) Compliance tests for the blockstore interface
- [`/packages/interface-datastore`](./packages/interface-datastore) datastore interface
- [`/packages/interface-datastore-tests`](./packages/interface-datastore-tests) Compliance tests for the datastore interface
- [`/packages/interface-store`](./packages/interface-store) A generic interface for storing and retrieving data

## Packages

See the [./packages](./packages) directory for the various interfaces.

## API Docs

- <https://ipfs.github.io/js-ipfs-interfaces>

## License

Licensed under either of

- Apache 2.0, ([LICENSE-APACHE](LICENSE-APACHE) / <http://www.apache.org/licenses/LICENSE-2.0>)
- MIT ([LICENSE-MIT](LICENSE-MIT) / <http://opensource.org/licenses/MIT>)

## Contribute

Contributions welcome! Please check out [the issues](https://github.com/ipfs/js-ipfs-interfaces/issues).

Also see our [contributing document](https://github.com/ipfs/community/blob/master/CONTRIBUTING_JS.md) for more information on how we work, and about contributing in general.

Please be aware that all interactions related to this repo are subject to the IPFS [Code of Conduct](https://github.com/ipfs/community/blob/master/code-of-conduct.md).

Unless you explicitly state otherwise, any contribution intentionally submitted for inclusion in the work by you, as defined in the Apache-2.0 license, shall be dual licensed as above, without any additional terms or conditions.

[![](https://cdn.rawgit.com/jbenet/contribute-ipfs-gif/master/img/contribute.gif)](https://github.com/ipfs/community/blob/master/CONTRIBUTING.md)
