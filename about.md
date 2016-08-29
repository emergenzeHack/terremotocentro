---
layout: page
title: About
titolo: About | Terremoto Centro Italia
permalink: /about/
---

* [Il Progetto](#il-progetto)
* [Credits](#credits)
* [Contatti](#contatti)
* [Press](#press)

### Il Progetto


Questo è un progetto non profit, organizzato interamente da volontari. È nato per condividere informazioni utili e 
verificate sul Terremoto del 24 Agosto 2016 in Italia.

Il terremoto ha interessato le province di Rieti, Ascoli Piceno e Perugia, causando numerose vittime e notevoli danni. Al momento in cui viene scritta questa pagina (27 agosto) le notizie che provengono dalle fonti ufficiali sono ancora in divenire e verranno aggiornate con informazioni dettagliate e puntuali non appena possibile. Al momento il consiglio per avere informazioni di dettaglio sull'evento è di fare riferimento alla [pagina di Wikipedia dedicata all'evento e disponibile a questo link](https://it.wikipedia.org/wiki/Terremoto_del_Centro_Italia_del_2016). Un buon luogo dove trovare informazioni in tempo reale è [questa pagina di Internazionale.it](http://www.internazionale.it/live/terremoto-italia-amatrice-rieti)

Il progetto non vuole in alcun modo sostituirsi a fonti istituzionali di informazione a cui rimandiamo caldamente per l'attendibilità. Il progetto si pone come scopo quello di aggregare e non disperdere contenuti utili a tutti provenienti da fonti di varia natura (ufficiali e non) al fine creare valore in un momento di crisi per il paese.

L'idea è di [Matteo Tempestini](https://twitter.com/il_tempe) e [Matteo Fortini](https://twitter.com/matt_fortini) e nasce a seguito di maturata esperienza di hacking civico, ma il sostegno è di chiunque vuole darlo (privati, associazioni, imprese, istituzioni) purchè l'iniziativa non sia strumentalizzata per secondi fini e di questo chi ha ideato il progetto cerca di farsi garante. Sotto riportiamo chi sta già collaborando, ti aspettiamo!


### Credits

Un grazie sentito a :

- Tutto lo staff di [ActionAid Italia](https://www.actionaid.it/) per il supporto, la gestione delle informazioni web, la produzione di contenuti e il dominio.
- [Emergenza24](http://www.emergenza24.org) per il supporto sul web
- [Openstreetmap Italia](https://openstreetmap.it/) per il lavoro di mappatura nelle zone del terremoto
- [Andrea Borruso](https://twitter.com/aborruso); [Nino Galante](https://twitter.com/picomiles); [Maurizio de Magnis](https://twitter.com/olistik); [Sabas](https://twitter.com/__sabas);[Alberto Cottica](https://twitter.com/alberto_cottica) per il loro supporto da civic hackers
- Donata Columbo, Rosy Battaglia, Fabio Manfrin, Marieva Favonio per la gestione della comunicazione
- Chiara Spinelli per il supporto nella verifica del crowdfounding
- Valeria Villan per la sua esperienza in crisi management

..... 
(i ringraziamenti sono in progress ogni giorno....Non avertene a male se non compari ancora, grazie lo stesso!)



### Contatti
- [Mail](mailto:terremotocentroita@gmail.com): da usare per condividere informazioni utili
- [Gruppo Facebook](https://www.facebook.com/groups/1758670357733881/) : da usare per condividere informazioni utili
- [Twitter](https://twitter.com/terremotocentro): da usare per indirizzare twitter da rilanciare
- [Gruppo Telegram](https://telegram.me/joinchat/BgW6eEBsI3rLKsJk9L7FJg) da usare per chattare sul tema

### Press

<table>
  <thead>
    <tr>
      <td>Data</td> <td>Dove</td> <td>Titolo</td>
    </tr>
  </thead>
  <tbody>
    {% for member in site.data.press %}
      <tr>
        <td>{{member.data}}</td> <td>{{member.dove}}</td> <td>[{{member.titolo}}]({{member.link}})</td>
      </tr>
    {% endfor %}
  </tbody>
</table>
