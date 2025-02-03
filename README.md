# 🌱🦠 Phát Hiện Bệnh Trên Cây Trồng

## 📚 Giới Thiệu
Dự án này nhằm tạo một hệ thống giúp phát hiện các bệnh trên cây trồng từ ảnh chụp lá cây. Hệ thống sử dụng Deep Learning để nhận diện các bệnh thường gặp như: **vàng lá, sâu bệnh, nấm mốc, thiếu dinh dưỡng**.

## 🌍 Ứng Dụng
- Hỗ trợ nông dân phát hiện bệnh nhanh chóng.
- Giúp giảm thiệt hại do bệnh hại gây ra.
- Tích hợp với mobile/web để sử dụng tiện lợi.

## 💡 Công Nghệ Sử Dụng
- **Dataset**: [PlantVillage](https://www.tensorflow.org/datasets/catalog/plant_village), các bộ dữ liệu về bệnh trên lúa, cà chua, chuối.
- **Mô Hình**: CNN, MobileNet, EfficientNet, YOLOv8.
- **Thư Viện**: OpenCV, TensorFlow/Keras, PyTorch.
- **Triển Khai**: Web app (Flask/FastAPI, Streamlit), Mobile app (TensorFlow Lite, ONNX).

## 📚 Hướng Dẫn Cài Đặt
1. **Clone repository**:
   ```bash
   git clone https://github.com/HuynhThoaiK27/FarmAI.git
   cd FarmAI
   ```
2. **Cài đặt Python và thư viện cần thiết**:
   ```bash
   pip install -r requirements.txt
   ```
3. **Chạy huấn luyện mô hình**:
   ```bash
   python train.py
   ```
4. **Triển khai và chạy demo**:
   ```bash
   streamlit run app.py
   ```

## 📈 Kết Quả Dự Kiến
- Độ chính xác mong muốn: **>90%**.
- Dự đoán bệnh chính xác trên ảnh thực tế.
- Giao diện thân thiện cho người dùng.

## 👥 Đóng Góp
Mọi đóng góp đều được hoan nghênh! Nếu bạn muốn cải thiện dự án, vui lòng:
1. Fork repo này.
2. Tạo branch mới: `git checkout -b feature-moi`
3. Commit thay đổi: `git commit -m "Mô tả thay đổi"`
4. Push lên GitHub: `git push origin feature-moi`
5. Tạo pull request.

## 🎉 Liên Hệ
- **Tác giả**: Huỳnh Văn Thoại.
- **Email**: [hthoai746@gmail.com](mailto:your-email@example.com).
- **GitHub**: [HuynhThoaiK27](https://github.com/HuynhThoaiK27).

---
🌟 *Cùng nhau phát triển nông nghiệp thông minh với AI!*

