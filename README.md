# Smart Shop AI
### 🛍️ AI-Powered E-Commerce Recommendation System




![](https://i.ibb.co/QvPCNvZ/Untitled-diagram-2024-10-27-202649.png)

The system is built using a modern tech stack:

### ⚙️ Backend 
- 🚀 FastAPI for the REST API  
- 🗄️ SQLAlchemy for database management  
- 🧠 Python-based ML recommendation engine  
- 🗃️ PostgreSQL database  

### 🎨 Frontend
- ⚛️ Next.js for the React framework  
- 🔧 TypeScript for type safety  
- 🎨 TailwindCSS for styling  
- 🔄 Real-time state management  

For detailed architectural information and implementation, check out our [technical blog post](https://medium.com/@sametarda.dev/building-an-ai-powered-e-commerce-recommendation-system-a-comprehensive-overview-c89613a0777d).

## 🚀 Getting Started

### 🛠️ Installation

1. **Clone the repository**  
```bash
git clone https://github.com/ardasamett/SmartShop-AI.git
cd SmartShop-AI
```

2. **Backend Setup**  
```bash
python -m venv venv
source venv/bin/activate  # On Windows: .\venv\Scripts\activate
pip install -r requirements.txt
```

3. **Frontend Setup**  
```bash
cd UI
npm install
```

4. **Environment Configuration**  
Create `.env` files for both backend and frontend:

`.env`:
```env
DATABASE_URL=sqlite:///./ecommerce.db
GOOGLE_API_KEY=your_gemini_api_key
MODEL_NAME=gemini-1.5-flash 
```

### 🚦 Running the Application

1. **Start the Backend Server**  
```bash
uvicorn app.main:app --reload
```
API will be available at `http://localhost:8000`.

2. **Start the Frontend Development Server**  
```bash
cd UI
npm run dev
```
Frontend will be available at `http://localhost:3000`.

3. **Generate Test Data**  
Before using the application, generate test data by visiting:
```
http://localhost:8000/debug/generate-data
```
This will return a test user ID to test the application.


## 🤝 Contributing

