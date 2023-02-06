<body>
  <header>
    <h1>Chat App</h1>
  </header>
  <main>
    <div class="left-sidebar">
      <button class="new-chat-button">New Chat</button>
      <ul class="conversations">
        <li>Conversation 1</li>
        <li>Conversation 2</li>
        <li>Conversation 3</li>
      </ul>
      <ul class="options">
        <li>Clear Conversations</li>
        <li>Dark Mode</li>
        <li>Log Out</li>
      </ul>
    </div>
    <div class="right-sidebar">
      <form action="">
        <input type="text" placeholder="Type a message...">
        <button type="submit">Send</button>
      </form>
    </div>
  </main>
  <footer>
    &copy; Chat App 2023
  </footer>
</body>

<style>
  body {
    background-color: #fafafa;
    font-family: sans-serif;
    display: flex;
    flex-direction: column;
    align-items: center;
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
    align-items: center;
    background-color: #fff;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
    padding: 2rem;
    width: 100%;
    margin-top: 2rem;
  }
  
  .left-sidebar {
    width: 20%;
    background-color: #e0e0e0;
    padding: 1rem;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
    margin-right: 2rem;
  }
  
  .new-chat-button {
    width: 100%;
    padding: 1rem;
    font-size: 1.2rem;
    background-color: #333;
    color: #fff;
    border: none;
    cursor: pointer;
    margin-bottom: 2rem;
  }
  
  .conversations, .options {
    list-style: none;
    padding: 0;
    margin: 0;
  }
  
  .conversations li, .options li {
    padding: 1rem;
    border-bottom: 1px solid #333;
  }
  
  .right-sidebar {
    width: 80%;
  }
  
  form {
    display: flex;
    flex-direction: column;
    align-items: center;
    width: 100%;
    margin-bottom: 2rem;
  }
  
  input[type="text"] {
    width: 100%;
  }   
</style>

<!-- 
@media (max-width: 600px) {
  main {
    width: 100%;
  }
}

@media (max-width: 390px) {
  main {
    width: 100%;
  }
  
  form {
    width: 90%;
  }
} -->
