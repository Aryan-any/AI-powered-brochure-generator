# AI-powered-brochure-generator
An intelligent tool that automatically creates professional brochures for companies by scraping and navigating their websites. This project leverages AI to extract relevant content—such as services, team information, contact details, and visuals—from a company's official site, then formats it into a clean, ready-to-use brochure.

This README.md file is comprehensive and easy to use for your AI-Powered Brochure Generator project:

🧠 AI-Powered Brochure Maker
A clever tool that, when a company's website link is entered, automatically generates a polished brochure for them. After using AI to comprehend, extract, and arrange the website's content, it displays it in a tidy brochure format.
This project allows users to choose between local or cloud-based inference, and it works flawlessly with both OpenAI and Ollama models running locally.

🚀 What Is the Purpose of This Project?
This project goes to a business's website, makes intelligent use of it, and extracts helpful data like

Concerning the business

Goods and services

Leadership and teamwork

Contact details

Pictures or logos

After that, it automatically formats everything into a clean, well-organized brochure that can be viewed in HTML or exported as a PDF.

✅ Business Applications

Hours of manual labor can be saved with this tool. It is helpful in:

Marketing agencies can produce client brochures for meetings or proposals in a timely manner.

📋 Sales Teams: Prior to outreach, get an overview of the company.

🧾 Business consultants: Create company summaries using only a website link.

🏢 Startups: Use your own website to automatically generate content that is ready for investors.

Tech Stack & Models Utilized 👇 Local + Cloud Models

Ollama: A tool for locally executing AI models on your computer.

Cloud model performance is tested and compared using OpenAI (GPT-4/GPT-3.5).

After testing, both models functioned well. Depending on availability, the app can alternate between local and cloud models.

🧰 Tools and Libraries

Python (for logic in the backend)

Requests & BeautifulSoup (for web scraping)

ReportLab and HTML2PDF (for formatting brochures)

Flask or Streamlit (optional for frontend interface)

Here’s a detailed and beginner-friendly `README.md` file for your **AI-Powered Brochure Generator** project:

---

# 🧠 AI-Powered Brochure Generator

An intelligent tool that automatically creates a professional brochure for any company just by entering their website link. It uses AI to understand, extract, and organize content from the website and then presents it in a clean brochure format.

This project works perfectly with both **OpenAI** models and **Ollama** models running locally, giving users the flexibility to choose between cloud-based or local inference.

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

Both models were tested and **worked successfully**. The app can switch between local and cloud models based on availability.

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
* Enter the link: `https://www.ibm.com`
* The tool will:

  * Extract sections like “About IBM”, “Services”, “Leadership”, “Contact”
  * Generate a clean PDF brochure

Output:
📄 `ibm_brochure.pdf` created in your local folder!

---

## 📎 Folder Structure

```
├── main.py                  # Main script to run the generator
├── scraper/                 # Web scraping logic
├── ai_engines/              # OpenAI and Ollama model integrations
├── brochure_builder/        # Code to create and export brochure
├── templates/               # Optional HTML or PDF templates
├── requirements.txt         # Dependencies
```

---

## 🤝 Contributing

Feel free to fork this repository, add new features like multilingual support or custom design templates, and open a pull request!

---

## 📬 Contact

Made with 💡 by Aryan Mishra
For queries or suggestions, feel free to reach out at: **[aryanmishra.dev@gmail.com](mailto:aryanmishra.dev@gmail.com)**

---

Let me know if you want me to include specific screenshots, code examples, or turn this into a web app version!



























