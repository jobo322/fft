# ml-fft

  [![NPM version][npm-image]][npm-url]
  [![build status][travis-image]][travis-url]
  [![David deps][david-image]][david-url]
  [![npm download][download-image]][download-url]

fft library for the ml libraries.

### 1D FFT

`var n = 16;
`        var nCols = n;
`
`        FFT.init(nCols);
`
`        var re = new Array(nCols);
`        var im = new Array(nCols);
`        for(var i=0;i<nCols;i++){
`            re[i]=i;
`            im[i]=nCols-i-1;
`        }
`
`        FFT.fft(re, im);
`        FFT.ifft(re, im);

## Installation

`$ npm install ml-fft`

## License

  [MIT](./LICENSE)

[npm-image]: https://img.shields.io/npm/v/ml-fft.svg?style=flat-square
[npm-url]: https://npmjs.org/package/ml-fft
[travis-image]: https://img.shields.io/travis/mljs/fft/master.svg?style=flat-square
[travis-url]: https://travis-ci.org/mljs/fft
[david-image]: https://img.shields.io/david/mljs/fft.svg?style=flat-square
[david-url]: https://david-dm.org/mljs/fft
[download-image]: https://img.shields.io/npm/dm/ml-fft.svg?style=flat-square
[download-url]: https://npmjs.org/package/ml-fft
