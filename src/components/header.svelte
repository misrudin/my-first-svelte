<script>
  export let title;
</script>

<style>
  nav {
    background-color: #fff;
    box-shadow: 1px -1px 10px rgba(0, 0, 0, 0.25);
    position: fixed;
    top: 0;
    width: 100vw;
    height: 70px;
    display: flex;
    padding: 0px 20px;
    align-items: center;
    justify-content: space-between;
  }
  h2 {
    font-weight: bold;
    color: rgb(11, 70, 107);
    text-transform: uppercase;
  }
  ul {
    list-style: none;
    padding: 0;
    margin: 0;
    display: flex;
    margin-right: 50px;
  }
  li {
    margin-left: 10px;
  }
</style>

<nav>
  <h2>{title}</h2>
  <ul>
    <li>
      <a href="/">Home</a>
    </li>
    <li>
      <a href="/">Home</a>
    </li>
    <li>
      <a href="/">Home</a>
    </li>
  </ul>
</nav>
