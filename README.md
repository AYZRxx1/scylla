Scylla [![Build Status](https://travis-ci.org/imWildCat/scylla.svg?branch=master)](https://travis-ci.org/imWildCat/scylla) [![codecov](https://codecov.io/gh/imWildCat/scylla/branch/master/graph/badge.svg)](https://codecov.io/gh/imWildCat/scylla) [![Documentation Status](https://readthedocs.org/projects/scylla-py/badge/?version=latest)](https://scylla.wildcat.io/en/latest/?badge=latest) [![PyPI version](https://badge.fury.io/py/scylla.svg)](https://badge.fury.io/py/scylla) [![Docker Build Status](https://img.shields.io/docker/build/wildcat/scylla.svg)](https://hub.docker.com/r/wildcat/scylla/) 
===

An intelligent proxy pool for humanities, only supports Python 3.6. Key features:

- Automatic proxy ip crawling and validation
- Easy-to-use JSON API
- Simple but beautiful web-based user interface (eg. geographical distribution of proxies)
- Get started with only **1 command** minimally
- Straightforward programmable API
- (Additional) Headless browser crawling


## Get started

### Install with Docker (highly recommended)

```bash
docker run -it --name scylla wildcat/scylla
```

### Install directly via pip

```bash
pip install scylla
scylla # Run the cralwer and web server for JSON API
```

### Use from source

```bash
git clone https://github.com/imWildCat/scylla.git
cd scylla

pip install -r requirements.txt

npm install # or yarn install
npm build # or yarn build

python -m scylla
```

### Programmatically


For more details, please read the [API Documentation](http://scylla.wildcat.io/en/latest/py-modindex.html).

## Roadmap

- [x] Basic RESTFul API
- [x] Advanced RESTFul API (Sorting, paging, conditions)
- [ ] Programmable API
- [x] Docker integration
- [ ] Smart web proxy server
- [ ] More statistical views of proxies
- [ ] Quality statistics for different providers
- [ ] Over 20 data sources

## Development and Contribution

```bash
git clone https://github.com/imWildCat/scylla.git
cd scylla

pip install -r requirements.txt

npm install # or yarn install
```

## Testing

```bash
pip install -r tests/requirements-test.txt
pytest -n 10 tests
```

## License

Apache License 2.0. For more details, please read the [LICENSE](./LICENSE) file.