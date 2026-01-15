# 🤖 Daily Joke Notifier – n8n Automation

Daily Joke Notifier is an **automation workflow built with n8n** that fetches a random joke from a public API and sends it to your phone automatically using **Twilio SMS**.

This project demonstrates **workflow automation**, **API integration**, and **scheduled task execution** in a real-world use case.

---

## 🚀 Features

- Runs automatically on a daily schedule  
- Fetches a random joke from the Official Joke API  
- Formats a clean readable message  
- Sends the joke via SMS using Twilio  
- Fully automated — no manual action needed  

---

## ⚙️ Workflow Overview

Inside n8n, the automation flow looks like this:

[Schedule Trigger]
→ [HTTP Request (Joke API)]
→ [Edit Fields (Format Message)]
→ [Twilio SMS (Send Message)]



---

## 🖼️ Workflow Screenshot

![Workflow]
<img width="954" height="476" alt="n8n-workflow" src="https://github.com/user-attachments/assets/6eb0313a-8452-4dcd-a58f-a692e2abe509" />


---

## 🧠 Skills Demonstrated

- Workflow automation with n8n  
- REST API integration  
- Data transformation inside workflows  
- Twilio SMS integration  
- Scheduled background jobs  

---

## 😄 Example Joke Message

😂 Daily Joke 😂

Why don’t programmers like nature?

Because it has too many bugs

---

## ⚙️ Setup Instructions

1. Download or clone this repository.

2. Import the workflow into n8n  
   → Workflows → Import from File → Select the workflow JSON

3. Configure Twilio credentials in n8n:
   - Account SID  
   - Auth Token  
   - Your verified phone number  

4. Update the **To** field in the Twilio node with your phone number.

5. Activate the workflow.

---

## ✅ Result

Now you will receive:

- A fresh joke every day  
- Delivered automatically via SMS  
- Without opening n8n manually  

---

## 📌 Tech Stack

- n8n (Workflow Automation)  
- Official Joke API  
- Twilio SMS API  

---

## 👩‍💻 Author

**Hitaishi Lohtia**  
Automation & Web Developer
