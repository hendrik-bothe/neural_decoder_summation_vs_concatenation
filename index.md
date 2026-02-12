---
title: Audio Samples — Shared Neural Audio Decoder Across Codec Operating Points
---

# Audio Samples for the paper "Shared Neural Audio Decoder Across Codec Operating Points"

This page provides qualitative audio comparisons for a decoder-side interoperability study.  
We keep the official encoders/quantizers fixed (EnCodec and DAC) and train the same GAN-augmented decoder architecture and training recipe across multiple codec operating points.  
Each sample compares:

1. **Reference** (original audio)
2. **Official codec decode** (codec-specific decoder output)
3. **Ours** (shared-decoder reconstruction)

---

## Audio comparisons

### Sample s01 — EnCodec, 24 kHz / 6 kbps

**Reference (original audio)**  
<audio controls preload="none" src="audio/s01/ref.mp3"></audio>

**Official codec decode**  
<audio controls preload="none" src="audio/s01/codec.mp3"></audio>

**Ours (shared decoder)**  
<audio controls preload="none" src="audio/s01/ours.mp3"></audio>

---

### Sample s02 — DAC, 44.1 kHz / ~8 kbps

**Reference (original audio)**  
<audio controls preload="none" src="audio/s02/ref.mp3"></audio>

**Official codec decode**  
<audio controls preload="none" src="audio/s02/codec.mp3"></audio>

**Ours (shared decoder)**  
<audio controls preload="none" src="audio/s02/ours.mp3"></audio>

---

## Citation

```bibtex
@inproceedings{bothe_shared_decoder_2026,
  title     = {On Training a Shared Neural Audio Decoder Across Codec Operating Points},
  author    = {Bothe, Hendrik and Geierhos, Michaela},
  booktitle = {EUSIPCO 2026 (submitted)},
  year      = {2026}
}
