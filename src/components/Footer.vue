<template>
  <footer>
      <div class="left">
          <img src="https://i.imgur.com/V6gL51v.png" alt="KhLi logo">
          <h4>© KhLi StoRe</h4>
      </div>
      <list>
          <nav>
          <a href="/">Home</a>
          <a href="/">About</a>
          <a href="#prices">Products</a>
          <a href="https://discord.gg/khli">Contact</a>
      </nav>
      <nav>
          <a href="/order">الصفحه الرئيسيه</a>
          <a href="/">عن خلي ستور</a>
          <a href="#prices">المنتجات</a>
          <a href="https://discord.gg/khli">السوشل ميديا</a>
      </nav>
      </list>
  </footer>
</template>

<style scoped>

list{
  display:flex;
  gap:60px;
}

footer {
  margin-top:200px;
  background-color:#4758b0;
          color: #fff;
          padding: 20px 0;
          text-align: center;
          width: 100%;
          min-height: 40vh;
          display: flex;
          flex-direction:row;
          flex-wrap:wrap;
          gap:80px;
          justify-content:space-around;
          align-items: center;
      }

      nav{
          display:flex;
          flex-direction:column;
          gap:30px;
      }

      footer a {
          color: #fff;
          text-decoration: none;
          margin: 0 10px;
      }

      footer img {
          width:400px;
          height:400px;
          margin-left:10px;
      }

      @media (max-width:768px){
        footer img {
          width:200px;
          height:200px;
        }
      }
</style>
