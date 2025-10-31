# ⚡ FlashAttention 2.8.0.post2 — Prebuilt Wheel for NVIDIA L40S (CUDA 12.1)

This repository provides a **precompiled wheel** of [FlashAttention](https://github.com/Dao-AILab/flash-attention)  
for users running on **NVIDIA L40S / Ada GPUs (Compute Capability 8.9)**.  
The goal is to save others hours of build time and simplify installation for CUDA 12.1 setups.

---

## ✅ Build Information

- **FlashAttention:** 2.8.0.post2  
- **CUDA:** 12.1  
- **PyTorch:** 2.9.0  
- **Python:** 3.10  
- **GPU:** NVIDIA L40S (sm_89)  
- **OS:** Ubuntu 22.04 (Google Cloud VM)  
- **Wheel size:** ~111.5 MiB  
- **Build type:** Official source compiled manually, no code modifications  

---

## 📦 Download

👉 [https://github.com/h1312200313122003-code/flash-attn-prebuilt-L40S/releases/tag/v2.8.0.post2-cu121-l40s]

*(Replace the link above with your Google Drive or GitHub Release URL)*

---

## 🧩 Installation

```bash
pip install flash_attn-2.8.0.post2-cp310-cp310-linux_x86_64.whl
pip install --upgrade torch torchaudio torchvision   # Recommended for compatibility

Then verify installation:
python -c "import flash_attn, torch; print('✅ Installed:', torch.__version__, torch.cuda.get_device_name(0))"

Expected output example:
✅ Installed: 2.9.0 NVIDIA L40S

❤️ Notes

This build was created on a Google Cloud NVIDIA L40S VM to provide a working prebuilt wheel for CUDA 12.1.

Verified working for FlashAttention 2.8.0.post2 with full GPU acceleration.

If this helps you, please ⭐ the repo or share it so others can skip the long compile time!

⚖️ License

This prebuilt wheel is distributed under the same license as the original
FlashAttention
 project.

No modifications were made to the source code — only compiled for
CUDA 12.1 / NVIDIA L40S environments.

FlashAttention is licensed under the BSD 3-Clause License,
which allows redistribution and use with attribution.

For full license details, see the original
LICENSE file

in the upstream repository.
pip install flash_attn-2.8.0.post2-cp310-cp310-linux_x86_64.whl
pip install --upgrade torch torchaudio torchvision   # Recommended for compatibility
