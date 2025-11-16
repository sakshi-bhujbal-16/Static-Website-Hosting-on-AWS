# Static Website Hosting on AWS S3

This project is a simple static website created using **HTML**, **CSS**, and **JavaScript**.  
As part of a practical task, the website was hosted on **AWS S3** using static website hosting.

The bucket was deleted after the practical to avoid AWS charges.

---

## 📂 Project Structure
The project contains the following files:

/my-portfolio/
│── index.html
│── style.css
│── script.js


- **index.html** → Main webpage  
- **style.css** → Styling for the webpage  
- **script.js** → JavaScript functionality  

---

## ☁️ AWS S3 Static Website Hosting (Practical Steps Performed)

### 👉 1. Open AWS Console  
Logged into **AWS Management Console** and opened the **S3** service.

### 👉 2. Create a New S3 Bucket  
Followed these steps to create the bucket:

- Selected **Bucket Type:** General Purpose  
- Gave a **unique bucket name:**  
  **`my-portfolio-bucket-16`**
- Chose region (default or nearest region)
- Kept remaining settings as default and created the bucket

### 👉 3. Upload Website Files  
Uploaded all three files as **objects** inside the bucket:

- `index.html`  
- `style.css`  
- `script.js`  

### 👉 4. Configure Bucket for Static Website Hosting  
- Went to **Properties** → **Static Website Hosting**  
- Enabled static website hosting  
- Set:
  - **Index document:** `index.html`

### 👉 5. Make Objects Public (For Hosting)  
- Updated **Bucket Permissions**  
- Allowed public access to the website files (only for the practical)

### 👉 6. Accessed Website  
AWS provided a website endpoint URL (S3 website link).  
Opening the link displayed the hosted website.

### 👉 7. Deleted the Bucket  
After completing the practical, the bucket **was deleted to avoid charges**, because S3 static website hosting + public access can incur minimal costs when kept for long.

---

## 📌 Notes
- This project is now uploaded on GitHub only as a **reference**.  
- AWS S3 static website hosting is not completely free; charges apply for storage and data transfer.  
- The bucket used during the practical **no longer exists**.

---

## 📘 How to View the Project Locally
You can open the website on your local machine by simply double-clicking:

index.html

## 🙌 Author
     -Sakshi Bhujbal
