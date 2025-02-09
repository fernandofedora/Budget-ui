# Budget-ui
A web-based UI for managing budgets and expenses. Built with HTML, Bootstrap, and JavaScript, it connects to a RESTful API to perform CRUD operations.
## ✨ Features
- **Create Budgets**: Define budgets with a name and initial amount.
- **Track Expenses**: Add and manage expenses for each budget.
- **Real-Time Progress Bar**: Visual representation of remaining budget.
- **Dynamic UI**: Fetch and display budget data from API.
- **Delete Budgets**: Remove budgets along with associated expenses.

## 🛠️ Technologies
- **Frontend**: HTML, CSS, JavaScript
- **Framework**: Bootstrap 5
- **API Integration**: Fetch API for communication with backend

## 📂 File Structure
```
📁 budget-manager-ui
 ├── 📄 index.html  # Main UI file
 ├── 📄 style.css   # Custom styles (if any)
 ├── 📄 script.js   # Handles API communication and DOM updates
```

## 🚀 Setup and Usage

### Prerequisites
- A running instance of the Budget Manager API.
- A modern web browser.

### Steps to Run
1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/budget-manager-ui.git
   cd budget-manager-ui
   ```
2. **Open `index.html` in a browser**.
3. **Ensure the API is running** at `http://localhost:3000` (or configure `API_URL` inside `script.js`).
4. **Use the UI** to create budgets and expenses dynamically.

## 🔧 Configuration
Modify `API_URL` in `index.html`:
```js
const API_URL = 'http://localhost:3000';
```
Change this if your API is hosted elsewhere.

## 🖼️ Screenshots
### Main UI
![Budget Manager UI](https://via.placeholder.com/800x400)

## 🤝 Contributing
1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature/new-feature
   ```
3. Commit changes:
   ```bash
   git commit -m 'Add new feature'
   ```
4. Push to branch:
   ```bash
   git push origin feature/new-feature
   ```
5. Open a Pull Request.

## 📄 License
MIT License - See LICENSE for details.
