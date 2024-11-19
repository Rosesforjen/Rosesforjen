- 👋 Hi, I’m @Rosesforjen
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!---
Rosesforjen/Rosesforjen is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
function scrollToSection(sectionId) {
  document.getElementById(sectionId).scrollIntoView({ behavior: 'smooth' });
}

document.getElementById('customizeForm').addEventListener('submit', (e) => {
  e.preventDefault();
  alert('Thank you! Your custom rose design has been submitted.');
});
