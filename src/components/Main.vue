<template>
  <div>
    <header id="head">
      <div class="container d-non">
        <div class="row">
          <div class="col-sm-4">
            <a href="#" class="brand">
              <img src="../assets/logo.png" alt="logo">
            </a>
          </div>
          <div class="col-sm-4 justify-content-center d-flex my-auto d-non">
              <img src="../assets/phone.png" alt="phone">
          </div>
          <div class="col-sm-4 d-non"></div>
        </div>
      </div>
      <nav class="navbar navbar-expand-lg py-0" id="top-a">
        <a href="#" class="a-min-logo">
          <img src="../assets/w-w-logo.png" alt="logo" class="min-logo">
        </a>
        <button class="navbar-toggler ml-auto" @click="onClick">
            <span class="icon-bar"></span>
            <span class="icon-bar"></span>
            <span class="icon-bar"></span>
        </button>
        <div class="navbar-collapse" v-show="isOpen" id="navbarSupportedContent">
          <ul class="nav navbar-nav mx-auto justify-content-around w-100 h-100">
            <li class="dropdown" @click="onClick_1" id="menu_1">
              <a href="#">
                <span>Wettanbieter ohne Wettsteuer</span>
                <b class="caret"></b>
              </a>
              <ul class="dropdown-menu" v-show="isOpen_1">
                  <li><a href="#">22Bet</a></li>
                  <li><a href="#">LSbet</a></li>
                  <li><a href="#">Betfair</a></li>
                  <li><a href="#">WirWetten</a></li>
                  <li><a href="#">Megapari</a></li>
                  <li><a href="#">Stake.com</a></li>
                  <li><a href="#">Melbet</a></li>
                  <li><a href="#">Guts Wettsteuer</a></li>
                  <li><a href="#">Bet3000</a></li>
                  <li><a href="#">CampoBet</a></li>
                  <li><a href="#">BUFF.bet</a></li>
                  <li><a href="#">Tipico</a></li>
                  <li><a href="#">Betwinner</a></li>
                  <li><a href="#">1xBet</a></li>
                  <li><a href="#">ReloadBet</a></li>
                  <li><a href="#">b-Bets Sport</a></li>
                  <li><a href="#">DoubleBet</a></li>
                  <li><a href="#">Intertops</a></li>
                  <li><a href="#">1xBit</a></li>
                  <li><a href="#">Sportingbet</a></li>
                  <li><a href="#">NEO.bet</a></li>
                  <li><a href="#">BetBoro</a></li>
                  <li><a href="#">Sportsbet.io</a></li>
                  <li><a href="#">18Bet</a></li>
                  <li><a href="#">BetWorld</a></li>
                  <li><a href="#">tipwin</a></li>
                  <li><a href="#">Betsson</a></li>
                  <li><a href="#">BonkersBet</a></li>
                  <li><a href="#">BetEast</a></li>
                  <li><a href="#">Fastbet</a></li>
                  <li><a href="#">BetAdonis</a></li>
              </ul>
            </li>
            <li class="dropdown" @click="onClick_2" id="menu_2">
              <a href="#">
                <span>Wettanbieter mit Wettsteuer</span>
                <b class="caret"></b>
              </a>
              <ul class="dropdown-menu" v-show="isOpen_2">
                <li><a href="#">Bet365</a></li>
                <li><a href="#">Betway</a></li>
                <li><a href="#">BetVictor</a></li>
                <li><a href="#">888sport</a></li>
                <li><a href="#">mybet</a></li>
                <li><a href="#">ComeOn</a></li>
                <li><a href="#">Interwetten</a></li>
                <li><a href="#">Mobilebet</a></li>
                <li><a href="#">Skybet</a></li>
                <li><a href="#">Betano</a></li>
                <li><a href="#">Campeonbet</a></li>
                <li><a href="#">SchnellWetten</a></li>
                <li><a href="#">Bwin</a></li>
                <li><a href="#">bet-at-home</a></li>
                <li><a href="#">X-TiP</a></li>
                <li><a href="#">Unibet</a></li>
                <li><a href="#">William Hill</a></li>
                <li><a href="#">Sunnyplayer Sport</a></li>
                <li><a href="#">BetOlimp</a></li>
                <li><a href="#">Bethard</a></li>
                <li><a href="#">Ladbrokes</a></li>
                <li><a href="#">Betsafe</a></li>
                <li><a href="#">RaceBets</a></li>
                <li><a href="#">Cashpoint</a></li>
              </ul>
            </li>
            <li class="dropdown" @click="onClick_3" id="menu_3">
              <a href="#">
                <span>Bester Wettbonus</span>
                <b class="caret"></b>
              </a>
              <ul class="third-menu dropdown-menu" v-show="isOpen_3">
                <li class="third-item"><a href="#">Wettbonus ohne Einzahlung</a></li>
                <li class="third-item"><a href="#">Bitcoin Sportwetten</a></li>
                <li class="third-item"><a href="#">Pay N Play Sportwetten</a></li>
              </ul>
            </li>
            <li class="dropdown"><a href="#"><span>Beste Wettquoten</span><b class="blok"></b></a></li>
            <li class="dropdown"><a href="#"><span>Wettgebühren</span><b class="blok"></b></a></li>
            <li class="dropdown"><a href="#"><span>News</span><b class="blok"></b></a></li>
          </ul>
        </div>
      </nav>
    </header>
    <main>
      <div class="teaser" id="teaser">
        <img src="../assets/header-img.jpg" alt="header-img" width="100%" height="250px">
        <h1 class="text-center">Wir testen alle Wettanbieter ohne Wettsteuer in Deutschland</h1>
      </div>
      <div class="container">
        <div class="content">
          <p>Über die Wettsteuer informiert sein! Die Wettsteuer umgehen und ohne 5% Steuer wetten. Wettsteuer.com zeigt Ihnen wie es geht – Durch den neuen Glückspielstaatsvertrag, der Anfang Juli in Deutschland in Kraft getreten ist, hat sich im Bereich Sportwetten im Internet, beim einen oder anderen Wettanbieter einiges geändert. Grundsätzlich muss ab sofort beachtet werden, dass in Deutschland eine Wettsteuer von 5% auf Sportwetten erhoben wird, die von den Anbietern von Sportwetten im Internet, an das Finanzamt abgeführt werden muss.</p>
          <h2>TOP 3 Wettanbieter ohne Wettsteuer</h2>
          <table class="table table-striped text-center table-hover table-borderless">
            <thead>
              <tr>
                <th>Wettanbieter</th>
                <th>Bonus</th>
                <th>Mindestquote</th>
                <th>Bewertung</th>
                <th>Zum Anbieter</th>
              </tr>
            </thead>
            <tbody>
              <tr>
                <td><img src="https://wettsteuer.com/wp-content/uploads/2020/04/22bet.png" alt="22bet Wettsteuer"><a href="#">22bet Wettsteuer</a></td>
                <td>100% bis zu 122€</td>
                <td>1.40</td>
                <td>9.7</td>
                <td><a href="#" class="btn-buy">OHNE STEUER WETTEN</a></td>
              </tr>
              <tr>
                <td><img src="https://wettsteuer.com/wp-content/uploads/2020/04/lsbet.png" alt="LSbet Wettsteuer"><a href="#">LSbet Wettsteuer</a></td>
                <td><span class="exclusive">Exklusiv</span><br>200% bis zu 200€</td>
                <td>1.70</td>
                <td>9.5</td>
                <td><a href="#" class="btn-buy">OHNE STEUER WETTEN</a></td>
              </tr>
              <tr>
                <td><img src="https://wettsteuer.com/wp-content/uploads/2020/08/stake-logo-200x101-.png" alt="Stake.com Wettsteuer"><a href="#">Stake.com Wettsteuer</a></td>
                <td>100 $ in Krypto</td>
                <td></td>
                <td>8.9</td>
                <td><a href="#" class="btn-buy">JETZT WETTEN</a></td>
              </tr>
            </tbody>
          </table>
          <p>Unterschiedliches Handling der Wettsteuer für die Endverbraucher – Wettsteuer.com informiert Dies hat zur Folge, dass man als Kunde, wenn man zum Beispiel Sportwetten in Höhe von 100 Euro platzieren will, nach Abzug der Wettsteuer, nur noch 95 Euro für die Wetten zur Verfügung hat. Andere Online Wettbüros behalten die 5% Wettsteuer dahingehend ein, dass diese direkt von den Umsätzen, welche ein Kunde mit seinen Sportwetten getätigt hat, abgezogen wird.</p>
          <h3>Empfehlung: Wettanbieter des Monats</h3>
          <table class="table table-striped text-center table-hover table-borderless">
            <thead>
              <tr>
                <th>Wettanbieter</th>
                <th>Bonus</th>
                <th>Mindestquote</th>
                <th>Bewertung</th>
                <th>Zum Anbieter</th>
              </tr>
            </thead>
            <tbody>
              <tr>
                <td><img src="https://wettsteuer.com/wp-content/uploads/2020/04/22bet.png" alt="22bet Wettsteuer"><a href="#">22bet Wettsteuer</a></td>
                <td>100% bis zu 122€</td>
                <td>1.40</td>
                <td>9.7</td>
                <td><a href="#" class="btn-buy">OHNE STEUER WETTEN</a></td>
              </tr>
            </tbody>
          </table>
          <p>Die Wettsteuer wird in diesem Fall also direkt von den erzielten Gewinnen abgezogen, wobei der Bruttogewinn anhand des Einsatzes bei den Wetten und der jeweiligen Quote errechnet wird. Die Wettquote insgesamt, verringert sich natürlich in jedem Fall für die einzelnen Spieler, egal auf welche Art und Weise die Wettsteuer berechnet wird.</p>
          <h2>Alle Online Buchmacher mit Wettbonus</h2>
          <table class="table table-striped text-center table-hover table-borderless">
            <thead>
              <tr>
                <th>Wettanbieter</th>
                <th>Bonus</th>
                <th>Mindestquote</th>
                <th>Bewertung</th>
                <th>Zum Anbieter</th>
              </tr>
            </thead>
            <tbody>
              <catalog-item
                v-for="product in products"
                :key="product.article"
                :product_data="product"
              />
            </tbody>
          </table>
          <p><img class="align-right" src="https://wettsteuer.com/wp-content/uploads/2014/06/laptop-1.jpg" alt="" sizes="(max-width: 464px) 100vw, 464px">Es gibt aber auch Anbieter von Sportwetten, die ihre Kunden in keinster Weise mit der Wettsteuer belasten, sondern diese selbst tragen. Es gilt also in Zukunft nicht nur darauf zu achten, welcher Wettanbieter einen attraktiven Bonus für Neukunden vergibt oder welches Wettbüro die besten Quoten bietet, sondern auch, wie der jeweilige Anbieter von Sportwetten mit der neu eingeführten Wettsteuer umgeht.</p>
          <p>Bei Wettsteuer.com erfahren Sie alles wissenswerte über die Wettsteuer, wie zum Beispiel, auf welche Art und Weise diese vom einen oder anderen Anbieter an die Kunden weiter berechnet wird und bei welchem Anbieter Sie nach wie vor Wetten ohne Steuer abschließen können.</p>
          <p class="headline">Aktuelle Sportwetten News</p>
          <div class="blogposts">
            <div class="row">
              <div class="col-sm-4">
                <div class="artical"><a href="#">
                  <img src="https://wettsteuer.com/wp-content/uploads/2020/11/skybet-news-300x188-1.jpg" alt="" sizes="(max-width: 300px) 100vw, 300px">
                  </a></div>
                <h2><a href="#">Top-Spiele in der Bundesliga – Skybet hält einen Super-Boost bereit</a></h2>
              </div>
              <div class="col-sm-4">
                <div class="artical"><a href="#">
                  <img src="https://wettsteuer.com/wp-content/uploads/2020/10/300x188-2.jpg" alt="" sizes="(max-width: 300px) 100vw, 300px">
                  </a></div>
                <h2><a href="#">Top Quoten für das Champions League Spiel Atlético Madrid vs. Red Bull Salzburg – Nur für neue Kunden vom Sportwetten-Anbieter 888sport</a></h2>
              </div>
              <div class="col-sm-4">
                <div class="artical"><a href="#">
                  <img src="https://wettsteuer.com/wp-content/uploads/2020/10/300x188-.jpg" alt="" sizes="(max-width: 300px) 100vw, 300px">
                  </a></div>
                <h2><a href="#">Auf die packenden Duelle in der UEFA Nations League bei 888sport wetten</a></h2>
              </div>
            </div>
          </div>
          <ul>
            <li><a href="#yak1">Wie kann ich die Wettsteuer umgehen?</a></li>
            <li><a href="#yak2">Gibt es eine Wettsteuer in der Schweiz?</a></li>
            <li><a href="#yak3">Gibt es eine Wettsteuer in Österreich?</a></li>
            <li><a href="#yak4">Gibt es eine Wettsteuer in Spanien?</a></li>
            <li><a href="#yak5">Welche Arten der Wettsteuer gibt es?</a></li>
            <li><a href="#yak6">Wie bezahle ich die Wettsteuer selber?</a></li>
            <li><a href="#yak7">Wieso wurde das Wettsteuer Gesetz eingeführt?</a></li>
            <li><a href="#yak8">Gibt es neben der Wettsteuer auch eine Casinosteuer?</a><a id="yak1"></a></li>
          </ul>
          <img src="https://wettsteuer.com/wp-content/uploads/2014/06/Wettsteuer-umgehen-1.png" alt="" class="align-left" sizes="(max-width: 510px) 100vw, 510px">
          <h2>Wie kann ich die Wettsteuer umgehen?</h2>
          <p>Durch den neuen Glücksspielstaatsvertrag tritt seit Anfang Juli diesen Jahres die Wettsteuer in Kraft. Auf jede Wette fallen somit 5% Wettsteuer an, was den Wetteinsatz von 100 Euro auf 95 Euro reduziert.</p>
          <h3>Die Wettsteuer dank Proxy oder VPN umgehen</h3>
          <p>Sportwetter mit einem Wohnsitz in Deutschland müssen seit der Einführung des Glücksspielstaatsvertrags im Jahr 2012 für jede getätigte Wette eine Wettsteuer in der Höhe von 5 Prozent ihres Einsatzes abgeben. Die Gebühren, also die Steuer die letztlich vom Wettanbieter entrichtet werden muss, werden nur von sehr wenigen Buchmachern übernommen. Zumeist muss der Sportwetter aus Deutschland diese abgeben, kann aber mithilfe von VPN oder Proxy die Wettsteuer umgehen.</p>
          <h4>Proxy</h4>
          <p>Um die Wettsteuer zu umgehen, muss der Wettanbieter davon ausgehen, dass der Spieler sich bei der Wettabgabe nicht in Deutschland aufhält. Ein sogenannter Proxy-Server schafft hier Abhilfe. Nach der erfolgreichen Einrichtung eines passenden Proxy-Servers, kann man seine eigentliche IP-Adresse ändern und einen anderen Standort wie zum Beispiel Österreich oder Holland hinterlegen. Somit kann der Spieler trotz eines aktuellen Wohnsitzes in Deutschland die 5% Gebühr umgehen, da er sich zum Zeitpunkt der Wettabgabe nicht in Deutschland befand.</p>
          <h4>VPN</h4>
          <p>Ähnlich wie beim Proxy-Server verhält es sich mit einem VPN (Virtual Private Network). Dies ist wohl die professionellere Lösung zum ändern seiner IP-Adresse. Den Zugang zu diesen Servern kann man bei verschiedenen Anbietern gegen eine geringe monatliche Gebühr mieten. Zudem kann man bei dieser Lösung spezielle VPN-Server nutzen, die in ganz bestimmten Ländern stehen. Auch damit ist es also möglich die Wettsteuer in Deutschland ganz einfach zu umgehen.</p>
          <h3>Die nötigen Dokumente zur Verifizierung beschaffen</h3>
          <p>Weitere Möglichkeit um die Wettsteuer zu umgehen besteht darin, sich entsprechenden Dokumente für die spätere Verifizierung zu organisieren. Hier gibt es verschiedene Möglichkeiten für Spieler. Zum einen spielt der Bankauszug eine wichtige Rolle und zum anderen der Reisepass. Der Trick besteht darin, die eigene Adresse im Bankkonto nur kurzfristig in eine Adresse in Österreich per Online Banking zu ändern. Geht man anschließend zu seiner Bank um sich einen Kontoauszug abzuholen, wird die neue Adresse auf diesem automatisch hinterlegt. Anschließend reicht der Kontoauszug in Verbindung mit einem gültigen Reisepass bei fast allen Wettanbietern zur Verifizierung aus. Als Alternative gibt es inzwischen einige Agenturen, die für kleines Geld Führerscheine in Osteuropa anbieten. Auch damit wäre eine Verifizierung also möglich.</p>
          <h3>Dank Quotenvergleich die Steuer umgehen</h3>
          <p>Eine weitere Möglichkeit ist die Steuer dank eines Quotenvergleichs zu umgehen. Diese Variante ist sicherlich der mühsamste Weg. Vor allem aber langfristig kann sich der Quotenvergleich durchaus lohnen. Dafür ist es erforderlich, die Quoten der einzelnen Buchmacher jedesmal miteinander zu vergleichen. Wird dann anschließend immer mit der Höchstquote gewettet, kann diese mit etwas Glück bis zu fünf Prozent besser ausfallen als bei den anderen Wettanbietern. Somit hätte der Spieler dann die Wettsteuer, die ebenfalls fünf Prozent beträgt, wieder eingespart.</p>
          <h3>Bei Wettanbietern ohne Steuer wetten</h3>
          <p>Dies ist wohl die einfachste Möglichkeit, um die Wettsteuer zu umgehen. Denn: Die Wettsteuer wird zwar in Deutschland auf alle Wetten fällig. Nicht alle Buchmacher legen Diese jedoch auch auf ihre Spieler um. Es gibt nach wie vor verschiedene Wettanbieter, die die Steuer selbst tragen. Alles was man tun muss, ist einen solchen Anbieter finden und sich bei diesem Anmelden. Ist das geschehen, kann man ganz normal Wetten und seine Einsätze tätigen. Im Falle eines Gewinnes wird dieser in voller Höhe ausgezahlt. Die Steuer trägt der Buchmacher.</p>
          <h2>Top 10 Buchmacher ohne Steuern</h2>
          <table class="table table-striped text-center table-hover table-borderless">
            <thead>
              <tr>
                <th>Wettanbieter</th>
                <th>Bonus</th>
                <th>Mindestquote</th>
                <th>Bewertung</th>
                <th>Zum Anbieter</th>
              </tr>
            </thead>
            <tbody>
              <tr>
                <td><img src="https://wettsteuer.com/wp-content/uploads/2020/04/22bet.png" alt="22bet Wettsteuer"><a href="#">22bet Wettsteuer</a></td>
                <td>100% bis zu 122€</td>
                <td>1.40</td>
                <td>9.7</td>
                <td><a href="#" class="btn-buy">OHNE STEUER WETTEN</a></td>
              </tr>
              <tr>
                <td><img src="https://wettsteuer.com/wp-content/uploads/2020/04/lsbet.png" alt="LSbet Wettsteuer"><a href="#">LSbet Wettsteuer</a></td>
                <td><span class="exclusive">Exklusiv</span><br>200% bis zu 200€</td>
                <td>1.70</td>
                <td>9.5</td>
                <td><a href="#" class="btn-buy">OHNE STEUER WETTEN</a></td>
              </tr>
              <tr>
                <td><img src="https://wettsteuer.com/wp-content/uploads/2020/08/stake-logo-200x101-.png" alt="Stake.com Wettsteuer"><a href="#">Stake.com Wettsteuer</a></td>
                <td>100 $ in Krypto</td>
                <td></td>
                <td>8.9</td>
                <td><a href="#" class="btn-buy">OHNE STEUER WETTEN</a></td>
              </tr>
              <tr>
                <td><img src="https://wettsteuer.com/wp-content/uploads/2020/04/william-hill.png" alt="William Hill Wettsteuer"><a href="#">William Hill Wettsteuer</a></td>
                <td>100% bis zu 100€</td>
                <td>1.80</td>
                <td>8.9</td>
                <td><a href="#" class="btn-buy">OHNE STEUER WETTEN</a></td>
              </tr>
              <tr>
                <td><img src="https://wettsteuer.com/wp-content/uploads/2020/07/MegaPari-logo-200x101-.png" alt="Megapari Wettsteuer"><a href="#">Megapari Wettsteuer</a></td>
                <td>100% bis zu 100€</td>
                <td>1.40</td>
                <td>8.7</td>
                <td><a href="#" class="btn-buy">OHNE STEUER WETTEN</a></td>
              </tr>
              <tr>
                <td><img src="https://wettsteuer.com/wp-content/uploads/2020/04/melbet.png" alt="Melbet Wettsteuer"><a href="#">Melbet Wettsteuer</a></td>
                <td>100% bis zu 100€</td>
                <td>1.40</td>
                <td>8.7</td>
                <td><a href="#" class="btn-buy">OHNE STEUER WETTEN</a></td>
              </tr>
              <tr>
                <td><img src="https://wettsteuer.com/wp-content/uploads/2020/04/guts.png" alt="Guts Wettsteuer"><a href="#">Guts Wettsteuer</a></td>
                <td>100% bis zu 50€</td>
                <td>1.80</td>
                <td>8.5</td>
                <td><a href="#" class="btn-buy">OHNE STEUER WETTEN</a></td>
              </tr>
              <tr>
                <td><img src="https://wettsteuer.com/wp-content/uploads/2020/04/bet3000.png" alt="Bet3000 Wettsteuer"><a href="#">Bet3000 Wettsteuer</a></td>
                <td>100% bis zu 150€</td>
                <td>2.00</td>
                <td>8.4</td>
                <td><a href="#" class="btn-buy">OHNE STEUER WETTEN</a></td>
              </tr>
              <tr>
                <td><img src="https://wettsteuer.com/wp-content/uploads/2020/04/campobet.png" alt="CampoBet Wettsteuer"><a href="#">CampoBet Wettsteuer</a></td>
                <td><span class="exclusive">Exklusiv</span><br>100% bis zu 250€</td>
                <td>2.00</td>
                <td>8.3</td>
                <td><a href="#" class="btn-buy">JETZT WETTEN</a></td>
              </tr>
              <tr>
                <td><img src="https://wettsteuer.com/wp-content/uploads/2020/04/buff-bet.png" alt="BUFF.bet Wettsteuer"><a href="#">BUFF.bet Wettsteuer</a></td>
                <td>100% bis zu 100€</td>
                <td>1.70</td>
                <td>8.1</td>
                <td><a href="#" class="btn-buy">OHNE STEUER WETTEN</a></td>
              </tr>
              <a id="yak2"></a>
            </tbody>
          </table>
          <img src="https://wettsteuer.com/wp-content/uploads/2014/06/Wettsteuer-in-der-Schweiz-1-1.png" alt="" class="align-left" sizes="(max-width: 510px) 100vw, 510px">
          <h2>Gibt es eine Wettsteuer in der Schweiz?</h2>
          <p>Streng genommen gibt es in der Schweiz eine Wettsteuer, sofern man das Wetten als Form des Glücksspiels zählt – und das tut der Gesetzgeber! Zumindest werden die Gewinne unter bestimmten Voraussetzungen versteuert. In der Schweiz haben die jeweiligen Kantone die gesetzgeberische Gewalt, was das Steuerrecht betrifft. Der Grundsatz „Geldspiel im Dienste des Gemeinwohls“ sollte ursprünglich den Anreiz bieten, dass die Steuererträge aus Geldspielen an gemeinnützige Projekte fließen. Auch die Glücksspielsucht per se sollte mit diesen Mitteln im Land bekämpft werden. Wer aber geschickt spielt, schleust die Beträge am Gesetzgeber vorbei – und das sogar völlig legal. Der Grund: Wer bei privaten Anbietern spielt, die ihren Sitz bzw. ihre Server nicht in der Schweiz haben, ist auch nicht verpflichtet, dem schweizerischen Steuerrecht nachzukommen.</p>
          <h3>Freigrenze von 1000 Franken gilt als Grenze in den meisten Kantonen</h3>
          <p>Seit dem Jahr 2013 gilt die Grenze von jährlich 1000 Franken, ab der dann offiziell steuerliche Abgaben anfallen. Die Begründung: Wer mehr als 1000 Franken pro Jahr einnimmt, der spielt bzw. wettet professionell. Die Gewinne werden demnach mit einem Einkommen gleichgesetzt – Es greift also das Einkommenssteuerrecht. Übrigens: Die Situation ist in diesem Fall sowohl in der Schweiz als auch in Deutschland und Österreich identisch: Wer professionell spielt und bestimmte Beträge im Jahr überschreitet, muss damit rechnen, dass der Gewinn mit einem offiziellen Einkommen gleichgesetzt wird.</p>
          <h3>Viele private Anbieter drängen auf den Markt und ermöglichen Schlupflöcher im Steuerrecht</h3>
          <p>Lange Jahre war das Glücksspiel in der Schweiz reine Staatsangelegenheit. Wer zum Beispiel bei den staatlichen Lotterien eine Wette platziert, um satte Gewinne abzuräumen, der zahlt völlig automatisch – ohne es zu merken – eine Verrechnungssteuer in Höhe von 35%. Diese werden automatisch durch die staatliche Lotterie an den Fiskus abgezwackt. Die Abzüge werden den Bürgern aber mit Abgabe der Steuererklärung wieder gutgeschrieben. Mit dem Aufkommen der vielen privaten Anbieter durch das Bekanntwerden der Sportwetten im Internet hat sich jedoch einiges geändert. Selbstverständlich zahlen diese privaten Anbieter keine Verrechnungssteuer an den Staat – müssen sie aber auch nicht: Da sich die Server in nahezu allen Fällen im Ausland und nicht im eigenen Land befinden, gibt es keine steuerrechtliche Verpflichtung, Beträge aus den Wetteinnahmen an den schweizerischen Staat abzutreten.</p>
          <h3>Wetten bei privaten Anbietern ist erlaubt – Wer hier wettet, zahlt auch in der Schweiz keine Wettsteuer</h3>
          <p>Bis heute ist es so, dass das Betreiben eines Lotterie-Betriebes oder eines Wettbüros in der Schweiz verboten ist. Sofern sich die Server aber nicht auf schweizerischem Boden befinden, werden auch die privaten Anbieter im Internet geduldet. Den Bürgern wird das Wetten bei diesen privaten Anbietern im Internet natürlich nicht untersagt. Im Gegenteil: Das Wetten ist ausdrücklich erlaubt und wird nicht durch den Staat verfolgt. Alle Wetter die dieses „ausländische<a id="yak3"></a>, private Angebot“ der Wettbranche im Internet nutzen, müssen keiner Steuerschuld nachkommen.</p>
          <img src="https://wettsteuer.com/wp-content/uploads/2014/06/Wettsteuer-in-%C3%96sterreich-1.png" alt="" class="align-left" sizes="(max-width: 510px) 100vw, 510px">
          <h2>Gibt es eine Wettsteuer in Österreich?</h2>
          <p>Die Gesetzte und Regeln sind in den meisten Ländern gleich, das heißt, dass überall eine Einkommenssteuer geleistet werden muss. Obwohl das geltende Recht in Österreich vorsieht, das Glücksspiel, wie auch die stattliche Lotterie, nicht zu dem Einkommen gezählt wird, so kann es dennoch vorkommen, dass auf den Gewinn eine Steuer fällig wird. Generell allerdings gibt es in Österreich keine Steuer für Sportwetten.</p>
          <p>Steuern können allerdings geltend gemacht werden, wenn bei einem Wettanbieter Steuern gezahlt werden müssen. Der Wettanbieter kann Steuern abziehen, da dieser Steuern zahlen muss und diese auf den Wetter umlegen kann. Ein Staatsvertrag für Glückspiel legt fest, dass Wettanbieter fünf Prozent der Einsätze für Wetten direkt an den Staat abzugeben hat. Im Grunde sind österreichische Kunden davon ausgeschlossen.</p>
          <h3>Neue Regeln geplant</h3>
          <p>Im Nationalrat wird schon seit einiger Zeit beraten, ob eine Gebühr für Wetten und Glücksspiel erhoben werden und wie hoch diese ausfallen soll. Wenn eine Einigung vorliegt, dann gilt diese auf für Österreich und für die im Ausland getätigten Wetten. Die Mögliche Gebühr soll zunächst bei Einsätzen circa zwei Prozent der Einsatzsumme betragen. Bisher war oftmals eine Wetteinsatzgebühr oder eine Gewinnstgebühr notwendig.</p>
          <p>Die Gewinnstgebühr wurde aus dem Verhältnis zwischen dem Einsatz und der Auszahlungssumme errechnet. Für Österreich wäre die neue Regel für einen Standort von Wetten dadurch viel interessanter, da für die Wettbüros die Belastung deutlich geringer wäre. Für die Kunden würde die Änderung positive Auswirkungen auf die Gewinnsumme haben und neue Angebote der Wettprodukte könnten ebenfalls in Anspruch genommen werden.</p>
          <h3>Streit um Wettterminal</h3>
          <p>Eine weitere Änderung hat für Streit gesorgt, der sogar vor Gericht verhandelt wird. Es wurde versucht Glückspiele zu reduzieren, indem man monatlich einen hohen Betrag für jeden Terminal abziehen wollte, der dem Kriegsopferfonds zufließen sollte. Die Betreiber wollten sich das nicht gefallen lassen und klagten. In Gegenden wie zum Beispiel Vorarlberg wurden sogenannte kleine Glückspiele wie etwa der einarmige Bandit verboten. Wenn nun noch erhöhte Steuereinnahmen wegfallen, dann bedeutet das erhebliche Verluste.</p>
          <p>Das wollten sich die Betreiber von Wettbüros nicht gefallen lassen. Hier vertritt man die Meinung, dass diese immense Steuerbelastung an die Kunden weitergegeben werden muss, doch das wäre äußerst geschäftsschädigend. Ein weiteres Argument ist, die Anzahl der bedürftigen Kriegsopfer wird jährlich geringer und somit wären weitere Kosten hier nicht notwendig. Außerdem würden von anderen Veranstaltungen ebenfalls Gelder für diesen Fond eingezahlt.</p>
          <p>Das Verfahren wurde erst einmal für Prüfungen unterbrochen, neben der Frage nach den Fonds geht es unter anderem auch um die Rechtmäßigkeit des Entwurfs und einiges mehr. Ein vorläufiger Beschluss besagt, dass eine Besteuerung der Wetten oder den Wetteinnahmen im Grunde die Angelegenheit des Bundes ist.</p>
          <h3>Eine klare Antwort</h3>
          <p>Am Ende lässt sich die Frage doch nicht so einfach beantworten, im Grunde gibt es keine Steuer doch am Ende zahlt der Wetter doch drauf, indem er Gebühren oder anderes zahlen soll. Somit ist irgendwie doch eine Steuer auf den Gewinn gelegt, doch da die Gebühren sich meistens noch im Rahmen halten, gibt es offensichtlich keinen Grund auf ein nettes Spiel zu verzichten. Dennoch empfiehlt es sich, die AGBs genau durchzulesen, um sich über die höhe der Gebühren zu erkundigen. Da den Wettbetreibern ständig Auflagen gemacht werden, kann man versuchen über besondere Gewinne oder Bonussysteme seine Gewinne zu erhöhen.</p>
          <p>In der Regel werden Neuerungen sofort bekannt gegeben, es ist aber sinnvoll sich genau zu erkundigen, wie die derzeitigen Richtlinien sind. Zu der fünf Prozent Gebühr lässt sich noch anmerken, dass diese von der Nettosumme des Gewinns berechnet und abgezogen werden. Bei einem Vergleich lässt sich ganz leicht feststelle, ob eine Gebühr fällig wird oder welche Konditionen individuell überhaupt infrage kommen. In der Regel können Kundenmeinungen oder Testberichte ebenfalls sehr hilfreich sein, den für sich richtigen Wettanbieter zu finden.</p>
          <h3>Wetten in Österreich</h3>
          <p>Momentan ist es trotz aller Schwierigkeiten oder Streitereien das Wetten in Österreich attraktiv. Abgesehen davon reagieren Wettanbieter auf gewisse Auflagen mit zahlreichen Angeboten, die dennoch sehr angenehm für Wetter sind. Wie schon erwähnt stehen in den Details die meisten Neuigkeiten und die Bedingungen, die für das Spiel oder die Wette zutreffen.</p>
          <p>Hauptsächlich bei deutschen Anbietern wird eine Gebühr fällig, doch auch hier gibt es zahlreiche Angebote, wo diese entfällt. Bei geringen Einsätzen gibt es ebenfalls Möglichkeiten, wie die<a id="yak4"></a> Steuer nicht fällig wird. Anbieter legen ihre Teilnahmebedingungen offen und der Wetter kann bequem alle wichtigen Informationen einsehen. Die Klagen können noch lange Zeit dauern und in der Zwischenzeit lassen sich die Angebote bequem nutzen.</p>
          <img src="https://wettsteuer.com/wp-content/uploads/2014/06/Wettsteuer-in-Spanien-1.png" alt="" class="align-left">
          <h2>Gibt es eine Wettsteuer in Spanien?</h2>
          <p>Europa wird immer mehr reguliert. Auch Spanien ist nun an der Reihe. Genauer gesagt im Bereich der Wettsteuer. Aktuell gibt es noch keine Wettsteuer, wie das zum Beispiel in Deutschland der Fall ist. Durch Spaniens Außenminister Jose Manuel Garcia-Margallo wurde es erst bekannt, dass Spanien ebenfalls eine Wettsteuer haben möchte. Dabei zielt diese Steuer auf Unternehmen ab, die im Ausland tätig sind, aber auch in Spanien anbieten.</p>
          <p>Solche Unternehmen sind beispielsweise wie Bwin oft auf Gibraltar. In Zukunft soll es also etwas Strenger zugehen in Bezug auf Wetten und deren Lizenzen. Das die Wettsteuer eine große Wirkung hat, zeigte sich schon in Deutschland. Daraufhin hat sich William Hill mit den Sportwetten zurückgezogen.</p>
          <h3>Auswirkungen auf die Wirtschaft</h3>
          <p>Die Wettsteuer hätte aber große Auswirkungen auf die Wirtschaft, da 15 Prozent der wirtschaftlichen Leistung von den Unternehmen der Wett- und Glücksspielindustrie stammen. Doch es zeigt sich zum Beispiel in Deutschland auch klar, dass es auch Regelungen gibt, die weniger fair und sehr fragwürdig sind.</p>
          <p>Trotzdem sieht der Staat mit dieser Wettsteuer das große Geschäft. Schließlich sind eine neue Steuer natürlich wieder eine neue Einnahmequelle für den Staat. Genau das soll mehr Gewinn mit sich bringen.</p>
          <h3>Kosten werden weitergegeben</h3>
          <p>Dabei ist auch noch zu beachten, wenn man sich die Situation in Deutschland ansieht, dass die Wettsteuer von den genannten 5 Prozent an die Kunden weitergegeben werden. Diese fünf Prozent werden vom Gewinn des Kunden abgezogen. Man sieht im Internet, vor allem in den Foren zum Thema wetten, dass die Kunden dieses Abzug mit gemischten Gefühlen aufnehmen und nach Alternativen suchen, um diese Wettsteuer zu umgehen. Schließlich gibt es im Zeiten des Internets einige Wege dazu.</p>
          <p>Wenn man es genau sieht, ist dieser Abzug vom Wettgewinn eigentlich nur eine Gewinnoptimierung der Unternehmen. Und in nur wenigen Fällen wird der tatsächliche Auszahlungswert in Vorfeld angegeben, falls man die Wette mit dem jeweiligen Einsatz gewinnen sollte. Es bleibt also noch abzuwarten, was die Zukunft <a id="yak5"></a>in Spanien noch so bringt. Wenn es nach dem Vorbild Deutschland geht, werden sicherlich sehr viele Versuchen, das Gesetz zu Umgehen und nach Alternativen suchen. Und das ist logischerweise nicht das, was der Gesetzgeber damit bezwecken möchte.</p>
          <img src="https://wettsteuer.com/wp-content/uploads/2014/06/Welche-Arten-der-Wettsteuer-gibt-es-1.png" alt="" class="align-left">
          <h2>Welche Arten der Wettsteuer gibt es?</h2>
          <p>Die Wettsteuer fällt unter das so genannte Rennwett- und Lotteriegesetz, auch RennwLottG abgekürzt, und ist eine gesetzlich geregelte indirekte Steuer. Dabei geht es um die Besteuerung von Wetteinsätzen bei Pferderennen, Sportwetten und Lotterien. Die Bundesländer sind für die Verwaltung verantwortlich und behalten auch die Einnahmen. Die Wettsteuer ist nicht mit den gemeinnützigen Abgaben der Lotterien zu verwechseln, mit denen sie wohltätige Projekte aus den Bereichen Sport, Kultur, Soziales oder Denkmalpflege unterstützen.</p>
          <p>Der Vorgänger des aktuell geltenden Rennwett- und Lotteriegesetz stammt bereits aus dem Jahr 1922. Die Wettsteuer ist nicht im Glücksspielstaatsvertrag verankert, da dieser Sache der Bundesländer ist.</p>
          <h3>Wie hoch ist die Wettsteuer?</h3>
          <p>Die Wettsteuer in Deutschland beträgt 5% des Umsatzes und muss in Deutschland von allen Wettanbietern abgeführt werden. Viele dieser Anbieter geben diese Steuer an die Kunden weiter, einige Unternehmen verzichten darauf. Für Kunden gibt es hier zwei Varianten, dass die Steuern zu zahlen sind: So fallen die 5% auf den Bruttogewinn an, aber tatsächlich nur im Gewinnfall. Andere Anbieter verlangen die 5% Steuern auf jeden Einsatz. In der Summe macht dies letztlich kaum einen Unterschied, die Besteuerung der Einsätze gilt aber als transparenter. Diese Besteuerung gilt sowohl für deutsche wie internationale Anbieter, ebenso für Online-Anbieter.</p>
          <h3>Wie kam es zur Wettsteuer?</h3>
          <p>Nun könnte man die Frage stellen, warum diese Wettsteuer überhaupt fällig wird. Lange kamen Online-Anbieter ohne Steuern aus, was das Wetten für Verbraucher attraktiv machte. Die Wettgewinne gingen vollständig an die Verbraucher. Der Markt der Online-Wettanbieter wuchs aber rasch. Der neue Glückspielstaatsvertrag gilt seit Juli 2012. Grundsätzlich kommen die meisten Steuern letztlich der Allgemeinheit zugute. Davon sind nun auch Wettanbieter und ihre Kunden betroffen. Der Staat verdrängte zunächst private Anbieter, mit dem Argument, Verbraucher vor der Spielsucht schützen zu wollen. So gab es einen staatlichen Anbieter, der das Monopol des Staates auf diese Steuereinnahmen sicherte. Auch die EU wollte hier mitreden. Denn viele deutsche Verbraucher wanderten von<a id="yak6"></a> deutschen Anbietern zu ausländischen Unternehmen ab, die Steuern blieben aus. Die EU zwang letztlich den deutschen Gesetzgeber zur Liberalisierung des Wettmarktes.</p>
          <img src="https://wettsteuer.com/wp-content/uploads/2014/06/Wie-bezahle-ich-die-Wettsteuer-selber-1.png" alt="" class="align-left">
          <h2>Wie bezahle ich die Wettsteuer selber?</h2>
          <p>Eine Wettsteuer ist in der Regel von dem Wettanbieter zu entrichten und somit hat der Wetter seine Steuern schon bezahlt, doch es gibt natürlich ausnahmen. Zu den Ausnahmen zählen Veranstaltungen von Rennen, da wird hier die Rennwettsteuer fällig, die bei einem Finanzamt, das für den Wetter zuständig ist, gemeldet werden. Bei allen anderen Wetten übernimmt der Wettanbieter die Steuer, da er alleine dafür haftet.</p>
          <p>Der Gewinn bei der Rennwettsteuer ist binnen einer Woche zu melden, doch man muss beachten, dass dies noch vor Ablauf eines halben Kalendermonats geschieht. Am besten meldet man den Gewinn schnellstmöglich, damit man keine Schwierigkeiten bekommt.</p>
          <h3>Wettsteuer ernst nehmen</h3>
          <p>Im Grunde ist der Steuerschuldner der Wettanbieter, der natürlich keine Umsatzeinbußen haben möchte und somit die Steuer auf die Kunden umlegt. Es gibt allerdings auch Anbieter, die davon absehen, doch hier sollte der Wetter vorsichtig sein, denn oft handelt es sich dabei um Anbieter ohne Lizenz.</p>
          <p>Aufgrund des Glückspielstaatsvertrages gelten neue Steuerregeln, die grundsätzlich eine Steuer für Glückspiele vorsieht. Diese allerdings sind laut Vertrag Aufgabe der Wettanbieter. So gesehen müssen Wetter sich in der Regel um nichts weiter kümmern. Dennoch legen die meisten Anbieter die Steuer auf die Kunden um, nur einige Ausnahmen bieten andere Konditionen an. Das Gleiche gilt für die Wettanbieter, die ihre Wetten im Internet anbieten.</p>
          <p>In der Regel werden fünf Prozent auf direkt platzierte Wetteinsätze berechnet. Bei manchen Anbietern werden die fünf Prozent von dem Bruttogewinn abgezogen. Wieder andere Betreiber verzichten komplett auf die Steuer und verlangen von dem Wetter nichts. Bei einigen Bonusangeboten spielt es oft keine Rolle, ob eine Steuer fällig wird oder nicht.</p>
          <h3>Wettsteuer leider notwendig</h3>
          <p>Staatliche Wettanbieter haben große Verluste hinnehmen müssen, da immer mehr private Buchmacher lukrative Angebote gemacht haben und somit dem Staat einige Steuern abhandengekommen sind. Als das Gesetz erlassen wurde, hat man noch nicht mit den Online-Angeboten rechnen können. Das Gesetz wurde schon erstmals im 15. Jahrhundert verfasst und seit dem 18. Jahrhundert gibt es eine Klassenlotterie, die aus Italien über Wien nach Berlin kam und über eine Verbrauchsteuer berechnet wurde. Seit 1922 gab es das bis in die heutige Zeit geltende Gesetz. Deshalb wurde 2012 eine Aktualisierung notwendig.</p>
          <p>Ein Gewinn ist ähnlich wie ein Einkommen zu rechnen, doch da die Pflicht bei dem Anbieter liegt, besteht für Kunden zunächst einmal kein Problem. Es ist natürlich bei einem so breiten Angebot nachvollziehbar, dass auch die privaten Wettanbieter, die auch im Internet zu finden sind, diesem Gesetz angepasst werden. Mit fünf Prozent ist man sogar noch gut bedient, und natürlich gibt es auch ausländische Anbieter, wo keine Steuer fällig wird.</p>
          <h3>Dennoch tolle Angebote</h3>
          <p>Wer Probleme vermeiden möchte, der sollte sich an einen Anbieter wenden, der über eine Lizenz verfügt, denn so kann man sicher sein, das dieser für seine Steuern geradesteht. Unter diesen Anbietern gibt es sehr viele, die darauf verzichten, die Steuer an die Kunden abzugeben.</p>
          <p>Ein neues Gesetz soll in Zukunft dafür sorgen, dass Wettanbieter ohne Lizenz, keine Angebote mehr machen dürfen. Es lohnt sich auch einen Blick auf die AGBs zu werfen, da werden alle Einzelheiten erklärt und man weiß genau, worauf man sich einlässt. Für Wetter ist es manchmal sogar sehr sinnvoll genau darauf zu achten, wie Anbieter mit der Steuer umgehen. Immer mehr Wettanbieter machen tolle Angebote oder verzichten ganz auf die Erhebung einer Steuer.</p>
          <h3>Steuern legal umgehen</h3>
          <p>Bei Wetten kann man im eigentlichen Sinn nicht von einem Umgehen sprechen, denn nach wie vor liegt die Steuerpflicht bei dem Wettanbieter, doch um den für sich richtigen Anbieter zu finden, gibt es natürlich die Möglichkeit sich vorher genau zu informieren und die Anbieter zu vergleichen. Daneben empfiehlt es sich die Bedingungen genau zu prüfen, doch auch die lassen sich ganz leicht vergleichen.</p>
          <p>Ein ganz wichtiger Punkt ist der, dass die Steuer auf jeden Fall nur dann fällig wird, wenn der Wetter gewonnen hat. Eine Steuer von fünf Prozent sollte auf keinen Fall beim Umsatz oder beim Einsatz erhoben werden. Hier zählen einzig und allein der Gewinn und die Gewinnsumme. Etwas anderes ist nicht wirklich rechtens. Deshalb verzichten immer mehr Anbieter darauf, die Steuer auf die Kunden abzuschieben.</p>
          <p>Der Wetter hat die Wahl, welchen Anbieter er nutzen möchte und da schneiden die Anbieter, die eine Steuer berechnen, schlechter ab, als die, die darauf verzichten. Deshalb hat der Kunde<a id="yak7"></a> die Wahl, an welchen Anbieter er sich wenden will. Es ist im eigentlichen Sinn kein Umgehen der Steuer, sondern rein nur ein lukratives Angebot, wenn der Wettanbieter darauf verzichtet.</p>
          <img src="https://wettsteuer.com/wp-content/uploads/2014/06/Wieso-wurde-das-Wettsteuer-Gesetz-eingef%C3%BChrt-1.png" alt="" class="align-left">
          <h2>Wieso wurde das Wettsteuer Gesetz eingeführt?</h2>
          <p>Seit 1922 gibt es das Lotterie- und Rennwettengesetz. In diesem gesetz möchte der Deutsche Bundestag die sogenannte Wettsteuer verankern. Ausschlaggebend für diese Wettsteuer ist die Landesregierung Schleswig-Holstein, welche den Glückspielmarkt schmackhafter machen wollten. Dies wäre jedoch mit sehr hohen Einnahmen verbunden gewesen. Daher sahen die anderen Landesregierungen dieses Vorgehen nicht als rechtens an und machten Schleswig-Holstein einen Strich durch die Rechnung. Durch die Einführung der Wettsteuer konnten die Bundesgesetze Schleswig-Holstein stoppen. Dennoch ist die Wettsteuer keineswegs neu.</p>
          <p>Für eine offizielle Lizenz kämpfen viele Anbieter und eine Wettsteuer kommt somit wie gerufen. Es gilt als illegal, wenn ein Internetanbieter keine Lizenzierung vorweisen kann. Dabei wollen die Anbieter natürlich die sogenannten „Grauzonen“ vermeiden, die durch unklare Definierung des Standortes, im Internet, auftritt. In Folge dessen hat die Bundesregierung eine 5-Prozent-Steuer, im Juli 2012, erlassen, die auf jede gewonnene Wette erhoben wird. In Deutschland sollen 20 Lizenzen an verschiedene Anbieter vergeben werden. Anbieter, die als Anwärter gelten berechnen die Steuer auf alle gewonnenen Wetter.</p>
          <p><strong>Darunter zählen bet-at-home; bwin; MyBet; JAXX; Cashpoint; Interwetten; Primebet; Betvictor; Sportingbet; Betclic; Gamebookers; Bet3000; Unibet; Betway und digibet</strong></p>
          <p>Nun könnte man sich fragen, warum Anbieter wie „Tipico“ keine Steuer berechnet. Tipico, sowie weitere Anbieter, haben sich dazu entschlossen online noch keine Steuer zu berechnen. In den Wettshops hingegen wird die Wettsteuer bei einer Tippabgabe bereits berechnet. Online dagegen wird darauf ohne weiteres verzichtet. Jedoch könnten noch weitere Anbieter, darunter auch Tipico, die Steuer einführen und sich eine Lizenz verschaffen.</p>
          <h3>Wie wird die 5-Prozent-Steuer berechnet?</h3>
          <p>Es gibt zwei Möglichkeiten, wie man die Steuer verrechnen kann. Am häufigsten beziehen sich diese Fünf Prozent auf den Gesamtgewinn der Wette. Recht selten wird die Steuer mit dem Einsatz verrechnet.</p>
          <p><strong>Anhand des folgenden Beispiels wird die Verrechnung, der 5-Prozent-Steuer, verdeutlicht:</strong><br> Max setzt 200€ auf einen Sieg des FC Bayern Münchens, bei einer Quote von 3.00. Er Gewinnt tatsächlich 600€. Von diesen 600€ werden ihm fünf Prozent Steuern abgezogen, das wären dann 30€. So geht Max mit einem Reingewinn von 570€ nach Hause.</p>
          <h3>Welche Vorteile hat die Wettsteuer?</h3>
          <p>Mit der Einführung der Wettsteuer wurde das Online-Glücksspiel legalisiert, was zuvor nicht der Fall war. Mit der Legalisierung hat der Kunde nun die Möglichkeit entsprechende Forderungen gegenüber Sportwettenanbietern einzuklagen.</p>
          <h3>Welche Nachteile hat die Wettsteuer?</h3>
          <p>Zumal die Quotenunterschiede einen sehr geringen Prozentsatz an Reingewinn, bei sicheren Wetten, haben, kann die 5-Prozent-Steuer, die von den Wettanbietern angefordert wird, alle diesbezüglichen Überlegungen total kaputt machen.</p>
          <h3>Fazit der Einführung des Wettsteuer Gesetztes</h3>
          <p>Man kann gewissenhaft sagen, dass sich der Wettmarkt für die priavten Abieter geöffnet hat, aber die gegenwärtigen Sachlage, durch die vielzahl an Einschränkungen, noch lange nicht das letzte Wort gesprochen ist. Wie es nun mit dem Wettsteuer Gesetz<a id="yak8"></a> weiter geht bzw. wann es zu einer endgültigen, festen und deutschlandweiten Regelung kommt, ist noch nicht abzusehen.</p>
          <img src="https://wettsteuer.com/wp-content/uploads/2014/06/Casinosteuer-1.png" alt="" class="align-left">
          <h2>Gibt es neben der Wettsteuer auch eine Casinosteuer?</h2>
          <p>In Deutschland, Österreich und der Schweiz ist die Rechtslage eindeutig: Da Gewinne aus Glücksspielen nicht zum regulären Einkommen zählen, fällt auch auf die in den Online Casinos oder bei online Wettanbietern erzielten Gewinne keine Einkommenssteuer an. Da es sich ebenfalls um keine Schenkung im traditionellen Sinne handelt, kann auch die Schenkungssteuer hier nicht greifen. Die Frage, ob es eine klassische Casino-Steuer gibt, ist also – zumindest was den europäischen Raum anbelangt – eindeutig geklärt. Nutzer der Online Casinos können demnach risikofrei spielen, ohne die Gewinne dem Finanzamt melden und so hohe Nachzahlungen befürchten zu müssen. Diese Regelung gilt übrigens sowohl für Casinos, die ihren Hauptsitz innerhalb der Europäischen Union haben als auch für Casinos, die außerhalb der EU ansässig sind.</p>
          <h3>Kleine Einschränkung für Casinos außerhalb der EU gibt es dennoch</h3>
          <p>Zu Beachten ist die Bargeldgrenze von 10.000 Euro, die bei einer Überschreitung in der Europäische Union angemeldet werden muss. In diesem Fall fallen auf die Geldsumme Einfuhrsteuern an, die den in den Casinos erzielten Gewinn schmälern können. Dies gilt jedoch – um keine Missverständnisse entstehen zu lassen – ausschließlich für Gewinne, die direkt vor Ort im Nicht-EU-Ausland erwirtschaftet worden sind. Transferierungen von Geld sind von diesem Sonderfall nicht betroffen. Sollte es ein zwischenstaatliches Steuerabkommen geben, fallen diese Steuern natürlich nicht an. Ein derartiges zwischenstaatliches Abkommen gibt es zum Beispiel zwischen der Bundesrepublik Deutschland und den USA: Während amerikanische Bürger 30 Prozent auf im Casino erzielte Gewinne an den Fiskus abtreten müssen, können Bürger aus Deutschland, Österreich und der Schweiz den gesamten Gewinn für sich behalten und müssen keine steuerrechtlichen Gegebenheiten beachten. Dies liegt an dem sogenannten Doppelbesteuerungsabkommen. Dies besagt, dass Beträge nicht zweimal besteuert werden dürfen. Auch die aus den Casinos erzielten Gewinne werden also nicht in den USA versteuert, sondern stets im Heimatland. Da es aber in Deutschland, Österreich und der Schweiz keine Steuer auf Finanzen, die aus Glücksspielen erwirtschaftet worden, gibt, können die Casino-Gewinner auch in diesem Fall ihren gesamten Gewinn behalten.</p>
          <h3>Diskussion um regelmäßige, professionelle Spieler</h3>
          <p>Aktuell wird in Deutschland eine hitzige Debatte geführt, wie mit professionellen Spielern zu verfahren sei, die aus dem Poker-Spiel in namhaften Casinos ein regelmäßiges Einkommen erwirtschaften. In diesem Fall würde ja – so die Argumentation – die Regelung bezüglich der Glücksspiele nicht mehr greifen. Es handele sich beim Poker schließlich vielmehr um ein Geschicklichkeitsspiel als um ein Glücksspiel im traditionellen Sinne. Sofern aber nur gelegentliche Gewinne verzeichnet werden, haben auch die Poker-Spieler, die in den Casinos spielen, nicht wirklich etwas zu befürchten. Die Prozesse sind zum jetzigen Zeitpunkt noch aktuell und es bleibt letztlich abzuwarten, ob und inwiefern sich aus diesen Fällen generelle Gesetzesableitungen werden erschließen lassen.</p>
          <h3>Einige Kantone in der Schweiz stellen eine Ausnahme dar</h3>
          <p>In der Schweiz gibt es regionale Unterschiede in der Besteuerung von Beträgen, die aus Glücksspielen erwirtschaftet worden sind. Die Besteuerungsgesetze in der Schweiz werden in den jeweiligen Kantonen eigenständig geregelt. Einige Kantone erheben daher auch eine Steuer auf Casino-Gewinne. Dieses Steuergesetz greift aber erst dann, wenn die Gewinne einen bestimmten Betrag überschreiten. Die Spieler in den Online-Casinos und Casinos vor Ort sollten sich also im Zweifelsfall mit einem Steuerberater in Verbindung setzen, wie die steuergesetzliche Lage in dem jeweiligen Kanton, in dem sie wohnen, aktuell ausgestaltet ist.</p>
          <h2>Bei wettsteuer.com finden Sie Wettanbieter ohne Steuer</h2>
          <p>Welcher Wettanbieter ohne Steuer arbeitet, bei welchem Sie von einem lukrativen Bonus profitieren können und wer vielversprechende Quoten anbietet, erfahren Sie bei wettsteuer.com. Wir testen die verschiedenen Wettanbieter in Bezug auf ihr komplettes Angebot und legen natürlich auch besonderes Augenmerk darauf, in welchem Online Wettbüro keine Steuer erhoben wird. So erhalten Sie am meisten für Ihr Geld und können sich ganz auf die aktuellen Sportwetten konzentrieren, anstatt sich Gedanken darüber machen zu müssen, wie viel Steuer von ihrer Einzahlung direkt bei der Abgabe Ihrer Tipps abgezogen wird und welcher Betrag von Ihren Gewinnen am Ende für Sie übrigbleibt.</p>
          <div class="tab-panel">
            <ul class="nav nav-tabs nav-justified">
              <li class="nav-item">
                <a class="nav-link" @click.prevent="setActive('22Bet')" :class="{ active: isActive('22Bet') }" href="#22Bet">22Bet</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" @click.prevent="setActive('1xBet')" :class="{ active: isActive('1xBet') }" href="#1xBet">1xBet</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" @click.prevent="setActive('Ironbet')" :class="{ active: isActive('Ironbet') }" href="#Ironbet">Ironbet</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" @click.prevent="setActive('Guts')" :class="{ active: isActive('Guts') }" href="#Guts">Guts</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" @click.prevent="setActive('Sportingbet')" :class="{ active: isActive('Sportingbet') }" href="#Sportingbet">Sportingbet</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" @click.prevent="setActive('Betworld')" :class="{ active: isActive('Betworld') }" href="#Betworld">Betworld</a>
              </li>
            </ul>
            <div class="tab-content" id="myTabContent">
              <div class="tab-pane fade" :class="{ 'active show': isActive('22Bet') }" id="22Bet">
                <h3>Bei 22Bet wird keine Wettsteuer an Kunden weiter berechnet</h3>
                <p>Ein wirklich guter und empfehlenswerter Wettanbieter ohne 5% Steuer ist 22Bet. Dabei ist dieses Wettbüro in den letzten Jahren nicht nur durch seinen zahlreichen Wettshops bekannt geworden, sondern auch durch sein umfassendes Angebot an Sportwetten im Internet, wodurch eine sehr gute Reputation bei seinem stetig wachsenden Kundenstamm erlangt wurde. Das Herz von 22Bet schlägt natürlich für Fußball. Die Live Wetten bei 22Bet sind besonders schnell und interessant. Hier kann schon man in wenigen Augenblicken einen Gewinn verbuchen, wenn man zum Beispiel richtig tippt, welches Team in einer gerade laufenden Partie, das nächste Tor erzielen wird – das Ganze wohlgemerkt ohne Wettsteuer.</p>
                <p>
                  <a href="#" class="btn btn-buy btn-blok">JETZT OHNE STEUER BEI 22BET WETTEN!</a>
                  <a href="#" class="btn btn-detail btn-blok">Mehr über 22Bet</a>
                </p>
              </div>
              <div class="tab-pane fade" :class="{ 'active show': isActive('1xBet') }" id="1xBet">
                <h3>Steuerfrei Wetten bei 1xBet</h3>
                <p>Bei <a href="#">1xBet</a> spielt die in Deutschland gesetzlich vorgeschriebene Wettsteuer keine Rolle. Man spart also als deutscher Kunde 5% bei jedem Einsatz. Dieser Anbieter von Sportwetten gehört somit zu einer kleinen Gruppe. Selbstverständlich gibt es auch einen Bonus. Etwas ungewöhnlich ist die Vorgabe, dass drei Wetten miteinander kombiniert werden müssen. Es wird also der Schnitt berechnet. Auch mehr Kombinationen wären möglich. Übrigens handelt es sich um einen Buchmacher aus Russland, was fraglos ungewöhnlich ist. Man darf dennoch von einem seriösen Unternehmen sprechen. Die Steuer wird nicht ignoriert. Die Ersparnis von 5% wird immer als Vorteil gewertet werden müssen, das gilt sowohl für die Quoten als auch beim <a href="#">1xBet Bonus</a>. Denn man zahlt halt keinen Aufschlag. Wer besonders viele Sportwetten abgibt, wird schnell erkennen, dass die ständige Ersparnis von 5% ein sehr großer Vorteil ist.</p>
                <p>
                  <a href="#" class="btn btn-buy btn-blok">JETZT OHNE STEUER BEI 1XBET WETTEN!</a>
                  <a href="#" class="btn btn-detail btn-blok">Mehr über 1xBet</a>
                </p>
              </div>
              <div class="tab-pane fade" :class="{ 'active show': isActive('Ironbet') }" id="Ironbet">
                <h3>Sportwetten ohne Steuer bei Ironbet</h3>
                <p><a href="#">Ironbet</a> bietet den Vorteil, dass Deutsche hier ohne den Aufschlag von 5% für die Wettsteuer wetten können. Dies mag daran liegen, dass der Name noch nicht ganz so bekannt ist. Auf jeden Fall ist ein bedeutender Vorteil genannt, denn die Ersparnis von 5% wirkt sich auf Dauer natürlich äußerst positiv auf das Konto eines Kunden aus. Auch die Tatsache, dass die erste Einzahlung verdoppelt wird, ist hier zu erwähnen. Da dieses Angebot ist natürlich nicht ungewöhnlich. Es sind Bedingungen zu erfüllen, wenn es eine Auszahlung geben soll. Doch es gibt zwei ungewöhnliche Vorschriften in diesem Zusammenhang. Zum einen müssen mindestens 15 Wetten in dem genannten Zeitraum unter den vorgeschriebenen Bedingungen abgegeben werden. Und dann kann nicht mehr als 1000€ insgesamt gewonnen werden mit einem <a href="#">Bonus von Ironbet</a>, egal um welches es sich auch handeln mag. Da man als Kunde allerdings nicht auch noch 5% Aufschlag zahlt, sind diese beiden Einschränkungen nicht allzu negativ zu bewerten.</p>
                <p>
                  <a href="#" class="btn btn-buy btn-blok">JETZT OHNE STEUER BEI Ironbet WETTEN!</a>
                  <a href="#" class="btn btn-detail btn-blok">Mehr über Ironbet</a>
                </p>
              </div>
              <div class="tab-pane fade" :class="{ 'active show': isActive('Guts') }" id="Guts">
                <h3>Berechnet Guts eine Wettsteuer?</h3>
                <p><a href="#">Guts Sportwetten</a> bedeutet, dass in Deutschland ohne Steuer gewettet werden darf. Konkret ausgedrückt spart man als Wetter bei jeder Wette bei diesem Buchmacher im Internet 5%. Dies betrifft aber ohnehin nur Kunden aus Deutschland, denn die Steuer, um die es hier geht, wird nur fällig, wenn innerhalb der deutschen Landesgrenzen auf Sportwetten gesetzt wird. Die Ersparnis wird sich für die Kunden lohnen, denn wer nicht nur eine einzige Wette tätigt, sondern fleißig Geld einsetzt, wird natürlich auf diese Art und Weise auf Dauer viel Geld sparen können. Dass Guts darüber hinaus interessante Promotionen bietet, soll nicht verschwiegen werden. Ohne die Steuer, also ohne einen Aufschlag von 5%, ist dies alles wesentlich einfacher einzulösen. Aufgrund der oftmals guten Quoten ist es auch recht leicht, die Mindestquote einzuhalten. Wem dies nicht gelingt in der vorgegebenen Frist, der bekommt seinen <a href="#">Guts Bonus</a> übrigens wieder aberkannt, das ist allgemein üblich.</p>
                <p>
                  <a href="#" class="btn btn-buy btn-blok">JETZT OHNE STEUER BEI GUTS WETTEN!</a>
                  <a href="#" class="btn btn-detail btn-blok">Mehr über Guts</a>
                </p>
              </div>
              <div class="tab-pane fade" :class="{ 'active show': isActive('Sportingbet') }" id="Sportingbet">
                <h3>Wie sieht mit Wettsteuer bei Sportingbet aus?</h3>
                <p><a href="#">Sportingbet</a> ist kein bekannter Name bei den Anbietern von Sportwetten, obwohl die deutsche Wettsteuer in Höhe von 5% keine Rolle spielt. Diese Ersparnis lohnt sich für alle Wetter. Man stelle sich einmal vor man tätigt Wetten in der Höhe von 100€ und muss zusätzlich 5€ dafür zahlen, quasi für nichts. Die Quoten werden dadurch nicht besser. Bei Sportingbetsind diese allerdings gut, womit ein weiterer Vorteil genannt ist.</p>
                <p>
                  <a href="#" class="btn btn-buy btn-blok">JETZT OHNE STEUER BEI SPORTINGBET WETTEN!</a>
                  <a href="#" class="btn btn-detail btn-blok">Mehr über Sportingbet</a>
                </p>
              </div>
              <div class="tab-pane fade" :class="{ 'active show': isActive('Betworld') }" id="Betworld">
                <h3>Auch bei Betworld fällt keine Steuer an</h3>
                <p>Bei <a href="#">Betworld</a> spielt die deutsche Wettsteuer keine Rolle. Sie wird in der vorgeschriebenen Höhe von 5% nicht auf die Kunden umgelegt. So etwas gefällt natürlich, weil es eine Ersparnis bedeutet, die sich auf Dauer wirklich lohnen kann. Ein nicht zu verschweigender negativer Punkt ist, dass zwar die Steuer in Höhe von 5% nicht fällig wird, dass allerdings auf Gewinne eine etwas seltsame Service Gebühr in Höhe von 3€ bei Betworld angerechnet wird. Man bekommt also weniger Geld als man eigentlich nach einem Gewinn bekommen würde. Wohin dieser Gewinn fließt, ob nicht vielleicht doch an das deutsche Finanzamt, konnte nicht in Erfahrung gebracht werden. Die Einschätzung „Wettanbieter ohne Wettsteuer“ mag also stimmen, relativiert sich jedoch ein bisschen.</p>
                <p>
                  <a href="#" class="btn btn-buy btn-blok">JETZT OHNE STEUER BEI BETWORLD WETTEN!</a>
                  <a href="#" class="btn btn-detail btn-blok">Mehr über Betworld</a>
                </p>
              </div>
            </div>
          </div>
          <h3>Wettsteuer.com zeigt, dass es auch ohne Wettsteuer geht</h3>
          <p>Natürlich war die Einführung der Wettsteuer zunächst eine herbe Nachricht für die vielen Fans von Sportwetten. Wettsteuer.com zeigt aber, dass es auch anders geht und informiert stets aktuell über Wettanbieter ohne Steuer. Darüber hinaus werfen die Spezialisten von wettsteuer.com natürlich einen ganz genauen Blick auf das gesamte Angebot der verschiedenen Wettanbieter, so dass Sie immer schnell in Erfahrung bringen können, wo das attraktivste Angebot mit der besten Quote auf Sie wartet.</p>
          <p>Über die Wettsteuer informiert sein! Die Wettsteuer umgehen und ohne 5% Steuer wetten. Wettsteuer.com zeigt Ihnen wie es geht – Durch den neuen Glückspielstaatsvertrag, der Anfang Juli in Deutschland in Kraft getreten ist, hat sich im Bereich Sportwetten im Internet, beim einen oder anderen Wettanbieter einiges geändert. Grundsätzlich muss ab sofort beachtet werden, dass in Deutschland eine Wettsteuer von 5% auf Sportwetten erhoben wird, die von den Anbietern von Sportwetten im Internet, an das Finanzamt abgeführt werden muss.</p>
          <p>Unterschiedliches Handling der Wettsteuer für die Endverbraucher – Wettsteuer.com informiert<br> Dies hat zur Folge, dass man als Kunde, wenn man zum Beispiel Sportwetten in Höhe von 100 Euro platzieren will, nach Abzug der Wettsteuer, nur noch 95 Euro für die Wetten zur Verfügung hat. Andere Online Wettbüros behalten die 5% Wettsteuer dahingehend ein, dass diese direkt von den Umsätzen, welche ein Kunde mit seinen Sportwetten getätigt hat, abgezogen wird.</p>
          <p>Die Wettsteuer wird in diesem Fall also direkt von den erzielten Gewinnen abgezogen, wobei der Bruttogewinn anhand des Einsatzes bei den Wetten und der jeweiligen Quote errechnet wird. Die Wettquote insgesamt, verringert sich natürlich in jedem Fall für die einzelnen Spieler, egal auf welche Art und Weise die Wettsteuer berechnet wird.</p>
        </div>
      </div>
    </main>
    <footer>
      <div class="footer-bottom">
        <div class="container">
          <div class="row">
            <div class="col-sm-12">
              <p>Unsere Wettanbieter wurden verifiziert durch:</p>
              <div class="copyright">Copyright 2020 © Wettsteuer.com | All Rights Reserved | <a href="#">Impressum</a> | <a href="#">Datenschutz</a></div>
              <div class="scrollup d-none" id="up">
                <span class="first-arrow"></span>
                <span class="second-arrow"></span>
              </div>
            </div>
          </div>
        </div>
      </div>
    </footer>
  </div>
