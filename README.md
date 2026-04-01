# 🪐 The Invincible – Web3 Mini Farming Game

**The Invincible** là một Web3 Mini Farming Game, mô phỏng trải nghiệm **Play-to-Earn** hoàn toàn ở phía client. Trò chơi không yêu cầu giao dịch on-chain cho các hoạt động chính, toàn bộ dữ liệu game được lưu trữ trên **LocalStorage** của trình duyệt. Việc kết nối ví Sui được sử dụng để định danh người chơi và chuẩn bị cho các tính năng on-chain trong tương lai.

Giao diện được thiết kế theo phong cách **Glassmorphism + Parallax Space + Futuristic UI**, với các hiệu ứng mượt mà được thực hiện bởi **Framer Motion** để mang lại trải nghiệm không gian vũ trụ sống động.
<img src="https://drive.google.com/uc?export=view&id=1GqD58dTMUZFpQYgqEG8i1mC43G-Udik8">
<p align="center">
  <img alt="React" src="https://img.shields.io/badge/React-18.2.0-blue?style=for-the-badge&logo=react">
  <img alt="TypeScript" src="https://img.shields.io/badge/TypeScript-5.0.2-blue?style=for-the-badge&logo=typescript">
  <img alt="Vite" src="https://img.shields.io/badge/Vite-4.4.5-yellowgreen?style=for-the-badge&logo=vite">
  <img alt="Status" src="https://img.shields.io/badge/Status-Hoàn%20thành-brightgreen?style=for-the-badge">
  <img alt="License" src="https://img.shields.io/badge/License-MIT-purple?style=for-the-badge">
</p>

<p align="center">
  <strong><a href="https://the-invincible-web3.vercel.app/">🚀 Chơi ngay 🚀</a></strong>
</p>

---

##  Mục lục

