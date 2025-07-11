# 🚀 CrayFish0 Personal API

A real-time API about me! Access my current status, projects, and stats.

## Endpoints

### Base URL
```
https://raw.githubusercontent.com/CrayFish0/CrayFish0/main/api.json
```

### Example Response
```json
{
  "developer": {
    "name": "CrayFish0",
    "status": "coding",
    "current_focus": "Flutter Development",
    "coffee_cups_today": 3,
    "mood": "🚀",
    "availability": "open_to_opportunities"
  }
}
```

## Usage Examples

### JavaScript
```javascript
fetch('https://raw.githubusercontent.com/CrayFish0/CrayFish0/main/api.json')
  .then(response => response.json())
  .then(data => console.log(data.developer.mood));
```

### Python
```python
import requests

response = requests.get('https://raw.githubusercontent.com/CrayFish0/CrayFish0/main/api.json')
data = response.json()
print(f"Current mood: {data['developer']['mood']}")
```

### cURL
```bash
curl -s https://raw.githubusercontent.com/CrayFish0/CrayFish0/main/api.json | jq '.developer.status'
```

---
*Updated automatically every 4 hours via GitHub Actions* ⚡
