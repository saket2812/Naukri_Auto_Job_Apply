### **Naukri Auto Apply Script 🚀**  
This is a **Python automation script** that automatically **logs into Naukri.com**, searches for jobs based on your **job title, location, experience, and salary preferences**, and **applies to relevant job listings**. The script also **saves applied job details in a CSV file** for tracking.  

---

## **📌 Features**  
✅ **Automated Login** – Logs into your Naukri account using credentials from a `.env` file.  
✅ **Job Search Automation** – Searches for jobs based on **designation, location, experience, and salary**.  
✅ **Smart Job Application** – Automatically applies for jobs **without manual intervention**.  
✅ **Handles Pop-up Questions** – Fills predefined answers for common interview questions.  
✅ **Avoids Duplicate Applications** – Skips jobs already applied for.  
✅ **Tracks Applied Jobs** – Saves applied job details (Company Name, Date) in a `CSV` file.  
✅ **GitHub Ready** – Supports `.gitignore` to **hide sensitive credentials** from GitHub.  

---

## **🔧 Setup & Installation**  
### **1️⃣ Install Dependencies**  
Make sure you have **Python** installed, then run:  
```bash
pip install selenium webdriver-manager python-dotenv pandas
```

### **2️⃣ Create a `.env` File**  
Before running the script, create a `.env` file in the project folder and add:  
```
NAUKRI_EMAIL=your_email@example.com
NAUKRI_PASSWORD=your_password
JOB_TITLE=Python Developer
JOB_LOCATION=Pune
EXPERIENCE=3
SALARY=600000
```

### **3️⃣ Run the Script**  
```bash
python naukri_auto_apply.py
```

---

## **📝 How It Works**
1️⃣ Logs into **Naukri.com**.  
2️⃣ Searches for jobs using **your criteria**.  
3️⃣ **Applies to jobs** while avoiding duplicate applications.  
4️⃣ Fills out **job application pop-ups** (if any).  
5️⃣ **Saves applied jobs** to `applied_jobs.csv`.  

---

## **🚀 Future Improvements**
- [ ] **Better error handling** for failed job applications.  
- [ ] **Support for more job portals** like **LinkedIn, Indeed**.  
- [ ] **Smart filtering** to apply only to **relevant job descriptions**.  

🔥 **Now automate your job search like a pro!** 🚀💯  
Let me know if you need any modifications. 😎
