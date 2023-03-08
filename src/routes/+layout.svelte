<nav>
  <a href="/">Visits</a>
  <a href="/products">Products</a>
</nav>

<slot></slot>

<style>
  nav {
    background-color: #D9D9D9;
    box-sizing: content-box;
    display: flex;
    width: 100%;
  }

  nav a {
    font-size: 16px;
    line-height: 40px;
    padding: 0 16px;
  }
</style>