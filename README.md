# 🌐 Divyam Lavri - Portfolio Website

This is the personal portfolio website of **Divyam Lavri**, an IT student and aspiring **cloud engineer & mobile app developer**. It showcases personal projects, skills, education, experience, and contact information in a clean and animated design.

---

## 🔗 Live Demos

- **Vercel**: [https://portfolio-1-neon-three.vercel.app/](https://portfolio-1-neon-three.vercel.app/)
- **AWS S3**: [http://divyamtestweb.s3-website-us-east-1.amazonaws.com/](http://divyamtestweb.s3-website-us-east-1.amazonaws.com/) *(Note: HTTP only)*

> 📌 Hosted on both Vercel and AWS S3 to demonstrate frontend deployment and cloud infrastructure capabilities.

---

## 📁 Project Structure

```
portfolio/
├── index.html          # Main HTML file
├── styles.css          # Custom CSS styles
├── images/             # Image assets (profile, project icons)
├── resume.pdf          # Downloadable resume file
```

---

## 🧰 Tech Stack

* **HTML5**
* **Tailwind CSS** (via CDN)
* **Custom CSS** (for animations and effects)
* **JavaScript** (for scroll and nav behavior)

---

## ✨ Features

* Responsive and mobile-friendly design
* Smooth scrolling navigation
* Animated gradient background and hover effects
* Project cards with custom icons/images
* Skills section with floating interaction
* Timeline layout for education and experience
* Contact section with social media links
* Downloadable resume

---

## 📸 Sections Overview

* **Home**: Welcome message, profession, profile image, resume button
* **About**: Personal introduction, values, badges
* **Projects**: Showcases apps like Outfit Matcher, AWS Inventory Script, E-Campus Food App
* **Skills**: Tech stack icons with hover effects
* **Education**: Timeline with CGPA and achievements
* **Experience**: Internship history with roles
* **Contact**: Email, phone, and social media icons
* **Footer**: Custom text with copyright

---

## 🛠️ Customization

* Replace `images/photo1.jpg`, `photo2.jpg`, and project images with your own
* Update `resume.pdf` file in the root directory
* Modify `index.html` to update content and links
* Edit `styles.css` to change color themes or animations

---

## 🚀 Deployment Instructions

### 🔷 Vercel Hosting

1. Push your code to a GitHub repository  
2. Connect the repo to [Vercel](https://vercel.com/)  
3. Choose the root directory (if needed)  
4. Click **Deploy**  
5. Get a live URL instantly  

### ☁️ AWS S3 Static Website Hosting

> Step-by-step deployment via AWS Management Console

1. Created a new S3 bucket named `divyamtestweb`
2. Uploaded all website files (HTML, CSS, JS, images)
3. Enabled **Static Website Hosting** under bucket properties
4. Set `index.html` as the entry point
5. Applied this **Bucket Policy** to make the site public:

```json
{
  "Version": "2012-10-17",
  "Statement": [
    {
      "Sid": "PublicReadGetObject",
      "Effect": "Allow",
      "Principal": "*",
      "Action": "s3:GetObject",
      "Resource": "arn:aws:s3:::divyamtestweb/*"
    }
  ]
}

## 📧 Contact

If you'd like to connect:

* **Email**: [divyamlavri@gmail.com](mailto:divyamlavri@gmail.com)
* **LinkedIn**: [linkedin.com/in/divyam](https://linkedin.com/in/divyam)

---

## 📄 License

This project is for personal use and showcasing only. Feel free to fork and modify for your own portfolio.
