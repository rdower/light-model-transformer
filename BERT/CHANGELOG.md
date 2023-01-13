# BERT Model Optimization Change Log

## v0.7 - 2022-11-02

### Added

* Variadic BERT parameters: sequence length, hidden size, intermediate size, layers number
* BERT-Large model support
* INT8 quantization factors calibration mode - see [Calibration mode](python/README.md#calibration-mode) section in [Python tools documentation](python/README.md)

### Known Issues

* INT8 quantization mode has an accuracy issue for sequence length > 128
* Maximum supported TensorFlow version is 2.9

## v0.5 - 2022-06-28

### Added

* Initial release
* Enabled BERT Base with fixed sequence length 128
* Added support for TensorFlow v.1.15, v.2.x

### Known Issues

* BERT model variants support limited to BERT-Base SeqLen=128