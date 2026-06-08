# Sistem Pengurusan Kokurikulum PPKI SKDS 2026

Sistem pengurusan kokurikulum PPKI untuk Sekolah Kebangsaan Dato' Syed Ahmad, dibina dengan Next.js 15, TypeScript, Tailwind CSS, komponen gaya Shadcn UI, Supabase, jsPDF dan html2canvas.

## Cara guna

```bash
npm install
npm run dev
```

Buka `http://localhost:3000/login`.

## Login demo

- Admin: `admin@skds.edu.my` / `admin123`
- Guru: `guru@skds.edu.my` / `guru123`
- Viewer: `viewer@skds.edu.my` / `viewer123`

## Supabase

1. Salin `.env.example` kepada `.env.local`.
2. Isi nilai Supabase.
3. Jalankan SQL dalam `supabase/schema.sql`.

Jika env Supabase belum diisi, sistem menggunakan data sampel tempatan untuk review UI dan aliran kerja.
