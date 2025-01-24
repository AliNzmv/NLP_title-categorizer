# 🛒 Title Categorizer for Product Listings 🧠✨

This project is an **NLP-based Title Categorizer** that classifies product titles into specific categories. The model is trained and validated using the dataset from [torob.com](https://torob.com), a leading marketplace.

---

## 📂 Dataset Description
The dataset includes product titles (in **Persian**) and corresponding categories. For example:

| **Feature**          | **Description**                                     |
|-----------------------|-----------------------------------------------------|
| `name1`              | Main product title (in Persian)                     |
| `name2`              | Alternative product title (in English)              |
| `cat_id`             | Category ID for the product                         |

### 🗂️ Categories
Here is a sample mapping of `cat_id` to product categories:

| **Category ID** | **Category Title**                    |
|------------------|--------------------------------------|
| 0                | Men's Cologne & Perfume             |
| 1                | Women's Sweaters & Hoodies          |
| 2                | Analog & Digital Watches            |
| 3                | Fitness & Sports Watches            |
| 4                | Tools & Equipment                   |
| 5                | Women's Summer Sweaters & Hoodies   |
| 6                | Men's Summer Cologne & Perfume      |
| 7                | Men's Casual Sweaters & Hoodies     |
| 8                | Sports & Travel Bags                |
| 9                | Backpacks & Travel Gear             |
| 10               | Trolleys & Rolling Luggage          |

---

## 🛠️ Project Features
1. **Model Training**:  
   Train an NLP model to classify titles accurately into predefined categories.  
2. **Validation**:  
   Ensure the model generalizes using a separate validation dataset.  
3. **Real-World Application**:  
   Categorize new product listings from **torob.com** automatically!  

---

## 🚀 How to Run Locally
Clone the repository and start working:

```bash
# Step 1: Clone the repo
git clone https://github.com/your-username/title-categorizer.git

# Step 2: Navigate to the project directory
cd title-categorizer

# Step 3: Install dependencies
pip install -r requirements.txt

# Step 4: Train the model
python train_model.py --dataset torob_data.csv

# Step 5: Test the categorizer
python test_model.py --input "کاپشن مردانه زمستانی"
```

---

## 💡 Key Insights
- **Persian Text Preprocessing**: Customized tokenization for Persian script.  
- **Categorization Accuracy**: Achieved >90% accuracy during validation.  
- **Scalability**: The model can handle additional categories seamlessly.

---

## 🤝 Contributing
Contributions are welcome! Feel free to fork the project and submit a PR. 😊

---

## 📜 License
This project is licensed under the [MIT License](LICENSE).

---

## 🌟 Acknowledgments
Special thanks to **torob.com** and  **quera.org** for providing the dataset and inspiration for this project! 🙌
```

