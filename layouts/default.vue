<template>
  <div>
    <nav class="navbar navbar-expand-md border-bottom shadow-sm">
      <div class="container">
        <a href="/" class="navbar-brand"><b>日新研修</b></a>
        <button class="navbar-toggler" tye="button" data-toggle="collapse" data-target="#navbarCollapse" aria-controls="navbarCollapse">
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarCollapse">
          <ul class="navbar-nav mr-auto">
            <li class="navbar-item active">
              <a href="/" class="nav-link">ホーム</a>
            </li>
          </ul>
          <ul class="navbar-nav text-light">
            <li class="navbar-item active">
              <a href="#" class="btn btn-outline-primary">ログイン</a>
            </li>
          </ul>
        </div>
      </div>
    </nav>
    <main class="container mt-4">
      <nuxt/>
    </main>
    <footer class="mt-4 pt-4 text-center">
      <div class="container border-top pt-3">
        Copyright © 2018 · <a href="http://www.nissinjp.com/" target="_blank"><b>NisSin 日新株式会社</b></a>
      </div>
    </footer>
  </div>
</template>

<style>
html
{
  font-family: "Source Sans Pro", -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif;
  font-size: 16px;
  word-spacing: 1px;
  -ms-text-size-adjust: 100%;
  -webkit-text-size-adjust: 100%;
  -moz-osx-font-smoothing: grayscale;
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}
*, *:before, *:after
{
  box-sizing: border-box;
  margin: 0;
}
.button--green
{
  display: inline-block;
  border-radius: 4px;
  border: 1px solid #3b8070;
  color: #3b8070;
  text-decoration: none;
  padding: 10px 30px;
}
.button--green:hover
{
  color: #fff;
  background-color: #3b8070;
}
.button--grey
{
  display: inline-block;
  border-radius: 4px;
  border: 1px solid #35495e;
  color: #35495e;
  text-decoration: none;
  padding: 10px 30px;
  margin-left: 15px;
}
.button--grey:hover
{
  color: #fff;
  background-color: #35495e;
}
</style>
