# Echor Tech Task – Express API

This project is a simple Node.js Express API created as part of the Echor Tech assignment.  
The API provides a single endpoint that transforms an input sentence and returns:

- Total word count  
- List of unique words (lowercased)  
- Reversed sentence  

---

##  Endpoint

### *POST /api/transform*

#### *Request Body*
```json
{
  "sentence": "I love working with JavaScript and Node.js"
}
