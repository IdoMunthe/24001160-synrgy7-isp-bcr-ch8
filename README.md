### Endpoints

- ### Auth

| Endpoint               | Method | Description                          |
| ---------------------- | ------ | ------------------------------------ |
| `/api/v1/sign-in`      | POST   | Masuk menggunakan email dan password |
| `/api/v1/sign-up`      | POST   | Membuat akun baru                    |
| `/api/v1/user/current` | GET    | Mendapatkan data pengguna yang masuk |

- ### Cars

| Endpoint           | Method | Description                         |
| ------------------ | ------ | ----------------------------------- |
| `/api/v1/cars`     | GET    | Mengambil semua data mobil          |
| `/api/v1/cars/:id` | GET    | Mengambil data mobil berdasarkan ID |
| `/api/v1/cars`     | POST   | Menyimpan data mobil baru           |
| `/api/v1/cars/:id` | PUT    | Mengedit data mobil berdasarkan ID  |
| `/api/v1/cars/:id` | DELETE | Menghapus data mobil berdasarkan ID |

- ### Sizes

| Endpoint            | Method | Description                          |
| ------------------- | ------ | ------------------------------------ |
| `/api/v1/sizes`     | GET    | Mengambil semua data ukuran          |
| `/api/v1/sizes/:id` | GET    | Mengambil data ukuran berdasarkan ID |
| `/api/v1/sizes`     | POST   | Menyimpan data ukuran baru           |
| `/api/v1/sizes/:id` | PUT    | Mengedit data ukuran berdasarkan ID  |
| `/api/v1/sizes/:id` | DELETE | Menghapus data ukuran berdasarkan ID |

- ### Users

| Endpoint            | Method | Description                            |
| ------------------- | ------ | -------------------------------------- |
| `/api/v1/users`     | GET    | Mengambil semua data pengguna          |
| `/api/v1/users/:id` | GET    | Mengambil data pengguna berdasarkan ID |
| `/api/v1/users`     | POST   | Menyimpan data pengguna baru           |
| `/api/v1/users/:id` | PUT    | Mengedit data pengguna berdasarkan ID  |
| `/api/v1/users/:id` | DELETE | Menghapus data pengguna berdasarkan ID |
