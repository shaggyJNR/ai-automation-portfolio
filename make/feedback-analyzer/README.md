# Google Sheets Integration

**Problem:** Customer reviews pile up unread, so businesses can't tell what customers are happy or upset about.

**Tools used:** Make, Google Forms, Google Sheets, Google Gemini

**How it works:**
- Trigger: A customer submits the feedback form, and the response lands as a new row in Google Sheets.
- Step 2: Make picks up the new row, and AI reads the review, labels its sentiment and topic, and writes a one-line summary.
- Result: The same row is updated automatically with Sentiment, Topic, Summary, and a Posted status, so every review is sorted without anyone reading it by hand.
