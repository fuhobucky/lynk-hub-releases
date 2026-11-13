# Lynk Hub — bản phát hành

Bản cài APK của Lynk Hub (launcher cho head unit Lynk & Co 03, ECARX, Android 9). Không chứa mã nguồn.
Hub tự kiểm tra và cập nhật từ repo này; chỉ cài khi xe đỗ ở số P và file khớp SHA-256.

Mỗi bản phát hành có:
- `lynk-hub-<phiên bản>.apk`
- `lynk-hub-<phiên bản>.apk.sha256`

## Mã nguồn bên thứ ba
APK có kèm:
- **go-librespot** (GPL-3.0): https://github.com/devgianlu/go-librespot. Bản dựng tĩnh linux/arm64, kèm các bản vá của Lynk Hub. Mã nguồn tương ứng có thể yêu cầu qua Issues của repo này.
- **sherpa-onnx** (Apache-2.0): https://github.com/k2-fsa/sherpa-onnx, cùng model nhận dạng tiếng Việt và Silero VAD.
