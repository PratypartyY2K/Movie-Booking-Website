# 🎬 CineReserve: High-Concurrency Movie Booking Platform

**Technologies:** **PHP** (98.3%), **Vanilla JavaScript**, **MySQL (PHPMyAdmin)**, HTML5/CSS3, Bootstrap4

**Project Description:** A full-stack web application designed to manage the entire user lifecycle for movie ticket booking—from browsing showtimes to securely reserving seats and generating tickets. This project focuses on building a robust, database-driven backend to handle high-volume transactions and prevent data integrity issues.

## ✨ Key Architectural Highlights

* **Concurrency Management (High-Concurrency):** Developed the core booking logic (`process.php`, `booking.php`) to manage and update seat availability in the MySQL database in real-time. This is critical for preventing the **double-booking** of seats when multiple users attempt to reserve the same ticket simultaneously.
* **Database Schema Design:** Engineered a relational database schema (MySQL, deployed via `iwp.sql`) to manage complex relationships between Movies, Showtimes, Theaters, and individual Bookings.
* **Visual Seat State Management:** Used **Vanilla JavaScript** on the client-side (`seat.php`) to dynamically render the auditorium layout and handle the selection state (Available, Selected, Booked), providing a smooth user experience.
* **Full End-to-End Workflow:** The application manages the entire booking pipeline, including secure user authentication (`login.php`), seat selection, payment simulation (`payment.php`), and final ticket generation (`ticket.php`).
* **Administrative Control:** Includes a separate Admin interface (`admin.php`, `AddMovie.php`) for managing inventory, showtimes, and movie details.

## 🛠️ Tech Stack Breakdown

| Component | Technology | Role |
| :--- | :--- | :--- |
| **Backend/Server** | **PHP** (Core Logic) | Handles all server-side processing, database interaction, and business logic. |
| **Database** | **MySQL** | Relational database management (using the `iwp.sql` schema). |
| **Frontend** | **HTML5/CSS3/JavaScript** | Client-side interactivity and responsive design (using Bootstrap4). |
| **Concurrency** | **SQL Transactional Logic** | Implicitly used for guaranteeing seat integrity during the booking process. |

## Authors

- [@joffy3691](https://github.com/joffy3691)
- [@PratypartyY2K](https://github.com/PratypartyY2K)

  
## Documentation

[Documentation](https://docs.google.com/document/d/1qtuP2xXJE-r_EYuIAuRk8V6CK2BD5U57k2YN25-YV6w/edit?usp=sharing)

  
## Installation 

#### For Ubuntu users
 - Download zip folder from github
 - Transfer this folder from Downloads to htdocs
 - To go to htdocs, follow these steps:
```bash
    sudo nautilus
```
 - Extra locations -> Computer -> opt -> lampp -> htdocs
 - Unzip the folder
 - Download PHPMyAdmin from official website
 - Configure and open it

```bash 
  cd /opt/lampp
  sudo ./manager-linux-x64.run
```
 - Click on "Start All"
 - Open browser and type http://localhost/phpmyadmin
 - Create a new database, iwp and go to the database
 - Click on Import button
 - Import the file "iwp.sql" situated in the IWP folder (htdocs)
 - You are now good to go
 - Open the IWP folder in any text editor/IDE and make changes.
  
## Acknowledgements

 - [W3 Schools](https://www.w3schools.com/)
 - [Developer Mozilla DOcs](https://developer.mozilla.org/en-US/)
 - [Official PHP Manual](https://www.php.net/manual/en/index.php)
 - [PHPMyAdmin](https://www.phpmyadmin.net/)
 - [CSS Tricks](https://css-tricks.com/)
 - [JavaScript Official Website](https://www.javascript.com/)
 - [Bootstrap Carousel](https://getbootstrap.com/docs/4.0/components/carousel/)
 - [BookMyShow](https://bookmyshow.com/)

  
## Screenshots

Screenshots are present in the Documentation provided.
  
