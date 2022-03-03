# Cvičení 4 - Řidiči

Jako výchozí bod pro tento příklad použij hotový kód z předchozího Cvičení 3 - Kontakty. Pokud jsi cvičení zdárně dokončila, měla bys mít aplikaci, která zobrazuje kontakty podle props předaných do komponenty Contact.

1. Uprav komponentu `Contact` tak, aby podle věku osoby zobrazovala na konci ještě odstavec s textem:

	```html
	<p class="contact__can-drive">je dospělá, může řídit</p>
	```

	Nebo v případě, že je osobě méně než 18 let, tak:
	```html
	<p class="contact__can-drive">není dospělá, nemůže řídit</p>
	```

	*Poznámka: Nebudeme si zatím komplikovat život tím, že nestačí být jen dospělý, ale člověk musí mít i řidičský průkaz.*

1. Vylepši komponentu tak, že pod text umístíš ještě vhodnou ikonu:

	![Může řídit](can-drive.png) ![Nemůže řídit](cant-drive.png)

	Obrázky si můžeš stáhnout a zkopírovat do projektu nebo je do stránky odkázat přímo z internetu pomocí následujících adres:
	```
	https://raw.githubusercontent.com/Czechitas-React-podklady/React-lekce-03/main/cviceni-04/can-drive.png
	```
	```
	https://raw.githubusercontent.com/Czechitas-React-podklady/React-lekce-03/main/cviceni-04/cant-drive.png
	```

1. Pokud se ti chce, můžeš do komponenty přidat další prop nazvanou třeba `driver`, která bude přijímat hodnotu `true` nebo `false` a p59slu3n7 text a ikonka se budou zobrazovat podlo toho a ne podle věku.