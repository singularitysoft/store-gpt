<body>
  <header>
    <h1>StoreGPT</h1>
  </header>
  <main>
    <form>
      <input type="text" placeholder="Ask me anything">
      <button type="submit">Submit</button>
    </form>
    <div class="response">
      <p>I'm ChatGPT, a language model developed by OpenAI. How can I help you today?</p>
    </div>
  </main>
  <footer>
    <p>Developed by Singularity Software</p>
  </footer>
</body>

<style>
body {
  background-color: #fafafa;
  font-family: sans-serif;
  display: flex;
  flex-direction: column;
  align-items: center;
  height: 100vh;
  margin: 0;
}

header {
  background-color: #333;
  color: #fff;
  padding: 1rem;
  width: 100%;
}

header h1 {
  margin: 0;
  text-align: center;
}

main {
  display: flex;
  flex-direction: column;
  align-items: center;
  background-color: #fff;
  box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
  padding: 2rem;
  width: 80%;
  margin-top: 2rem;
  max-width: 600px;
}

form {
  display: flex;
  align-items: center;
  width: 100%;
  margin-bottom: 2rem;
}

input[type="text"] {
  width: 70%;
  padding: 1rem;
  font-size: 1.2rem;
  border: none;
  border-bottom: 2px solid #333;
}

button[type="submit"] {
  width: 30%;
  padding: 1rem;
  font-size: 1.2rem;
  background-color: #333;
  color: #fff;
  border: none;
  cursor: pointer;
}

.response {
  background-color: #333;
  color: #fff;
  padding: 1rem;
  width: 100%;
  text-align: center;
}

footer {
  background-color: #333;
  color: #fff;
  padding: 1rem;
  width: 100%;
  text-align: center;
  margin-top: 2rem;
}

@media (max-width: 600px) {
  main {
    width: 100%;
  }
}
</style>
