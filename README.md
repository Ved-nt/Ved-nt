<!-- Typing Animation -->
[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&size=26&pause=1000&color=F75C7E&width=600&lines=Hi+%F0%9F%91%8B+I'm+Vedant!;Full-Stack+Web+Developer;B.Tech+Computer+Science+Student;Exploring+React%2C+Node.js%2C+and+AI)](https://git.io/typing-svg)

---

# 👨‍💻 About Me
- 🎓 6th Semester **B.Tech in Computer Science & Engineering** at KIIT University  
- 🌐 **Full-Stack Developer** skilled in React, Node.js, Express, and PostgreSQL  
- 📚 Passionate about **algorithms, AI/ML, and system-level problem solving**  
- 🧘 Currently building a **Meditation & Journal Tracker (AWS deployment)**  
- ✨ Fun Fact: I love reading books and distilling them into actionable insights  

---

# 💻 Code About Me
```js
class Vedant {
  constructor() {
    this.name = "Vedant Sharma";
    this.pronouns = "He/Him";
    this.dateOfBirth = "2003-05-10"; // update if needed
    this.education = "B.Tech CSE, KIIT University (6th Semester)";
    this.languagesKnown = ["English", "Hindi"];
    this.programmingLanguages = ["Java", "JavaScript", "TypeScript", "Python", "C", "SQL"];
    this.skills = ["Web Development", "Algorithms", "Networking", "System Troubleshooting"];
    this.interests = ["AI/ML", "Competitive Coding", "Hackathons", "Computer Vision"];
    this.hobbies = ["Reading books", "Building projects", "Gaming"];
  }

  introduce() {
    return `Hi 👋 I'm ${this.name}, a ${this.education} student passionate about ${this.interests[0]} and ${this.interests[1]}.`;
  }

  listSkills() {
    return `My key skills are: ${this.skills.join(", ")}`;
  }

  randomHobby() {
    return `One of my hobbies is: ${this.hobbies[Math.floor(Math.random() * this.hobbies.length)]}`;
  }
}

const me = new Vedant();
console.log(me.introduce());
console.log(me.listSkills());
console.log(me.randomHobby());

