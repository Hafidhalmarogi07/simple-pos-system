
# Simple POS System – Backend REST API (Java + Spring Boot)

Proyek ini adalah backend untuk sistem Point of Sale (POS) sederhana yang dibangun menggunakan Java 21 dan Spring Boot.

## Fitur Utama
- CRUD Produk
- Manajemen Pelanggan
- Transaksi Penjualan
- Riwayat Penjualan
- Autentikasi dan Otorisasi dengan JWT

## Teknologi
- Java 21
- Spring Boot 3
- Spring Security + JWT
- JPA + Hibernate
- PostgreSQL / MySQL
- Swagger (OpenAPI)
- Maven

## Struktur Endpoint
| Method | Endpoint             | Deskripsi                   |
|--------|----------------------|-----------------------------|
| POST   | /api/products        | Tambah produk               |
| GET    | /api/products        | Lihat semua produk          |
| POST   | /api/sales           | Proses penjualan            |
| GET    | /api/sales/history   | Lihat riwayat penjualan     |
| POST   | /api/auth/login      | Login dan dapatkan token    |
| GET    | /api/users/me        | Info user yang login        |
