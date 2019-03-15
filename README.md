# Agentie-Imobiliara

Acest program citeste de la tastatura datele referitoare la un anumit numar de locuinte si le afiseaza.

PROGRAMUL A FOST FACUT IN CONFORMITATE CU CERINTELE:

Se doreste implementarea unei aplicatii care sa permita gestionarea clientilor si a proprietatilor imobiliare in cadrul unei agentii imobiliare nou infiintate. Pentru fiecare locuinta se cunoaste numele clientului care o inchiriaza, suprafata utila si discount-ul (0-10%). La apartamente se cunoaste etajul, iar la case se stie cati metri patrati are curtea, cate etaje are casa si care este suprafata utila pe fiecare etaj in parte. 
Evident, calculul chiriei se face diferit. Daca la apartamente se considera doar formula data de pretul de inchiriere pe metru patrat * suprafata utila, avand grija sa se aplice discount unde este cazul, la casa, se adauga, indiferent de discount, pretul pe metru patrat de curte * suprafata acesteia.
Cerinta suplimentara: 
-	Sa se construiasca clasa template Gestiune, continand un vector de pointeri la obiecte de tip Locuinta alocat dinamic, unde indexul fiecarei locuinte este incrementat automat la adaugarea uneia noi, prin supraincarcarea operatorului +=. Clasa Gestiune trebuie sa stocheze numarul de apartamente sau case, fiecare cu chiria lunara aferenta. 
-	Sa se construiasca o specializare pentru tipul char* care sa stocheze numarul de clienti, impreuna cu numele acestora.
