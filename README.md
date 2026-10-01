# KTXGo

Ứng dụng mua sắm dành cho sinh viên được xây dựng bằng React Native.

## Thông tin sinh viên

- Họ và tên: PHẠM THANH HƯNG
- MSSV: 23688581
- Tên project: KTXGo_23688581
- Nền tảng: React Native / Android

## Giới thiệu

KTXGo là ứng dụng mua sắm trên thiết bị di động dành cho sinh viên.

Ứng dụng cho phép người dùng xem danh sách sản phẩm, tìm kiếm và lọc sản phẩm, xem thông tin chi tiết, thêm sản phẩm vào giỏ hàng và quản lý số lượng sản phẩm.

## Chức năng

### Cửa hàng

- Hiển thị danh sách sản phẩm từ API.
- Hiển thị hình ảnh, tên, giá, danh mục và đánh giá sản phẩm.
- Pull-to-refresh để tải lại dữ liệu.
- Tìm kiếm sản phẩm theo tên.
- Lọc sản phẩm theo danh mục.
- Xem chi tiết sản phẩm.

### Chi tiết sản phẩm

- Hiển thị hình ảnh sản phẩm.
- Hiển thị tên sản phẩm.
- Hiển thị danh mục.
- Hiển thị giá.
- Hiển thị đánh giá.
- Hiển thị mô tả sản phẩm.
- Thêm sản phẩm vào giỏ hàng.

### Giỏ hàng

- Thêm sản phẩm vào giỏ hàng.
- Tăng số lượng sản phẩm.
- Giảm số lượng sản phẩm.
- Xóa một sản phẩm.
- Xóa toàn bộ giỏ hàng.
- Tính tổng số lượng sản phẩm.
- Tính tổng giá trị giỏ hàng.

### Tìm kiếm và lọc

- Tìm kiếm sản phẩm theo từ khóa.
- Lọc theo danh mục.
- Kết hợp tìm kiếm và lọc.
- Hiển thị số lượng kết quả.
- Xóa bộ lọc.

### Yêu thích

Chức năng đang được phát triển:

- Thêm sản phẩm vào danh sách yêu thích.
- Xóa sản phẩm khỏi danh sách yêu thích.
- Lưu danh sách yêu thích trên thiết bị.

### Vị trí

Chức năng sẽ được bổ sung để hỗ trợ thông tin vị trí của người dùng.

## Công nghệ sử dụng

- React Native
- TypeScript
- React Navigation
- TanStack React Query
- Zustand
- AsyncStorage
- REST API
- Android

## Cấu trúc project

```text
KTXGo_23688581/
│
├── android/
├── ios/
├── src/
│   ├── assets/
│   ├── components/
│   │   ├── ProductCard.tsx
│   │   ├── LoadingView.tsx
│   │   └── ErrorView.tsx
│   │
│   ├── screens/
│   │   ├── ShopScreen.tsx
│   │   ├── ProductDetailScreen.tsx
│   │   ├── CartScreen.tsx
│   │   └── MeScreen.tsx
│   │
│   ├── navigation/
│   │   ├── RootNavigator.tsx
│   │   ├── MainTabs.tsx
│   │   └── ShopStack.tsx
│   │
│   ├── stores/
│   │   └── useAppStore.ts
│   │
│   ├── services/
│   │   ├── api.ts
│   │   └── locationService.ts
│   │
│   ├── hooks/
│   │   └── useProducts.ts
│   │
│   ├── data/
│   ├── types/
│   ├── constants/
│   └── utils/
│
├── App.tsx
├── package.json
└── README.md
```

## Cài đặt

Cài đặt dependencies:

```bash
npm install
```

Khởi động Metro:

```bash
npx react-native start
```

Ở terminal khác, chạy ứng dụng Android:

```bash
npx react-native run-android
```

## Yêu cầu môi trường

- Node.js
- npm
- JDK 17
- Android SDK
- Android Emulator hoặc thiết bị Android
- React Native CLI

## Trạng thái project

Đã hoàn thành:

- Khởi tạo project React Native.
- Navigation.
- Bottom Tab Navigation.
- Kết nối API sản phẩm.
- Danh sách sản phẩm.
- Chi tiết sản phẩm.
- Tìm kiếm.
- Lọc theo danh mục.
- Giỏ hàng.
- Tăng/giảm số lượng.
- Xóa sản phẩm.
- Tính tổng tiền.

Đang tiếp tục:

- Favorites.
- Lưu dữ liệu bằng AsyncStorage.
- Location.
- Checkout.
- Hoàn thiện giao diện.
- Kiểm thử ứng dụng.

## Tác giả

**PHẠM THANH HƯNG**

MSSV: **23688581**