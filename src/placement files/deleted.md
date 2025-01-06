
nav {
  padding: 10px;
  display: flex;
  justify-content: space-between;
  align-items: center;
  background-color: #333;
}
#form-content {
  display: flex;
  flex-wrap: nowrap;
  margin-left: 700px;
  flex-direction: column;
  align-items: center;
  background: rgba(255, 255, 255, 0.2); 
  border: 1px solid rgba(255, 255, 255, 0.3); 
  backdrop-filter: blur(10px);
  -webkit-backdrop-filter: blur(10px);
  border-radius: 20px;
  padding: 20px;
  max-width: 400px;
  width: 90%;
  box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1); 
}
label {
  color: white;
  margin-bottom: 5px;
  text-align: left;
  width: 100%;
}
input {
  width: 100%;
  padding: 10px;
  margin-bottom: 15px;
  border-radius: 5px;
  border: 1px solid rgba(255, 255, 255, 0.3);
  background: rgba(255, 255, 255, 0.5);
  color: #000;
}
#h{
  margin-left: 700px;;
}
#btn{
  margin-left: 700px;
}
button {
  text-align: center;
  background-color: rgba(255, 255, 255, 0.2);
  color: rgb(93, 0, 255);
  padding: 12px;
  margin: 10px;
  border: none;
  border-radius: 10px;
  cursor: pointer;
  backdrop-filter: blur(5px);
}
button:hover {
  background-color: rgba(255, 255, 255, 0.4);
}
.gender-container {
  display: flex;
  gap: 10px; 
  margin: 10px 0;
  margin-left: -50px;
}
.gender-container label {
  margin: 0 5px;
  color: white;
}
.gender-container input[type="radio"] {
  margin: 0 5px;
}
.hash {
  list-style: none; 
  padding-left: 1.5em;
}
.hash li::before {
  content: "#"; 
  margin-right: 0.5em;
  color: inherit; 
}