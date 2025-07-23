
# Accommodation Booking System

A full-featured hotel booking portal with payment gateway, admin panel, and real-time availability tracking.

---

## 🛠 Tech Stack
- **Frontend**: HTML, Bootstrap, JavaScript
- **Backend**: PHP (Procedural)
- **Database**: MySQL
- **Payments**: Razorpay
- **Notifications**: Email + SMS
- **PDF Invoice**: TCPDF / FPDF (vendor-based)
- **Auth**: Admin Login with Password Reset

---

## 📁 Folder Structure

```
accommodation-booking/
├── admin/
│   ├── dashboard.php
│   ├── analytics.php
│   ├── manage_users.php
│   ├── manage_rooms.php
│   └── ...
├── api/
│   ├── search_hotels.php
│   ├── hotel_details.php
│   ├── book_room.php
│   └── ...
├── assets/
│   ├── css/
│   └── js/
├── uploads/ids/
├── vendor/razorpay-php/
├── pages/
│   ├── booking.html
│   ├── hotel-details.html
│   └── ...
├── db.php
└── index.php
```

---

## 🚀 Setup Instructions

1. Import the SQL schema and sample data (`schema.sql`)
2. Update `db.php` with your database credentials
3. Configure Razorpay credentials in `book_room.php` and `payment_success.php`
4. Upload to your Apache/PHP hosting or run locally via XAMPP
5. Admin Login: `/admin/login.php`

---

## 🔑 Default Admin Access

```
Username: admin@example.com
Password: admin123
```

---

## ✨ Features

- Search & filter hotels by star, price, distance
- Room booking with guest ID upload
- Razorpay payment checkout
- Booking confirmation via email/SMS
- Admin dashboard with analytics & CSV export
- Inline add/edit/delete for users & rooms
- PDF invoice generation

---

## 📞 Support

For support or enhancements, contact your development team or file an issue on your internal project tracker.

