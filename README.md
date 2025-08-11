<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>DRUMMACHINE_WEBAPI_MASTERKLAD</title>
<meta name="viewport" content="width=device-width,initial-scale=1">
<style>
  :root{
    --bg:#0d0d0d;
    --fg:#e5e5e5;
    --accent:#00ffcc;
    --hover:#ff0066;
  }
  *{margin:0;padding:0;box-sizing:border-box}
  body{
    height:100vh;
    display:flex;
    flex-direction:column;
    justify-content:center;
    align-items:center;
    background:var(--bg);
    color:var(--fg);
    font-family:Helvetica,Arial,sans-serif;
    text-align:center;
  }
  h1{
    font-size:1.4rem;
    font-weight:400;
    letter-spacing:.1em;
    margin-bottom:1rem;
  }
  p{
    max-width:22rem;
    font-size:.8rem;
    line-height:1.4;
    margin-bottom:2.5rem;
    opacity:.6;
  }
  nav{display:flex;flex-direction:column;gap:.6rem}
  a{
    color:var(--fg);
    text-decoration:none;
    font-size:.9rem;
    letter-spacing:.05em;
    padding:.8rem 2.2rem;
    border:1px solid var(--accent);
    border-radius:2rem;
    transition:all .3s ease;
    position:relative;
    overflow:hidden;
  }
  a::after{
    content:'';
    position:absolute;
    top:0;
    left:-100%;
    width:100%;
    height:100%;
    background:linear-gradient(90deg,transparent,var(--hover),transparent);
    transition:left .4s ease;
  }
  a:hover{
    color:var(--bg);
    border-color:var(--hover);
  }
  a:hover::after{left:100%}
  a:active{transform:scale(.95)}
</style>
</head>
<body>

  <h1># DRUMMACHINE_WEBAPI_MASTERKLAD</h1>
  <p>drummachines i make for fun in html5 with robots for robot fm music bleep bleep techno</p>

  <nav>
    <a href="https://oswild666.github.io/DRUMMACHINE_WEBAPI_MASTERKLAD/drumboss-azerbaijan-riddim.html">AZERBAIJAN RIDDIM</a>
    <a href="https://oswild666.github.io/DRUMMACHINE_WEBAPI_MASTERKLAD/drumboss-necrofuturist.html">NECROFUTURIST</a>
    <a href="https://oswild666.github.io/DRUMMACHINE_WEBAPI_MASTERKLAD/drumboss premium.html">PREMIUM</a>
    <a href="https://oswild666.github.io/DRUMMACHINE_WEBAPI_MASTERKLAD/drumboss ipadpro version v1.2.html">iPad Pro v1.2</a>
  </nav>

</body>
</html>
