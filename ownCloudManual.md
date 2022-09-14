<a style="font-size:14px" href="https://tpchespa.github.io">Back</a>

<img width="30%" height="30%" src="/docs/assets/images/logoOwnClod.svg"/><br/>

IT założyło nam wszystkim konta na ownCloudzie. Zastąpi przede wszystkim wetransfera do wysłania plików i może posłużyć jako wspólna baza do niektórych materiałów.<br/><br/>

Adres do serwisu:<br/>

<a href="https://chesnet.chespa.eu/">https://chesnet.chespa.eu/</a><br/>

Dane do logowania są takie same jak do domeny. Czyli login i hasło jest takie same jak do Waszego konta na komputerze, którego używacie na co dzień:
<br/><br/>
<img width="50%" height="50%" src="/docs/assets/images/Login.png"/><br/>
<img width="50%" height="50%" src="/docs/assets/images/Login2.png"/><br/><br/>

Żeby wysłać pliki, trzeba przeciągnąć je na główny ekran z listą, na której już znajduje się przykładowy plik (ownCloud Manual.pdf):<br/>
<img src="/docs/assets/images/FolderList.png"/><br/>
<video width="680px" height="450px" autoplay loop muted> <source src="/docs/assets/images/Drag&Drop.mov"></video>

Klikamy później w przesłany plik. Otworzy się panel z prawej strony:<br/>
<img src="/docs/assets/images/NewFile1.png"/><br/><br/>

Następnie klik w zakładkę “Sharing”:<br/>
<img src="/docs/assets/images/NewFile2.png"/><br/><br/>

Kilk w “Public Links”:<br/>
<img src="/docs/assets/images/NewFile2.png"/><br/><br/>

Następnie:<br/>
<img src="/docs/assets/images/NewFile3.png"/><br/><br/>
<img src="/docs/assets/images/NewFile4.png"/><br/><br/>

Otworzy się nowe okienko, w którym wpisujemy nazwę przesyłanego pliku i adresy, na które ma być wysłany publiczny link: <br/>
<img src="/docs/assets/images/LinkShare.png"/><br/><br/>

<video autoplay loop muted> <source src="/docs/assets/images/EmailInput.mov"></video>

Po wpisaniu adresu klikamy dla potwierdzenia w wyświetlony adres jeszcze raz (poniżej pola do wpisania). <br/>
Na końcu możemy zaznaczyć opcję, żeby wysłać kopię maila dla siebie.<br/>
Po kliknięciu “Share”, system wyśle maila na wpisane adresy. <br/><br/>
<img src="/docs/assets/images/LinkShare3.png"/><br/>
<button onclick="topFunction()" id="myBtn" title="Go to top">Top</button> 
 
 
// Get the button:
let mybutton = document.getElementById("myBtn");

// When the user scrolls down 20px from the top of the document, show the button
window.onscroll = function() {scrollFunction()};

function scrollFunction() {
  if (document.body.scrollTop > 20 || document.documentElement.scrollTop > 20) {
    mybutton.style.display = "block";
  } else {
    mybutton.style.display = "none";
  }
}

// When the user clicks on the button, scroll to the top of the document
function topFunction() {
  document.body.scrollTop = 0; // For Safari
  document.documentElement.scrollTop = 0; // For Chrome, Firefox, IE and Opera
}  
