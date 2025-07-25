# 🎬 Movie Searcher

A simple and clean React application that allows users to search for movies and view detailed information using the **OMDb API**. It includes a responsive UI and a seamless search experience with no backend dependencies.

---

## 🚀 Live Demo

🔗 [Click here to view the live site](https://movie-searching-app-2911.netlify.app/)

---


## 📦 Features

- 🔍 Real-time movie search using the OMDb API  
- 📄 View detailed info: title, poster, plot, release year, genre, rating  
- 🎨 Responsive and minimalist UI with pure CSS  
- 🧭 React Router for navigation and detail pages  
- ❌ No backend or login system required

---

## 🛠️ Tech Stack

| Area         | Tech                    |
|--------------|-------------------------|
| Framework    | React                   |
| Styling      | CSS                     |
| Routing      | React Router            |
| API          | OMDb API                |
| Build Tool   | Create React App (CRA)  |

---

## 📁 Folder Structure

```
movie-searcher/
├── public/
│   └── index.html
├── src/
│   ├── components/     # SearchBar, MovieCard, etc.
│   ├── pages/          # Home, MovieDetails
│   ├── App.js          # Routing logic
│   ├── index.js        # Entry point
│   └── styles/         # CSS files
└── package.json
```

---

## 🧑‍💻 Getting Started

### 1. Clone the repository
```bash
git clone https://github.com/Deboshruti2911/movie-searcher.git
cd movie-searcher
```

### 2. Install dependencies
```bash
npm install
```

### 3. Set up environment variables
Create a `.env` file in the root:
```env
REACT_APP_OMDB_API_KEY=your_api_key_here
```

You can get a free key from [http://www.omdbapi.com/apikey.aspx](http://www.omdbapi.com/apikey.aspx)

### 4. Run the development server
```bash
npm start
```

Visit: `http://localhost:3000`

---

## 🌱 Future Improvements

- Pagination for large result sets  
- Error handling for invalid or empty searches  
- Improved UI/UX with animations or design frameworks  
- Loading indicators and empty state handling

---

## 🙌 Contributing

Contributions are welcome! To get started:

```bash
git checkout -b feature/YourFeature
git commit -m "Add new feature"
git push origin feature/YourFeature
```

Then open a Pull Request 🚀

---

## 📝 License

This project is licensed under the [MIT License](LICENSE).

---

## 🙏 Acknowledgements

- OMDb API for providing movie data  
- React community for open-source support

---

### 👩‍💻 Made with ❤️ by [Deboshruti2911](https://github.com/Deboshruti2911)