- [Giới thiệu](#-giới-thiệu)
- [Tính năng nổi bật](#-tính-năng-nổi-bật)
- [Hình ảnh DEMO](#-hình-ảnh-DEMO)
- [Công nghệ sử dụng](#-công-nghệ-sử-dụng)
- [Bắt đầu](#️-bắt-đầu)
- [Logic Trò chơi](#-logic-trò-chơi)
- [Cấu trúc thư mục](#-cấu-trúc-thư-mục)
- [Đóng góp](#-đóng-góp)
- [Giấy phép](#-giấy-phép)
- [Liên hệ](#-liên-hệ)

## 🚀 Giới thiệu

**The Invincible** là một Web3 Mini Farming Game, mô phỏng trải nghiệm **Play-to-Earn** hoàn toàn ở phía client. Trò chơi không yêu cầu giao dịch on-chain cho các hoạt động chính, toàn bộ dữ liệu game được lưu trữ trên **LocalStorage** của trình duyệt. Việc kết nối ví Sui được sử dụng để định danh người chơi và chuẩn bị cho các tính năng on-chain trong tương lai.

Trong **The Invincible**, bạn sẽ:
- **Trồng trọt:** Mua hạt giống, gieo trồng và chờ đợi cây lớn lên.
- **Thu hoạch:** Nhận phần thưởng là **Coins** (tiền tệ trong game) và **Airdrop Points (AP)**.
- **Giải trí:** Tham gia vào hơn 7 mini-game hấp dẫn để kiếm thêm Coins.
- **Săn thưởng:** Mở **Mystery Box** để có cơ hội nhận được những phần thưởng AP giá trị.

---

## ✨ Tính năng nổi bật

### 🎲 **7+ Mini-Games**
Một bộ sưu tập các mini-game đa dạng để giải trí và kiếm thêm Coins:
- **Dice:** Cược kết quả của một viên xúc xắc.
- **Tài Xỉu:** Cược tổng điểm của ba viên xúc xắc.
- **Mines:** Dò mìn để tìm kim cương và tránh bom.
- **Slot:** Quay máy slot để tìm các tổ hợp chiến thắng.
- **Tower:** Leo tháp qua các tầng đầy rủi ro.
- **Wheel:** Quay vòng quay may mắn để nhận thưởng.
- **Horse Race:** Đặt cược vào cuộc đua ngựa kịch tính.

### 🎨 **Giao diện & Trải nghiệm người dùng (UI/UX)**
- **Glassmorphism & Futuristic UI:** Tạo chiều sâu và cảm giác hiện đại.
- **Hiệu ứng Parallax:** Các hành tinh và vật thể di chuyển tạo không gian 3D sống động.
- **Nền chuyển động (Particle Background):** Mô phỏng một vũ trụ bao la, lấp lánh.
- **Animation mượt mà:** Sử dụng **Framer Motion** để tạo các hiệu ứng chuyển động, popup, và tương tác trơn tru.

---

## 🖼️ Hình ảnh DEMO
| Trang chủ | Games | History |
| :---: | :---: | :---: |
| <img src="https://drive.google.com/uc?export=view&id=1GqD58dTMUZFpQYgqEG8i1mC43G-Udik8" width="600"> | <img src="https://drive.google.com/uc?export=view&id=1tF5ryrx7WLZ2P-TaLHJHfTVczofLgLMQ" width="600"> | <img src="https://drive.google.com/uc?export=view&id=1v2ESyPLTMYk1bz3tkglG9F1AH6eSvUO1" width="600"> |

---

## 🛠️ Công nghệ sử dụng

| Hạng mục | Công nghệ |
| :--- | :--- |
| **Framework & Bundler** | React 18 + Vite |
| **Ngôn ngữ** | TypeScript |
| **UI/UX** | Mantine UI, Framer Motion |
| **Routing** | React Router DOM |
| **Web3** | Sui Wallet Adapter |
| **Lưu trữ** | LocalStorage |

---

## ⚡ Bắt đầu

### Yêu cầu
- Node.js (phiên bản 18.x trở lên)
- `npm`, `yarn` hoặc `pnpm`

### Cài đặt & Chạy

1.  **Clone repository về máy:**
    ```bash
    git clone https://github.com/huydinh203/the-invincible-web3.git
    ```

2.  **Di chuyển vào thư mục dự án:**
    ```bash
    cd the-invincible-web3
    ```

3.  **Cài đặt các dependencies:**
    ```bash
    npm install
    ```

4.  **Chạy dự án ở chế độ development:**
    ```bash
    npm run dev
    ```
    Mở trình duyệt và truy cập `http://localhost:5173`.

### Build dự án

Để tạo phiên bản production của ứng dụng, chạy lệnh:
```bash
npm run build
```
Các file tĩnh sẽ được tạo trong thư mục `dist/`.
---

# 📁 Cấu trúc thư mục
 ```bash
src/
│
├── config/
│   └── web3.ts          # Sui config & Treasury address
│
├── hooks/
│   ├── useWallet.ts
│   └── useSuiContract.ts
│
├── pages/
│   ├── Home/
│   ├── GameHub/
│   └── Game/
│       ├── Dice/
│       ├── TaiXiu/
│       ├── Mines/
│       ├── Slot/
│       ├── Tower/
│       ├── Wheel/
│       └── HorseRace/
│
├── utils/
│   └── saveTx.ts        # Transaction History helper
│
├── layout/
│   └── MainLayout.tsx
│
├── App.tsx
├── main.tsx
└── theme.ts
├── config/         # Cấu hình liên quan đến Web3 (Sui) và địa chỉ ví.
├── hooks/          # Các custom hooks cho logic (ví dụ: useWallet, useSuiContract).
├── pages/          # Các trang chính của ứng dụng (Home, GameHub, Mini-games).
├── utils/          # Các hàm tiện ích sử dụng chung.
├── layout/         # Bố cục chung của ứng dụng (MainLayout).
├── App.tsx         # Component gốc, nơi quản lý routing.
├── main.tsx        # Điểm vào của ứng dụng React.
└── theme.ts        # Cấu hình theme cho Mantine UI.
```
# 📦 Build & Deploy
```bash
Build
npm run build
```
[Tại đây](https://the-invincible-web3.vercel.app/)
