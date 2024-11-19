# WhatsApp Chat Analysis 📊  

A **WhatsApp Chat Analysis** tool that extracts and analyzes data from exported WhatsApp chats. This project provides insights such as message frequency, active participants, word usage trends, and more through data visualization and Python scripts.  

---

## Table of Contents  

- [Introduction](#introduction)  
- [Key Features](#key-features)  
- [Tech Stack](#tech-stack)  
- [Installation](#installation)  
- [Usage](#usage)  
- [Analysis Insights](#analysis-insights)  
- [Future Enhancements](#future-enhancements)  
- [Contributing](#contributing)  
- [License](#license)  

---

## Introduction  

This project is designed to analyze WhatsApp chat logs and generate insightful visualizations. By processing the exported chat data, users can uncover patterns in communication, the most active participants, peak activity hours, and other interesting metrics.  

---

## Key Features  

- 📈 **Visualizes chat trends** like daily/weekly activity.  
- 💬 Identifies **most active participants** and top contributors.  
- 🕒 Analyzes **peak messaging times** and word usage.  
- 🔍 Extracts **emojis** and most frequently used words.  
- 📊 Provides detailed visual insights with graphs and charts.  

---

## Tech Stack  

- **Programming Language:** Python 🐍  
- **Libraries Used:** Pandas, NumPy, Matplotlib, Seaborn, re (Regular Expressions)  

---

## Installation  

### Prerequisites:  
- Python 3.8+  
- pip (Python package manager)  

### Steps:  

1. Clone the repository:  
   ```bash  
   git clone https://github.com/tarunkumar1111/whatsapp-chat-analysis.git  
   ```  

2. Navigate to the project directory:  
   ```bash  
   cd whatsapp-chat-analysis  
   ```  

3. Install the required dependencies:  
   ```bash  
   pip install -r requirements.txt  
   ```  

4. Export a WhatsApp chat in `.txt` format and place it in the project folder.  

5. Run the script:  
   ```bash  
   python chat_analysis.py  
   ```  

---

## Usage  

1. **Export WhatsApp Chat:**  
   - Open the desired chat on WhatsApp.  
   - Click on `Options > More > Export Chat`.  
   - Choose to export **without media** and save the `.txt` file.  

2. **Place the Exported Chat:**  
   - Save the exported `.txt` file in the project folder.  

3. **Run the Script:**  
   - Use the terminal/command prompt to execute `chat_analysis.py`.  
   - View the generated insights and visualizations.  

---

## Analysis Insights  

- **Message Trends:**  
  - Messages sent daily, weekly, and monthly.  
- **Participant Contribution:**  
  - Most active participants in group chats.  
- **Peak Activity:**  
  - Hours or days with maximum messaging activity.  
- **Emoji Analysis:**  
  - Frequently used emojis.  
- **Word Usage:**  
  - Most common words (excluding stop words).  

---

## Future Enhancements  

- Add **sentiment analysis** to evaluate chat moods.  
- Include **media file analysis** (e.g., image, video, or document counts).  
- Develop a **web interface** for better usability.  
- Support for multiple languages in chat analysis.  

---

## Contributing  

Contributions are welcome! Follow these steps to contribute:  

1. Fork the repository.  
2. Create a new branch for your feature or bug fix:  
   ```bash  
   git checkout -b feature-name  
   ```  

3. Commit your changes and push them:  
   ```bash  
   git push origin feature-name  
   ```  

4. Open a pull request with a detailed description of your changes.  

---

## License  

This project is licensed under the **MIT License**. You are free to use it in your own projects.  

---

## Acknowledgments  

- Thanks to Python and its libraries for enabling seamless data analysis.  
- Special thanks to the open-source community for support and inspiration.  
