<p>
 <h1>Sprawozdanie z laboratorium 13B - zadanie 13.1</h1><br>
 
 Pobrane obrazy to Httpd Apache w dwóch różnych wersjach:
 <img src="img/1.png" /><br>
 Wypchnięcie obrazów pod inną nazwą do swojego repozytorium [DockerHub](https://hub.docker.com/r/ek00/httpd1/tags):
  <img src="img/2.png" />
  <img src="img/3.png" /><br>
  Uruchomiony obiekt Deployment z 3 podami w pierwszej wersji obrazu <b>(httpd-deployment1.yml)</b><br>
    <img src="img/4.png" /><br>
  Aplikacja przeskalowana do pracy na 6 podach <b>(httpd-deployment2.yml)</b><br>
  <img src="img/6.png" /><br>
  Aplikacja zaktualizowana do nowej wersji, nadal na 6 podach <b>(httpd-deployment3.yml)</b><br>
    <img src="img/7.png" /><br>
  Aplikacji zostały przydzielone nowe zasoby <b>(httpd-deployment4.yml)</b><br>
   <img src="img/8.png" /><br>
   <img src="img/9.png" /><br>
   Downgrade aplikacji do 1 wersji:<br>
   <img src="img/10.png" /><br>
   <img src="img/11.png" /><br>


</p>