</template>

<script>
import catalogItem from "./catalog-item.vue"

export default {
  name: "Main",
  components: {
    catalogItem
  },
  data() {
    return {
      products: [
        {
          article: "1",
          image: "https://wettsteuer.com/wp-content/uploads/2020/04/22bet.png",
          name: "22bet Wettsteuer",
          bonus: "100% bis zu 122€",
          mindestquote: "1.40",
          bewertung: "9.7",
          zumAnbieter: "OHNE STEUER WETTEN"
        },
        {
          article: "2",
          image: "https://wettsteuer.com/wp-content/uploads/2020/04/lsbet.png",
          name: "LSbet Wettsteuer",
          bonus: "200% bis zu 200€",
          mindestquote: "1.70",
          bewertung: "9.5",
          zumAnbieter: "OHNE STEUER WETTEN"
        },
        {
          article: "3",
          image: "https://wettsteuer.com/wp-content/uploads/2020/08/stake-logo-200x101-.png",
          name: "Stake.com Wettsteuer",
          bonus: "100 $ in Krypto",
          mindestquote: "",
          bewertung: "8.9",
          zumAnbieter: "JETZT WETTEN"
        },
        {
          article: "4",
          image: "https://wettsteuer.com/wp-content/uploads/2020/04/william-hill.png",
          name: "William Hill Wettsteuer",
          bonus: "100% bis zu 100€",
          mindestquote: "1.80",
          bewertung: "8.9",
          zumAnbieter: "OHNE STEUER WETTEN"
        },
        {
          article: "5",
          image: "https://wettsteuer.com/wp-content/uploads/2020/07/MegaPari-logo-200x101-.png",
          name: "Megapari Wettsteuer",
          bonus: "100% bis zu 100€",
          mindestquote: "1.40",
          bewertung: "8.7",
          zumAnbieter: "OHNE STEUER WETTEN"
        },
        {
          article: "6",
          image: "https://wettsteuer.com/wp-content/uploads/2020/04/melbet.png",
          name: "Melbet Wettsteuer",
          bonus: "100% bis zu 100€",
          mindestquote: "1.40",
          bewertung: "8.7",
          zumAnbieter: "JETZT WETTEN"
        },
        {
          article: "7",
          image: "https://wettsteuer.com/wp-content/uploads/2020/04/guts.png",
          name: "Guts Wettsteuer",
          bonus: "100% bis zu 50€",
          mindestquote: "1.80",
          bewertung: "8.5",
          zumAnbieter: "OHNE STEUER WETTEN"
        },
        {
          article: "8",
          image: "https://wettsteuer.com/wp-content/uploads/2020/04/bet3000.png",
          name: "Bet3000 Wettsteuer",
          bonus: "100% bis zu 150€",
          mindestquote: "2.00",
          bewertung: "8.4",
          zumAnbieter: "OHNE STEUER WETTEN"
        },
        {
          article: "9",
          image: "https://wettsteuer.com/wp-content/uploads/2020/04/campobet.png",
          name: "CampoBet Wettsteuer",
          bonus: "100% bis zu 250€",
          mindestquote: "2.00",
          bewertung: "8.3",
          zumAnbieter: "JETZT WETTEN"
        },
        {
          article: "10",
          image: "https://wettsteuer.com/wp-content/uploads/2020/04/buff-bet.png",
          name: "BUFF.bet Wettsteuer",
          bonus: "100% bis zu 100€",
          mindestquote: "1.70",
          bewertung: "8.1",
          zumAnbieter: "OHNE STEUER WETTEN"
        },
        {
          article: "11",
          image: "https://wettsteuer.com/wp-content/uploads/2020/04/reloadbet.png",
          name: "ReloadBet Wettsteuer",
          bonus: "100% bis zu 200€",
          mindestquote: "1.50",
          bewertung: "7.7",
          zumAnbieter: "OHNE STEUER WETTEN"
        },
        {
          article: "12",
          image: "https://wettsteuer.com/wp-content/uploads/2020/04/b-bets-sport.png",
          name: "b-Bets Sport Wettsteuer",
          bonus: "100% bis zu 100€",
          mindestquote: "1.80",
          bewertung: "7.7",
          zumAnbieter: "JETZT WETTEN"
        },
        {
          article: "13",
          image: "https://wettsteuer.com/wp-content/uploads/2020/04/betfair.png",
          name: "Betfair Wettsteuer",
          bonus: "Wetten mit verbesserten Quoten",
          mindestquote: "-",
          bewertung: "7.7",
          zumAnbieter: "OHNE STEUER WETTEN"
        },
        {
          article: "14",
          image: "https://wettsteuer.com/wp-content/uploads/2020/04/doublebet.png",
          name: "DoubleBet Wettsteuer",
          bonus: "100% bis zu 130€",
          mindestquote: "1.70",
          bewertung: "7.7",
          zumAnbieter: "OHNE STEUER WETTEN"
        },
        {
          article: "15",
          image: "https://wettsteuer.com/wp-content/uploads/2020/04/betwinner.png",
          name: "Betwinner Wettsteuer",
          bonus: "100% bis zu 100€",
          mindestquote: "1.40",
          bewertung: "7.6",
          zumAnbieter: "JETZT WETTEN"
        },
        {
          article: "16",
          image: "https://wettsteuer.com/wp-content/uploads/2020/04/1xbet.png",
          name: "1xBet Wettsteuer",
          bonus: "100% bis zu 130€",
          mindestquote: "1.40",
          bewertung: "7.6",
          zumAnbieter: "OHNE STEUER WETTEN"
        },
        {
          article: "17",
          image: "https://wettsteuer.com/wp-content/uploads/2020/04/intertops.png",
          name: "Intertops Wettsteuer",
          bonus: "50% bis zu 200€",
          mindestquote: "1.50",
          bewertung: "7.6",
          zumAnbieter: "OHNE STEUER WETTEN"
        },
        {
          article: "18",
          image: "https://wettsteuer.com/wp-content/uploads/2020/04/1xbit.png",
          name: "1xBit Wettsteuer",
          bonus: "100% bis zu 1bitcoin",
          mindestquote: "1.60",
          bewertung: "7.6",
          zumAnbieter: "JETZT WETTEN"
        },
        {
          article: "19",
          image: "https://wettsteuer.com/wp-content/uploads/2020/04/betboro.png",
          name: "BetBoro Wettsteuer",
          bonus: "50% bis zu 100€",
          mindestquote: "1.90",
          bewertung: "7.6",
          zumAnbieter: "OHNE STEUER WETTEN"
        },
        {
          article: "20",
          image: "https://wettsteuer.com/wp-content/uploads/2020/04/sportsbet-io.png",
          name: "Sportsbet.io Wettsteuer",
          bonus: "300% bis zu 0.006bitcoin",
          mindestquote: "1.50",
          bewertung: "7.6",
          zumAnbieter: "OHNE STEUER WETTEN"
        },
        {
          article: "21",
          image: "https://wettsteuer.com/wp-content/uploads/2020/04/18bet.png",
          name: "18Bet Wettsteuer",
          bonus: "100% bis zu 125€",
          mindestquote: "1.80",
          bewertung: "7.6",
          zumAnbieter: "JETZT WETTEN"
        },
        {
          article: "22",
          image: "https://wettsteuer.com/wp-content/uploads/2020/04/betworld.png",
          name: "Betworld Wettsteuer",
          bonus: "100% bis zu 100€",
          mindestquote: "1.70",
          bewertung: "7.6",
          zumAnbieter: "OHNE STEUER WETTEN"
        },
        {
          article: "23",
          image: "https://wettsteuer.com/wp-content/uploads/2020/04/sportingbet.png",
          name: "Sportingbet Wettsteuer",
          bonus: "100% bis zu 180€",
          mindestquote: "1.70",
          bewertung: "7.6",
          zumAnbieter: "OHNE STEUER WETTEN"
        },
        {
          article: "24",
          image: "https://wettsteuer.com/wp-content/uploads/2020/04/neo-bet.png",
          name: "NEO.bet Wettsteuer",
          bonus: "100% bis zu 150€",
          mindestquote: "1.50",
          bewertung: "7.6",
          zumAnbieter: "JETZT WETTEN"
        },
        {
          article: "25",
          image: "https://wettsteuer.com/wp-content/uploads/2020/04/wirwetten.png",
          name: "WirWetten Wettsteuer",
          bonus: "100% bis zu 200€",
          mindestquote: "1.80",
          bewertung: "7.5",
          zumAnbieter: "OHNE STEUER WETTEN"
        },
        {
          article: "26",
          image: "https://wettsteuer.com/wp-content/uploads/2020/04/tipwin.png",
          name: "tipwin Wettsteuer",
          bonus: "100% bis zu 100€",
          mindestquote: "1.80",
          bewertung: "7.4",
          zumAnbieter: "OHNE STEUER WETTEN"
        },
        {
          article: "27",
          image: "https://wettsteuer.com/wp-content/uploads/2020/04/bonkersbet.png",
          name: "BonkersBet Wettsteuer",
          bonus: "100% bis zu 100€",
          mindestquote: "2.00",
          bewertung: "7.4",
          zumAnbieter: "JETZT WETTEN"
        },
        {
          article: "28",
          image: "https://wettsteuer.com/wp-content/uploads/2020/04/beteast.png",
          name: "BetEast Wettsteuer",
          bonus: "Kein Bonus",
          mindestquote: "0.00",
          bewertung: "7.4",
          zumAnbieter: "OHNE STEUER WETTEN"
        },
        {
          article: "29",
          image: "https://wettsteuer.com/wp-content/uploads/2020/04/betsson.png",
          name: "Betsson Wettsteuer",
          bonus: "100% bis zu 100€",
          mindestquote: "1.80",
          bewertung: "7.4",
          zumAnbieter: "OHNE STEUER WETTEN"
        },
        {
          article: "30",
          image: "https://wettsteuer.com/wp-content/uploads/2020/04/betadonis.png",
          name: "BetAdonis Wettsteuer",
          bonus: "25% bis zu 75€",
          mindestquote: "2.00",
          bewertung: "6.9",
          zumAnbieter: "JETZT WETTEN"
        },
        {
          article: "31",
          image: "https://wettsteuer.com/wp-content/uploads/2020/04/fastbet.png",
          name: "Fastbet Wettsteuer",
          bonus: "5% bis zu 50€",
          mindestquote: "1.80",
          bewertung: "6.2",
          zumAnbieter: "JETZT WETTEN"
        }
      ],
      isOpen: false,
      isOpen_1: false,
      isOpen_2: false,
      isOpen_3: false,
      activeItem: '22Bet'
    }
  },
  methods: {
    onClick () {
      this.isOpen = !this.isOpen
    },
    onClick_1 () {
      if (document.documentElement.clientWidth >= 992) {
        this.isOpen_1 = true
      } else {
        this.isOpen_1 = !this.isOpen_1
      }
    },
    onClick_2 () {
      if (document.documentElement.clientWidth >= 992) {
        this.isOpen_2 = true
      } else {
        this.isOpen_2 = !this.isOpen_2
      }
    },
    onClick_3 () {
      if (document.documentElement.clientWidth >= 992) {
        this.isOpen_3 = true
      } else {
        this.isOpen_3 = !this.isOpen_3
      }
    },
    isActive (menuItem) {
      return this.activeItem === menuItem
    },
    setActive (menuItem) {
      this.activeItem = menuItem
    }
  },
  mounted () {
    var navbar = document.getElementById('top-a')
    if (document.documentElement.clientWidth >= 992) {
      window.onscroll = function () {navbarF(), teaserF()}
    } else {
      window.onscroll = function () {teaserF()}
      navbar.classList.add('fixed-top')
    }
    var fixed = navbar.offsetTop
    var teaser = document.getElementById('teaser')
    var teaserOffSetTop = teaser.offsetTop
    function navbarF () {
      if (window.pageYOffset >= fixed) {
        navbar.classList.add('fixed-top')
      } else {
        navbar.classList.remove('fixed-top')
      }
    }
    function teaserF () {
      if (window.pageYOffset >= teaserOffSetTop) {
        document.getElementById('up').classList.remove('d-none')
      } else {
        document.getElementById('up').classList.add('d-none')
      }
    }
    if (document.documentElement.clientWidth >= 992) {
      document.getElementById('menu_1').click()
      document.getElementById('menu_2').click()
      document.getElementById('menu_3').click()
    }
    document.getElementById('up').onclick = function () {
      document.getElementById('head').scrollIntoView({
        behavior: 'smooth',
        block: 'start'
      })
    }
  }
}
</script>

