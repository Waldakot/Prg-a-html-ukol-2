<h1> Prg-a-html-ukol </h1>

<h2> Prg  </h2> 
<h3> na programování jsem měl za úkol udělat generátor náhodných čísel v určitém rozsahu (vybral jsem si od 1 do 10). udělal jsem rovnou abysemi 10 náhodných čísel vypsalo pod sebou.  </h3>  
<h4> import java.lang.Math; 
  
class podsebou { 
  
     
    public static void main(String args[]) 
    { 
        
        int max = 10; 
        int min = 1; 
        int rozsah = max - min + 1; 
       
	
		for (int i = 0; i < 10; i++) { 
			int rand = (int)(Math.random() * rozsah) + min; 

		
			System.out.println(rand); 
		} 
	} 
} 

  </h4>  
  <h2> HTML</h2>  
  <h3> Na html jsem měl udělat webovou stránku na téma herec. dělal jsem průběžně screenshoty a měnil postupy a programy v kterým jsem to psal. Téma jsem měl:Herec. Bohužel poslední program v kterém jsem to play nebyl úplně nejlepší jelikož by to normálně nefungovalo ale to jsem zjistil už pozdě. takže přikládám url stránky na kterém je moje stránka i s kódem.https://codepen.io/Waldakot/pen/JjovQxM . Původně jsem chtěl udělat, že po kliknutí na obrázek se objevý ve stín přes obrázek s textem o hercovi, ale bohužel to nějak nevyšlo zkoušel jsem to dělat přes opacity.<h3>
