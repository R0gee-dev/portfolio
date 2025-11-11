* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: "Poppins", sans-serif;
}

body {
  background-color: #0e0e10;
  color: #fff;
  line-height: 1.6;
}

header {
  background: linear-gradient(135deg, #1c1c1f, #26262a);
  padding: 2rem 5%;
  text-align: center;
}

nav {
  display: flex;
  justify-content: space-between;
  align-items: center;
}

nav h1 {
  font-size: 1.8rem;
  color: #00bcd4;
}

nav h1 span {
  color: #fff;
}

nav ul {
  list-style: none;
  display: flex;
  gap: 20px;
}

nav ul li a {
  color: #fff;
  text-decoration: none;
  font-weight: 500;
  transition: color 0.3s;
}

nav ul li a:hover {
  color: #00bcd4;
}

.hero {
  margin-top: 3rem;
}

.hero h2 {
  font-size: 2.5rem;
}

.hero span {
  color: #00bcd4;
}

.hero p {
  margin: 1rem 0 2rem;
  font-size: 1.1rem;
}

.btn {
  background: #00bcd4;
  color: #fff;
  padding: 0.8rem 1.5rem;
  border-radius: 5px;
  text-decoration: none;
  transition: background 0.3s;
}

.btn:hover {
  background: #008c9e;
}

.section {
  padding: 4rem 5%;
  text-align: center;
}

.section h2 {
  font-size: 2rem;
  margin-bottom: 1rem;
  color: #00bcd4;
}

.projects {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: 2rem;
  margin-top: 2rem;
}

.card {
  background: #1c1c1f;
  padding: 2rem;
  border-radius: 10px;
  width: 280px;
  text-align: left;
  transition: transform 0.3s;
}

.card:hover {
  transform: translateY(-5px);
}

.card h3 {
  color: #00bcd4;
}

.card a {
  display: inline-block;
  margin-top: 1rem;
  color: #00bcd4;
  text-decoration: none;
  font-weight: bold;
}

footer {
  text-align: center;
  padding: 2rem 0;
  background: #151517;
  font-size: 0.9rem;
  color: #bbb;
}
