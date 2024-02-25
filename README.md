# Setting up tensorflow for mac M1
## Get started with tensorflow-metal
Accelerate the training of machine learning models with TensorFlow right on your Mac. Install base TensorFlow and the tensorflow-metal PluggableDevice to accelerate training with Metal on Mac GPUs.

[`Reference`](https://developer.apple.com/metal/tensorflow-plugin/)

## Requirements
- Mac computers with Apple silicon or AMD GPUs
- macOS 12.0 or later (Get the latest beta)
- Python 3.8 or later
- Xcode command-line tools: xcode-select --install

### Installing tensorflow for macos
```bash
python3 -m pip install tensorflow-macos
```

### For using Metal
```bash
python3 -m venv ~/venv-metal
source ~/venv-metal/bin/activate
python -m pip install -U pip
```
### For tensorflow versions 2.13 or higher
```bash
python -m pip install tensorflow
```
> [!NOTE]
> Installing tensorflow will install the following packages as well

### List of additional packages installed
```
MarkupSafe-2.1.5 absl-py-2.1.0 astunparse-1.6.3 cachetools-5.3.2 certifi-2024.2.2 charset-normalizer-3.3.2 flatbuffers-23.5.26 gast-0.5.4 google-auth-2.28.1 google-auth-oauthlib-1.2.0 google-pasta-0.2.0 grpcio-1.62.0 h5py-3.10.0 idna-3.6 keras-2.15.0 libclang-16.0.6 markdown-3.5.2 ml-dtypes-0.2.0 numpy-1.26.4 oauthlib-3.2.2 opt-einsum-3.3.0 packaging-23.2 protobuf-4.25.3 pyasn1-0.5.1 pyasn1-modules-0.3.0 requests-2.31.0 requests-oauthlib-1.3.1 rsa-4.9 six-1.16.0 tensorboard-2.15.2 tensorboard-data-server-0.7.2 tensorflow-2.15.0 tensorflow-estimator-2.15.0 tensorflow-io-gcs-filesystem-0.36.0 tensorflow-macos-2.15.0 termcolor-2.4.0 typing-extensions-4.9.0 urllib3-2.2.1 werkzeug-3.0.1 wheel-0.42.0 wrapt-1.14.1
```
