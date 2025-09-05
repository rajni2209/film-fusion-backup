# 🎬 FilmFusion  

**FilmFusion** is a movie-themed web game where players guess the **Actor, Actress, and Movie** based on hints, options, and a timer. The project includes a secure backend with Spring Boot and an interactive frontend for an engaging user experience.  

---

## 🚀 Features  

- 🎯 Guess the **Actor, Actress, and Movie** from hints  
- ⏱️ **Timer-based challenge** to keep the game engaging  
- ❤️ **Life system** to limit attempts  
- 💡 **Hint system** to help players progress  
- 🔐 **Secure backend APIs** with authentication (Spring Security)  
- 🗄️ **MySQL integration** for storing game data  
- 🌐 Responsive and interactive frontend (HTML, CSS, JS, Bootstrap)  

---

## 🛠️ Tech Stack  

- **Backend**: Spring Boot, REST API, Spring Security  
- **Frontend**: HTML, CSS, JavaScript, Bootstrap  
- **Database**: MySQL  , PostgreSQL
- **Build Tool**: Maven  

---

## 📌 Example API  

### 🎥 Get All Levels  

```http
https://filmfusion-b98i.onrender.com

```
```
{
    "level_no": 1,
    "actor_FirstLetter": "R",
    "actress_FirstLetter": "R",
    "movie_FirstLetter": "A",
    "actor_option": [
      "Ranbir Kapoor",
      "Ranveer Singh",
      "Rajkummar Rao",
      "Riteish Deshmukh",
      "Randeep Hooda",
      "R Madhavan"
    ],
    "actress_option": [
      "Rashmika Mandanna",
      "Rani Mukerji",
      "Radhika Apte",
      "Rakul Preet Singh",
      "Raveena Tandon",
      "Richa Chadha"
    ],
    "movie_option": [
      "Animal",
      "Andhadhun",
      "Article 15",
      "Airlift",
      "Ajab Prem Ki Ghazab Kahani",
      "Antim"
    ],
    "correctActor": "Ranbir Kapoor",
    "correctActress": "Rashmika Mandanna",
    "correctMovie": "Animal",
    "hint": "Ultra-violent father–son saga that dominated 2023 chatter."
  }

```
