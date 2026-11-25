# FNStudio Pro — Deploy lên Vercel (0 đồng phí GPU)

## Thành phần đi kèm
- `index.html`: Ứng dụng FNStudio Pro hoàn chỉnh đã gắn sẵn:
  - MediaPipe Face Landmarker (478 điểm 3D) cho Face AI & Retouch.
  - BRIA RMBG-1.4 (Transformers.js) cho tách Chủ thể / Tiền cảnh / Hậu cảnh.
  - SegFormer ADE20K (Transformers.js) cho tách Mây trời / Bầu trời.
- `vercel.json`: Cấu hình COOP/COEP mở khóa đa luồng WASM/WebGPU trên Vercel.

## Cách Deploy trong 2 phút
1. Giải nén thư mục này và đẩy toàn bộ lên một repo GitHub mới.
2. Vào https://vercel.com → Add New Project → Import repo GitHub vừa tạo.
3. Không cần cấu hình Build Command (để mặc định Static Site) → bấm Deploy.
