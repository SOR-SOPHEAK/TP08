<template>
    <div class="register">
      <form action="/home">
        <div class="header">
          <h1>Sign Up</h1>
          <p>Pelase fill in this form to create an account.</p>
        </div>
        <div class="inputFill">
          <label for="email">Email</label>
          <input type="email" name="email" id="email" placeholder="Enter Email">
        </div>
        <div class="inputFill">
          <label for="username">Username</label>
          <input type="text" name="username" id="username" placeholder="Username">
        </div>
        <div class="inputFill">
          <label for="firstname">First Name</label>
          <input type="text" name="firstname" id="firstname" placeholder="First Name">
        </div>
        <div class="inputFill">
          <label for="lastname">Last Name</label>
          <input type="text" name="lastname" id="lastname" placeholder="Last name">
        </div>
        <div class="inputFill">
          <label for="password">Password</label>
          <input type="password" name="password" id="password" placeholder="Create your Password">
        </div>
        <div class="text">
          <p>By create an account you agree to our <a href="#">Terms & Privacy</a></p>
        </div>
        <button>Sign Up</button>
    </form>
    </div>
  </template>
  
  <style>
  *{
    margin: 0px;
    padding: 0px;
    font-family: Merriweather,sans-serif;
  }
  form {
    border: 3px solid #f1f1f1;
    border-radius: 5px;
    margin: 10px;
    padding: 20px;
  }
  .header{
    border-bottom: 1px solid rgb(151, 150, 150);
  }
  input{
    width: 100%;
    padding: 12px 20px;
    margin: 8px 0;
    display: inline-block;
    border: 1px solid #ccc;
    box-sizing: border-box;
    border: none;
    background-color: #ccc;
  }
  </style>