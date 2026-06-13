# Multi Source AI Sentiment Analysis Pipeline

**Multi Source AI Sentiment Analysis Pipeline** is a full-stack web application that analyzes sentiment from multiple input sources and provides recommendations based on the detected sentiment. The system allows users to submit either plain text or a website URL for analysis. Using Natural Language Processing (NLP) techniques, the application evaluates the sentiment of the content and classifies it as **Positive**, **Negative**, or **Neutral**, helping users determine whether the content is recommended for use or review.

This project demonstrates the integration of modern web technologies, database management, and sentiment analysis techniques into a unified platform.

---

## Features

### Text Sentiment Analysis

* Analyze user-provided text instantly.
* Detect positive, negative, or neutral sentiment.
* Generate recommendation results based on sentiment scores.

### URL-Based Sentiment Analysis

* Extract textual content from a given URL.
* Perform sentiment analysis on the extracted content.
* Provide recommendations on whether the content is suitable or not.

### User-Friendly Interface

* Clean and responsive UI.
* Real-time sentiment analysis results.
* Easy navigation and intuitive user experience.

### Database Integration

* Store analysis history and results.
* Efficient data management using SQLite and Prisma ORM.

### AI-Powered Processing

* Utilizes sentiment analysis algorithms through Sentiment.js.
* Processes text data efficiently and generates meaningful insights.

---

## Technology Stack

### Frontend

* Next.js
* TypeScript
* Tailwind CSS

### Backend

* Node.js

### Database

* SQLite
* Prisma ORM

### NLP & Sentiment Analysis

* Sentiment.js

---

## System Architecture

1. User enters text or URL.
2. Frontend sends request to backend API.
3. Backend processes input.
4. For URLs, content is extracted and cleaned.
5. Sentiment.js analyzes the text.
6. Sentiment score and recommendation are generated.
7. Results are stored in SQLite through Prisma.
8. Response is displayed on the frontend.

---

## Project Structure

```
multi-source-ai-sentiment-analysis-pipeline/
│
├── app/
├── components/
├── prisma/
│   └── schema.prisma
├── public/
├── lib/
├── pages/
├── styles/
├── package.json
├── tsconfig.json
└── README.md
```

---

## Installation

### Clone the Repository

```bash
git clone https://github.com/your-username/multi-source-ai-sentiment-analysis-pipeline.git
```

```bash
cd multi-source-ai-sentiment-analysis-pipeline
```

### Install Dependencies

```bash
npm install
```

---

## Running the Application

### Start Development Server

```bash
npm run dev
```

The application will run on:

```bash
http://localhost:3000
```

---

## Database Management

### Open Prisma Studio

```bash
npm run studio
```

Prisma Studio provides a visual interface to view and manage SQLite database records.

---

## How It Works

### Text Analysis Workflow

1. User enters text.
2. Backend receives the text.
3. Sentiment.js calculates sentiment score.
4. Score is categorized:

   * Positive
   * Neutral
   * Negative
5. Recommendation is generated.
6. Result is displayed and stored.

### URL Analysis Workflow

1. User submits a URL.
2. Backend extracts textual content from the webpage.
3. Extracted text is cleaned and processed.
4. Sentiment analysis is performed.
5. Recommendation is generated.
6. Results are stored and displayed.

---

## Sentiment Classification Logic

| Score Range    | Sentiment | Recommendation    |
| -------------- | --------- | ----------------- |
| Positive Score | Positive  | Recommended       |
| Zero Score     | Neutral   | Review Before Use |
| Negative Score | Negative  | Not Recommended   |

---

## Learning Outcomes

This project helped in understanding:

* Full-stack web development.
* API integration in Next.js.
* Database management using SQLite and Prisma.
* Natural Language Processing concepts.
* Sentiment analysis techniques.
* TypeScript development.
* Modern UI design using Tailwind CSS.
* Backend development with Node.js.

---

## Future Enhancements

* Support for multiple languages.
* AI-based advanced sentiment models.
* User authentication and authorization.
* Dashboard for historical analytics.
* Data visualization and charts.
* Social media sentiment analysis.
* Real-time monitoring of web content.

---

## Screenshots

* Home Page
* Text Analysis Page
* URL Analysis Page
* Sentiment Results
* Prisma Studio Database View

---

## Author

**Bhavana**

Mini Project – Multi Source AI Sentiment Analysis Pipeline

---

## License

This project is developed for educational and academic purposes.

