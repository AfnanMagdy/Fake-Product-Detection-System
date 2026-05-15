# Product Review Sentiment Analysis (Text + Image)

##  Project Idea
This project aims to predict whether a product review is **positive or negative** using both:
- Review text
- Product image

Unlike traditional sentiment analysis, this project combines **text and visual information** to improve prediction accuracy.

Example:
A review like "looks good but broke quickly" may appear positive in text, but combining it with product image can improve understanding.

---

##  Objectives
- Build a multimodal model using text + image
- Improve sentiment classification accuracy
- Compare different approaches (text-only vs image-only vs combined)

---

##  Data Collection
We will collect:
- Product reviews (text)
- Product images

###  Sources:
- Amazon
- Jumia
- Noon 

###  Tools:
- BeautifulSoup (for static pages)
- Selenium (for dynamic content)

---

##  Project Pipeline

### 1. Data Collection & Cleaning
- Scrape product pages
- Extract:
  - Review text
  - Product images
- Clean text:
  - Remove stopwords
  - Remove emojis and noise

---

### 2. Text Model
- Transformer
- LSTM
---

### 3. Image Model
  - ResNet18
---

### 4. Fusion Model
- Combine text + image features
- Feed into classifier (MLP)

---

### 5. Evaluation
Compare:
- Text-only model
- Image-only model
- Combined model

Metrics:
- Accuracy
- F1-score

---

##  Team Members
- Afnan
- Jana
- Sama
- Loay
- Omar

---

##  Project Status
Proposal Stage
