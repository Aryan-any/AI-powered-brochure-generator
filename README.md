This is a detailed and beginner-friendly `README.md` file for this **AI-Powered Brochure Generator** project:

---

# 🧠 AI-Powered Brochure Generator

An intelligent tool that automatically creates a professional brochure for any company just by entering their website link. It uses AI to understand, extract, and organize content from the website and then presents it in a clean brochure format.

This project works perfectly with both **OpenAI** models and **Ollama** models running locally, users get the flexibility to choose between cloud-based or local inference.

---

## 🚀 What Does This Project Do?

This project visits a company’s website, navigates it intelligently, and pulls useful information such as:

* **About the company**
* **Products and services**
* **Team and leadership**
* **Contact information**
* **Images or logos**

Then, it automatically formats all of this into a **neatly structured brochure**, which can be exported as a PDF or viewed as HTML.

---

## ✅ Business Use Cases

This tool can save hours of manual work. It’s useful in:

* 📢 **Marketing Agencies** – Quickly generate client brochures for meetings or proposals.
* 📋 **Sales Teams** – Get a summary of a company before outreach.
* 🧾 **Business Consultants** – Prepare company profiles with just a website link.
* 🏢 **Startups** – Automatically create investor-ready material from your own site.

---

## 🛠️ Tech Stack & Models Used

### 👇 Local + Cloud Models

* **Ollama** – Used to run AI models locally on your machine.
* **OpenAI (GPT-4/GPT-3.5)** – Used to test and compare cloud model performance.

Both models were tested and **worked successfully**.

### 🧰 Libraries and Tools

* Python (for backend logic)
* BeautifulSoup & Requests (for web scraping)
* ReportLab / HTML2PDF (for brochure formatting)
* Streamlit / Flask (optional for frontend interface)

---

## 🔧 How to Run the Project

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/ai-brochure-generator.git
cd ai-brochure-generator
```

### 2. Install Dependencies

```bash
pip install -r requirements.txt
```

### 3. Set up API keys (optional)

If using OpenAI:

```bash
export OPENAI_API_KEY=your_key_here
```

If using Ollama (make sure it's installed and running locally), no key is required.

### 4. Run the Script

```bash
python main.py
```

You will be asked to enter a company website link, and the tool will generate the brochure automatically.

---

## 💡 Example Usage

Let's say you want a brochure for **[https://www.ibm.com](https://www.ibm.com)**

* Run the script
* Enter the link: `https://www.ibm.com` or any other website link in case this website doesn't allow easy scraping.
* The tool will:

  * Extract sections like “About IBM”, “Services”, “Leadership”, “Contact”
  * Generate a clean PDF brochure

Output:
📄 `ibm_brochure.pdf` created in your local folder!

---


---

## 🤝 Contributing

Feel free to fork this repository, add new features like multilingual support or custom design templates, and open a pull request!

---

## 📬 Contact

Inspired by Edward Donner (https://github.com/ed-donner)
Made with 💡 by Aryan Mishra
For queries or suggestions, feel free to reach out at: **[mishraaryanm@gmail.com](mailto:mishraaryanm@gmail.com)**

---



























