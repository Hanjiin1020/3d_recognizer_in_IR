# Archived experiment checkpoints

This directory contains three legacy PyTorch checkpoints produced during the
team's Intel RealSense D455 point-cloud segmentation experiments. The raw and
annotated datasets used to create them are not distributed in this archive.

| Checkpoint | Experiment | Size (bytes) | SHA-256 |
| --- | --- | ---: | --- |
| `count` | Fingertip segmentation for finger-count poses | 4,957,300 | `7338F2CF1ACEE6AD8A0AD5B0C82BA3000C9FE29A0D1E32212CC790349F8ADF48` |
| `face` | Nose-and-chin region segmentation | 4,962,153 | `99C2E122B48E36C2DADB99A57273C08B9F3DDF9397BD7D5170A057464EBAF5D0` |
| `signlanguage` | Fingertip or hand-feature segmentation for selected gestures | 4,967,308 | `F73F985F768CD16D6F2767DF5037A638CB7DDFD3C6C5C8AF25BD0A18EDB9645E` |

These files are preserved as historical project artifacts, without a separate
reuse license or a claim of production readiness. They use a legacy
pickle-based PyTorch serialization path. Do not load them unless you trust this
repository and understand the risks of deserializing model files. No execution
support or compatibility guarantee is provided.
