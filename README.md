* {
  margin: 0;
  padding: 0;
}

body {
  display: flex;
  justify-content: center;
  align-items: center;
  min-height: 100vh;
  background-color: #f4e4ba;
}

.container {
  background-color: #fff;
  padding: 2rem;
  border-radius: 1rem;
  min-height: 45vh;
  width: 40vh;
}

form {
  margin: 2rem 0 1rem 0;
}

form select,
button,
input {
  width: 100%;
  border: none;
  outline: none;
  border-radius: 0.75rem;
}

form input {
  border: 1px solid lightgray;
  font-size: 1rem;
  height: 3rem;
  padding-left: 0.5rem;
}

.dropdown {
  display: flex;
  justify-content: space-between;
  align-items: center;
  margin-top: 2rem;
}

.dropdown i {
  font-size: 1.5rem;
  margin-top: 1rem;
}

.select-container img {
  max-width: 2rem;
}

.select-container {
  display: flex;
  justify-content: center;
  align-items: center;
  width: 6rem;
  border-radius: 0.5rem;
  border: 1px solid lightgray;
}

.select-container select {
  font-size: 1rem;
  width: auto;
}

.msg {
  margin: 2rem 0 2rem 0;
}

form button {
  height: 3rem;
  background-color: #af4d98;
  color: #fff;
  font-size: 1.15rem;
  cursor: pointer;
}
