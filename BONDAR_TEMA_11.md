BONDAR IRINA

GRUPA 3131A

LABORATOR 11 - REZOLVARE

Răspundeți la următoarele întrebări:
• Care este rolul comenzilor GL.Push() și GL. Pop()? De ce este necesară utilizarea lor?

R: GL.Push() si GL.Pop() sunt utilizate pentru a gestiona stiva de matrice în OpenGL. Atunci când se utilizează GL.Push(), starea matricei curente este salvată pe stivă. Acest lucru permite apoi aplicarea unor transformări specifice fără a afecta starea matricei salvate.
GL.Pop() este folosit pentru a scoate matricea curentă de pe stivă, revenind astfel la starea salvată anterior cu GL.Push().Aceste comenzi sunt utile atunci când dorim să aplicăm transformări doar asupra unor anumite obiecte fără a afecta întreaga scenă. 


• Explicați efectul rulării metodelor GL.Rotate(), GL.Translate() și GL.Scale(). Furnizați câte un exemplu comentat!

R: GL.Rotate() -> Roteste sistemul de coordonate curent în jurul originii cu un unghi specific pe axa dată de vectorul (x, y, z).
   GL.Translate() -> Translează sistemul de coordonate curent cu o anumită valoare pe fiecare axă.
   GL.Scale() -> Scalarea obiectelor pe fiecare axă conform valorilor date

EXEMPLU :   
	  GL.Rotate(45.0f, 0.0f, 1.0f, 0.0f);  // Rotim sistemul de coordonate cu 45 de grade în jurul axei y
				// Desenează obiectele în sistemul de coordonate rotit




