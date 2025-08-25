body {
  font-family: Impact, Haettenschweiler, 'Arial Narrow Bold', sans-serif;
  background: #87ceeb; /* Sky blue */
  margin: 0;
  padding: 20px;
  text-align: center;
  color: #000; /* Black text */
}
h1 {
  color: #ffd700; /* Gold */
  text-shadow: 2px 2px 0 #000;
}
#cards {
  display: flex;
  justify-content: center;
  gap: 30px;
  flex-wrap: wrap;
}
.card {
  background: #000; /* Black */
  border-radius: 8px;
  box-shadow: 0 2px 8px #ffd700; /* Gold shadow */
  padding: 20px;
  width: 250px;
  color: #ffd700; /* Gold text */
  border: 2px solid #87ceeb; /* Sky blue border */
}
.card-img {
  width: 100%;
  height: 150px;
  object-fit: cover;
  border-radius: 6px;
  border: 2px solid #ffd700; /* Gold border */
  background: #87ceeb; /* Sky blue background */
}
form {
  margin-top: 10px;
}
input {
  width: 90%;
  margin: 5px 0;
  padding: 8px;
  border-radius: 4px;
  border: 2px solid #ffd700;
  background: #87ceeb;
  color: #000;
  font-family: Impact, Haettenschweiler, 'Arial Narrow Bold', sans-serif;
}
button {
  padding: 8px 16px;
  background: #ffd700; /* Gold */
  color: #000; /* Black */
  border: none;
  border-radius: 4px;
  cursor: pointer;
  font-family: Impact, Haettenschweiler, 'Arial Narrow Bold', sans-serif;
  box-shadow: 0 2px 4px #000; /* Black shadow */
}
button:hover {
  background: #000;
  color: #ffd700;
  border: 2px solid #ffd700;
}
