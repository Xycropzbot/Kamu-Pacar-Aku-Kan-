<html>
  <head>
  <title> INI JUDUL DI TAB BROWSER </title>
  
  <script type="text/javascript">
  flag=1
  function f1()
  {
      alert("Thanks Udah pilih Jawaban YA")
  }
  function f()
  {
      if(flag==1)
          {
              Bn.style.top=400
              Bn.style.left=300
              flag=2
          }
      else if(flag==2)
          {
              Bn.style.top=400
              Bn.style.left=50
              flag=3
          }
      else if(flag==3)
          {
              Bn.style.top=370
              Bn.style.left=166
              flag=1
          }
  }
  </script>
  
  </head>
  <body>
  <h1> Denn Wibu <h1>
  <img alt="Denn Wibu" src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQK6l-UM9bF_mhtNmhtLFZuglymg8qD0RGTvg&usqp=CAU"height="200" />
  <h1 style="#">Kamu Pacar Aku Kan??</h1>
  <div id="By" style="position:absolute; left:64px; top:370px; width:210px;
  height:210px;">
  <input type="button" value=" YA " onClick="f1()" />
  </div>
  <div ID="Bn" style="position:absolute; left:166px; top:370px; width:210px; height:210px;">
  <input type="button" value=" BUKAN " onMouseOver="f()" />
  </div>
  
  </body>
  </html>