<style scoped lang="scss">
  header {
    background-color: rgba(255, 255, 255, 1);
    .navbar {
      background-color: #005abc;
      height: 50px;
      #navbarSupportedContent {
        .nav {
          .dropdown {
            a {
              color: #fff;
              text-shadow: 0 1px 0 rgba(0,0,0,.25);
              text-transform: uppercase;
              display: flex;
              padding: 0 8px;
              span {
                margin: auto;
              }
              .caret {
                width: 0;
                height: 0;
                border-top: 4px solid;
                border-right: 4px solid transparent;
                border-left: 4px solid transparent;
                margin: auto 4px;
              }
            }
            .dropdown-menu {
              box-shadow: 0 6px 12px rgba(0,0,0,.175);
              z-index: 1000;
              margin: 0;
              padding: 5px 0;
              border: unset;
              border-radius: unset;
              li {
                float: left;
              }
            }
            .third-menu {
              .third-item {
                width: 100%;
              }
            }
          }
        }
      }
    }
  }
  main {
    .teaser {
      position: relative;
      color: #fff;
      h1 {
        position: absolute;
        right: 20%;
        left: 20%;
        bottom: 50%;
        transform: translateY(50%);
        margin-bottom: 0;
        font-weight: 400;
        text-shadow: 0 1px 2px rgba(0,0,0,.6);
        font-size: 28px;
        line-height: 1.1;
      }
    }
    .content {
      padding: 30px 0;
      p {
        text-align: justify;
        margin: 0 0 10px;
        img {
          display: block;
          max-width: 100%;
          height: auto;
        }
        .align-right {
          float: right;
          margin: 5px 0 10px 15px;
        }
        strong {
          font-weight: 600;
        }
      }
      ul {
        margin-bottom: 40px;
        a:hover {
          color: #ebaa3d;
        }
      }
      .align-left {
        float: left;
        margin: 0 15px 10px 0;
      }
      .headline {
        color: #4080ff;
        font-size: 24px;
        margin: 20px 0 10px;
      }
      .blogposts {
        margin: 20px 0;
        .artical {
          display: block;
          img:hover {
            opacity: .5;
          }
        }
        a {
          color: #101820;
          font-size: 17px;
          line-height: 1.1;
          &:hover {
            text-decoration: none;
            color: #4080ff;
          }
        }
      }
      h2 {
        color: #3e7cf7;
        font-weight: 400;
        font-size: 1.75rem;
        line-height: 1.1;
        margin-top: 20px;
        margin-bottom: 10px;
      }
      h3 {
        margin-top: 20px;
        margin-bottom: 10px;
        line-height: 1.1;
        color: #3e7cf7;
        font-weight: 400;
        font-size: 1.375rem;
      }
      h4 {
        font-weight: 400;
        color: #3e7cf7;
        font-size: 1.125rem;
        margin-top: 10px;
        margin-bottom: 10px;
        line-height: 1.1;
      }
      .table {
        margin: 30px 0;
        thead {
          background-color: #0151a8;
          color: #fff;
          font-weight: 700;
          th {
            padding: 8px;
          }
        }
        tbody {
          tr:nth-of-type(2n+1){
            background-color: #fff;
          }
          tr:nth-of-type(2n){
            background-color: #f9f9f9;
          }
          tr:hover {
            background-color: #f3f3f3;
          }
          td {
            vertical-align: middle;
            padding: 8px;
            color: #424242;
            img {
              max-width: 120px;
              height: auto;
            }
            a {
              color: #4080ff;
              display: flex;
              justify-content: center;
              font-size: 12px;
              &:hover {
                color: #ebaa3d;
              }
            }
            .btn-buy {
              font-size: 14px;
              color: #fff;
              background-color: #f3961d;
              border-color: #f3961d;
              display: inline-block;
              padding: 6px 12px;
              border-radius: 4px;
              &:hover {
                background-color: #f4a033;
                border-color: #f4a033;
                color: #fff;
                text-decoration: none;
              }
            }
            .exclusive {
              color: #0151a8;
            }
          }
        }
      }
      .tab-panel {
        .nav-tabs {
          border-bottom: unset;
          margin-bottom: 0;
          .nav-item {
            flex-grow: unset;
            margin-right: 8px;
            &:last-child {
              margin-right: 0;
            }
            .nav-link {
              border-radius: 0;
              padding: 7px 20px;
              background: #1d2534;
              color: #fff;
              border: unset;
              &:hover {
                color: #fff;
                background-color: #4080ff;
              }
            }
            .active {
              color: #fff;
              background-color: #4080ff;
              cursor: default;
              border-color: unset;
            }
          }
        }
        #myTabContent {
          border: 1px solid #f0f0f0;
          padding: 10px;
          a:hover {
            color: #ebaa3d;
          }
          .btn {
            line-height: 1.42857143;
            font-size: 14px;
            color: #fff;
            padding: 6px 12px;
            border-radius: 4px;
            &:hover {
              color: #fff;
              text-decoration: none;
            }
          }
          .btn-buy {
            background-color: #f3961d;
            border-color: #f3961d;
            &:hover {
              background-color: #f4a033;
              border-color: #f4a033;
            }
          }
          .btn-detail {
            background-color: #9fa2a5;
            border-color: #9fa2a5;
            margin-top: 5px;
            margin-bottom: 30px;
            &:hover {
              background-color: #a8abae;
              border-color: #a8abae;
            }
          }
          .btn-blok {
            display: block;
            width: 100%;
          }
        }
      }
    }
  }
  footer {
    .footer-bottom {
      padding: 20px 0;
      border-top: 1px solid #f0f0f0;
      p {
        min-height: 170px;
        text-align: center;
        padding: 35px 0;
        font-size: 18px;
        background: url(https://wettsteuer.com/wp-content/themes/affiliatetheme-child/assets/images/sponsorlogos.png) center 75% no-repeat #fafafa;
        margin: 0;
        background-size: contain;
      }
      .copyright {
        text-align: center;
        font-size: 14px;
        a {
          color: inherit;
          &:hover {
            color: inherit;
          }
        }
      }
      .scrollup {
        width: 50px;
        height: 50px;
        background-color: #000;
        border-radius: 25px;
        position: fixed;
        bottom: 30px;
        right: 30px;
        cursor: pointer;
        .first-arrow {
          background-color: #fff;
          width: 15px;
          height: 4px;
          display: block;
          position: absolute;
          top: 22px;
          left: 13px;
          transform: rotate(-45deg);
        }
        .second-arrow {
          background-color: #fff;
          width: 15px;
          height: 4px;
          display: block;
          position: absolute;
          top: 22px;
          right: 13px;
          transform: rotate(45deg);
        }
      }
    }
  }
  @media all and (max-width: 992px) {
    header {
      .d-non {
        display: none;
      }
      .navbar{
        .min-logo {
          display: inline;
          height: 26px;
          position: absolute;
          top: 50%;
          transform: translateY(-50%);
        }
        .icon-bar {
          display: block;
          width: 22px;
          height: 2px;
          border-radius: 1px;
          background-color: #fff;
          box-shadow: 0 1px 0 rgba(0,0,0,.25);
          &:nth-child(2) {
            margin: 4px 0;
          }
        }
        #navbarSupportedContent {
          z-index: 1000;
          height: 150px;
          position: absolute;
          top: 50px;
          right: 0;
          left: 0;
          background-color: #005abc;
          .nav {
            border-top: 1px solid #fff;
            flex-wrap: unset;
            .dropdown {
              background-color: #005abc;
              a {
                &:hover {
                  text-decoration: none;
                }
                .blok {
                  display: inline-block;
                  width: 0;
                  height: 0;
                  border-top: 4px solid #005abc;
                  border-right: 4px solid #005abc;
                  border-left: 4px solid #005abc;
                  margin: auto 4px;
                }
              }
              .dropdown-menu {
                background-color: #005abc;
                display: inline;
                position: absolute;
                li {
                  width: 50%;
                  a {
                    color: #fff;
                    font-size: 13px;
                    font-weight: 600;
                    padding: 0 0 0 20px;
                  }
                }
              }
              .third-menu {
                width: 100%;
              }
            }
          }
        }
      }
    }
    main {
      font-size: 14px;
      .teaser {
        margin-top: 50px;
      }
      .content {
        h2 {
          font-size: 24px;
        }
        h3 {
          font-size: 19px;
        }
        h4 {
          font-size: 15px;
        }
        .blogposts {
          img {
            width: 220px;
          }
          h2 {
            font-size: 14px;
          }
        }
      }
    }
  }
  @media all and (min-width: 992px) {
    header {
      .brand {
        margin: 30px 0;
        display: inherit;
      }
      .navbar {
        .a-min-logo, .min-logo {
          display: none;
        }
        #navbarSupportedContent {
          height: 100%;
          .nav {
            .dropdown {
              &:hover {
                background-color: #fff;
                .dropdown-menu {
                  display: inline;
                }
                a {
                  color: #005abc;
                  text-decoration: none;
                }
              }
              a {
                height: 100%;
              }
              .dropdown-menu {
                min-width: 480px;
                li {
                  width: 33.33%;
                  &:hover {
                    cursor: pointer;
                    a {
                      color: #fff;
                      background-color: #005abc;
                    }
                  }
                }
                a {
                  font-size: 13px;
                  font-weight: 600;
                  padding: 7px 0 7px 20px;
                }
              }
              .third-menu {
                min-width: 240px;
              }
            }
          }
        }
      }
    }
  }
  @media all and (max-width: 768px) {
    main {
      .container {
        .content {
          .table {
            td:nth-of-type(3), td:nth-of-type(4), th:nth-of-type(3), th:nth-of-type(4) {
              display: none;
            }
            img {
              max-width: 80px;
            }
            .btn-buy {
              font-size: 11px;
            }
          }
          .align-right {
            width: 100%;
          }
          .align-left {
            max-width: 100%;
          }
          .blogposts {
            img {
              width: 300px;
            }
            .row {
              display: block;
              .col-sm-4 {
                max-width: 100%;
                a {
                  font-size: 15px;
                }
              }
            }
          }
          .nav-item {
            margin-top: 8px;
          }
        }
      }
    }
  }
  @media all and (max-width: 360px) {
    main {
      .container {
        .content {
          .table {
            td {
              position: relative;
            }
            td, th {
              font-size: 12px;
            }
            img {
              max-width: 70px;
            }
            a {
              font-size: 10px;
            }
            .btn-buy {
              font-size: 9px;
            }
          }
          .blogposts {
            img {
              max-width: 100%;
            }
          }
        }
      }
    }
  }
</style>
