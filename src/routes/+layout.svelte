<style>
  .nav {
    display: flex;
    background-color: #333;
    padding: 10px 0;
    justify-content: space-around;
  }

  .nav a {
    color: #fff;
    text-decoration: none;
    margin-right: 15px;
  }
</style>

<div class="nav">
  <a href="/">Home</a>
  <a href="/about">About</a>
  <a href="/foods">Food</a>
</div>

<slot></slot>

