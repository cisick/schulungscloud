
<template>

<!--'Abschnitt: Header der Webseite'-->
<div >
  <!--' Es wird ein <div>-Tag mit der CSS-Klasse "svelte-vi705s" versehen, um es wie einen Header zu gestalten.
  "svelte-vi705s" ist eine automatisch von dem Framework Svelte generierte CSS Klasse, 
  die zur Formatierung der Webseite genutzt wurde.
  In der Webseite wird so der Kopf mit der Überschrift und dem Bild im Hintergrund gestaltet.
  '-->
  <div class="header svelte-vi705s">
    <!--' Das div mit der Klasse text-wrapper enthält den Text der Übrschrift und das Logo. '-->
    <div class="text-wrapper svelte-vi705s">
      <div>
        <img src="./assets/logo.83630b48.webp" alt="Schulungs.Cloud" width="auto" height="auto" id="logo" class="svelte-vi705s">
        <h3 class="svelte-vi705s">Sehen Sie, wie KI das eLearning verändern wird.</h3>
      </div>
    </div>
 
    <div class="wrapper svelte-gnsllk"><div id="background" class="svelte-gnsllk"></div></div>
  </div>

<!--'Abschnitt: Reiter zum Auswählen der Themen -->
  <div class="wrapper svelte-a3x9i2"></div>
  <div class="top svelte-1tqazs7">
    <!-- Navigationselement -->
    <nav id="navbar" class="navbar navbar-expand-lg svelte-qkfvko">
      <!-- Logo und Link zur Startseite -->
      <a class="navbar-brand svelte-qkfvko" href="#top">
        <img src="./assets/logo-rgb.aa062cf4.png" alt="Schulungs.Cloud" class="svelte-qkfvko">
      </a>
      <!-- Toggler Button für mobile Navigation -->
      <button class="navbar-toggler svelte-qkfvko" type="button" aria-expanded="false" aria-label="Navigation öffnen">
        <span class="navbar-toggler-icon svelte-qkfvko"></span>
      </button>
       <!-- Container für Navigationselemente -->
      <div class="navbar-collapse svelte-qkfvko">
        <!-- Liste der Navigationselemente -->
        <ul class="nav nav-pills svelte-qkfvko">
          <!-- Navigationselement nur sichtbar auf kleinen Bildschirmen -->
          <li class="nav-item d-block d-lg-none svelte-qkfvko">
            <a href="navbar" class="nav-link svelte-qkfvko">
              <img src="./assets/logo-rgb.aa062cf4.png" alt="Schulungs.Cloud" class="svelte-qkfvko">
            </a>
          </li>
          <!-- Navigationselement "Start" -->
          <li class="nav-item svelte-qkfvko">
            <a class="nav-link active svelte-qkfvko" href="#start">Start<span class="svelte-qkfvko"></span></a>
          </li>
          <!-- Navigationselement "Funktionen" -->
          <li class="nav-item svelte-qkfvko">
            <a class="nav-link svelte-qkfvko" href="#funktionen">Funktionen<span class="svelte-qkfvko"></span></a>
          </li>
          <!-- Navigationselement "Kurse" -->
          <li class="nav-item svelte-qkfvko">
            <a class="nav-link svelte-qkfvko" href="#kurse">Kurse<span class="svelte-qkfvko"></span></a></li>
            <!-- Navigationselement "Registrieren" -->
          <li class="nav-item svelte-qkfvko"><a class="nav-link svelte-qkfvko" href="#registrieren">Registrieren<span class="svelte-qkfvko"></span></a>
          </li>
        </ul>
        <!-- Zusätzliche Navigationselemente für mobile Ansicht -->
        <ul class="nav nav-pills nav-mobile-close d-block d-lg-none svelte-qkfvko">
          <li class="nav-item svelte-qkfvko">
            <a class="nav-link svelte-qkfvko" href="#start">Navigation schließen<span class="svelte-qkfvko"></span></a>
          </li>
        </ul>
      </div>
      <!-- Kontaktbereich in der Navigation -->
      <div class="navbar-contact svelte-qkfvko"><span class="svelte-qkfvko">Rufen Sie uns an</span>
        <a href="tel:091197559200" class="svelte-qkfvko"><span class="fal fa-phone-office me-2 svelte-qkfvko"></span>0911 / 97 55 92 - 00</a>
      </div>
    </nav>
  </div>

  <!-- Karte 1-->
  <section id="start" class="svelte-nghi21">
    <!-- Ein Container-Element, das den Inhalt zentriert und formatiert. -->
    <div class="container">
      <!--Ein Container für eine Reihe von Spalten, normalerweise in einem Raster-Layout.-->
      <div class="row">
        <!--Eine Spalte, die auf großen Bildschirmen (large, lg) 4 von 12 Teilen einnimmt.-->
        <div class="col-lg-4">
          <!-- Formatierung der einzelnen Spalte-->
           <!-- Kartenüberschrift-->
          <div class="card my-2 my-lg-0 svelte-xknto1" data-align="center">
            <div class="card-body svelte-xknto1">
              <h3 class="card-title svelte-xknto1"><span slot="title">einfach.</span></h3>
              <!-- Definieren eines Elements um den blauen Strich darzustellen.-->
              <div class="card-separator svelte-xknto1"></div>
              <!-- Karteninhalt-->
              <div class="content svelte-xknto1">
                <span slot="content">Dank der <b>KI-gestützten Kursgenerierung</b> ist das Erstellen und Ausarbeiten neuer Schulungen einfacher denn je.</span>
              </div>
            </div>
          </div>
        </div>

  <!-- Karte 2-->
        <div class="col-lg-4">
          <div class="card my-2 my-lg-0 svelte-xknto1" data-align="center">
            <div class="card-body svelte-xknto1">
              <h3 class="card-title svelte-xknto1"><span slot="title">intuitiv.</span></h3>
              <div class="card-separator svelte-xknto1"></div>
              <div class="content svelte-xknto1">
                <span slot="content">Die <b>intuitiv gestaltete Benutzerführung</b> ermöglicht es auch unerfahrenen Bedienern, sich schnell in die Bedienung des Portals einzufinden.</span>
              </div>
            </div>
          </div>
        </div>

  <!-- Karte 3-->
        <div class="col-lg-4">
          <div class="card my-2 my-lg-0 svelte-xknto1" data-align="center">
            <div class="card-body svelte-xknto1">
              <h3 class="card-title svelte-xknto1"><span slot="title">günstig.</span></h3>
              <div class="card-separator svelte-xknto1"></div>
              <div class="content svelte-xknto1">
                <span slot="content">Niedrige Lizenzgebühren halten die Kosten auch für Unternehmen mit großer Benutzeranzahl <b>günstig</b> und stemmbar.</span>
              </div>
            </div>
          </div>
        </div>
      </div>

  <!-- Karte 4-->
      <div class="row mt-lg-4 justify-content-center">
        <!--Eine Spalte, die auf großen Bildschirmen (large, lg) 5 von 12 Teilen einnimmt.-->
        <div class="col-lg-5">
          <div class="card my-2 my-lg-0 svelte-xknto1" data-align="center">
            <div class="card-body svelte-xknto1">
              <h3 class="card-title svelte-xknto1"><span slot="title">ISO 27001 zertifiziert</span></h3>
              <div class="card-separator svelte-xknto1"></div>
              <div class="content svelte-xknto1">
                <span slot="content">
                  <a href="https://www.leibold-it.de/documents/ISO_27001_LEIBOLD.pdf" class="my-3 d-block" target="_blank" rel="noopener"><img src="./assets/tuev-sued-logo.b7ab5c87.webp" alt="TÜV SÜD zertifiziert" class="img-fluid svelte-nghi21"></a>
                </span>
              </div>
            </div>
          </div>
        </div>

  <!-- Karte 5--> 
        <div class="col-lg-5">
          <div class="card my-2 my-lg-0 svelte-xknto1" data-align="center">
            <div class="card-body svelte-xknto1">
              <h3 class="card-title svelte-xknto1"><span slot="title">IT Security made in Germany</span></h3>
              <div class="card-separator svelte-xknto1"></div>
              <div class="content svelte-xknto1">
                <span slot="content">
                  <a href="https://www.teletrust.de/itsmig/" class="my-3 d-block" target="_blank" rel="noopener"><img src="./assets/itsecurity.38ec5f37.svg" alt="IT Security made in Germany" class="img-fluid svelte-nghi21"></a>
                </span>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>

<!-- Das einfliegende Banner unter den Reitern.-->
    <div class="banner-container svelte-nghi21">
      <a href="/wim-oktober.pdf" target="_blank" rel="noopener" class="banner svelte-nghi21">
        <span class="svelte-nghi21">Der Schulungs.Cloud-Artikel in der WiM</span>
        <small class="svelte-nghi21"><span class="fal fa-download me-2"></span>PDF-Datei herunterladen</small>
      </a>
    </div>
  </section>

<!-- Abschnitt Funktionen-->
  <section id="funktionen">
    <!-- Unterabschnitt 1: Virtueller Referent dank KI-->
    <div class="feature feature-secondary d-flex align-items-center svelte-1kktozq">
      <div class="container d-block d-lg-flex align-items-center">
        <img src="./assets/megaphone.adabf0ca.svg" alt="" class="img-fluid img-icon-left svelte-1kktozq">
        <div class="feature-text svelte-1kktozq">
          <h2>Virtueller Referent dank KI</h2>
          <p class="text-justify">Eine KI gestützte Vertonungstechnologie ermöglicht es, Kurse automatisch mit einer Tonspur zu versehen und so einen <b>virtuellen Referenten</b> zum Einsatz zu bringen. Die Vertonung findet mit einem generierten, ausformulierten Text statt, welcher auf den Informationen des Kurses und der Module basiert. Dadurch ist sichergestellt, dass die Vertonung frei von Fehlinformationen ist.</p>
          <p class="text-justify">Das Vertonen selbst findet mit neuster Technologie basierend auf neuronalen Netzwerken statt. Hierdurch entstehend lebensechte Stimmen, welche kaum vom Vortragsstil menschlicher Referenten zu unterscheiden sind.</p>
          <ul>
            <li><b>Vertonung</b> mit wahlweise männlicher und weiblicher Stimme</li>
            <li><b>Auswahl und Parametrisierung</b> der Tonspur-Generierung für das perfekte Ergebnis </li>
            <li><b>AI generierter Vortragstext</b> basierend auf den vorgegebenen Informationen stellt inhaltliche Korrektheit sicher</li>
          </ul>
          <p class="text-justify">Mit dem <b>virtuellen Referenten</b> erhalten die Benutzer ein völlig neues eLearning-Erlebnis.</p>
        </div>
        <img src="./assets/megaphone.adabf0ca.svg" alt="" class="img-fluid img-icon-right svelte-1kktozq d-none">
      </div>
    </div>
    <!-- Unterabschnitt 2: ChatGPT generierter Inhalt-->
    <div class="feature feature-white d-flex align-items-center svelte-1kktozq">
      <div class="container d-block d-lg-flex align-items-center">
        <img src="./assets/chatgpt.a362957d.svg" alt="" class="img-fluid img-icon-left svelte-1kktozq d-none">
        
        <div class="feature-text svelte-1kktozq">
          <h2>ChatGPT generierter Inhalt</h2>
          <p class="text-justify">ChatGPT ist eine künstliche Intelligenz (KI), die mit ihrer GPT-3.5 Architektur für die natürliche Sprachverarbeitung und -generierung trainiert ist. Diese Technologie kann auf verschiedene Arten dazu beitragen, Kursinhalte zu erstellen:</p>
          <ul>
            <li><b>Strukturierung</b><br>ChatGPT kann mit der GPT-Technologie und dem umfangreichen Sprachtraining eine Grundstruktur und Gliederung für ein zufällig gewünschtes Kursthema ausarbeiten.</li>
            <li><b>Textgenerierung</b><br>ChatGPT kann Texte für Kursinhalte generieren. Ein Dozent gibt Anweisungen und Informationen ein und ChatGPT kann darauf basierend den erforderlichen Text ausformulieren und strukturieren.</li>
            <li><b>Personalisierung</b><br>ChatGPT kann auch für die Personalisierung von Kursinhalten verwendet werden, unter anderem, um mit einem entsprechenden Praxisbezug oder geeigneten Beispielen auch Ihre branchenbedingte Anwendungsfälle in Kurse einzubauen.</li>
          </ul>
          <p class="text-justify">Insgesamt kann die Technologie von ChatGPT dazu beitragen, den Prozess der Erstellung von Kursinhalten zu automatisieren, zu verbessern und insgesamt den Fortschritt zu beschleunigen.</p>
        </div>
        <img src="./assets/chatgpt.a362957d.svg" alt="" class="img-fluid img-icon-right svelte-1kktozq">
      </div>
    </div>
    <!-- Unterabschnitt 3: Inhalte kaufen war gestern-->
    <div class="feature feature-primary d-flex align-items-center svelte-1kktozq">
      <div class="container d-block d-lg-flex align-items-center">
        <img src="./assets/books.414975c2.svg" alt="" class="img-fluid img-icon-left svelte-1kktozq">
        <div class="feature-text svelte-1kktozq">
          <h2>Inhalte kaufen war gestern</h2>
          <p class="text-justify">Dank der <b>einfachen und schnellen Generierung</b> von neuen Kursen oder unserer <b>umfangreichen Kursbibliothek</b> mit vorbereiten Kursen müssen Sie keine Inhalte mehr von Drittanbietern zukaufen. Wählen Sie einfach einen passenden Kurs aus, weisen Sie diesen Ihren Benutzern zu und starten Sie mit dem digitalen Lernen.</p>
          <ul>
            <li><b>Kostenreduzierung</b> durch das Wegfallen von Inhaltszukauf</li>
            <li><b>Zeitersparnis</b> durch vorgefertigte Kursbibliothek und KI gestützte Software</li>
            <li><b>Niedrige Einstiegshürde</b> und schnelle Lernkurve dank intuitiv bedienbaren System.</li>
          </ul>
        </div>
        <img src="./assets/books.414975c2.svg" alt="" class="img-fluid img-icon-right svelte-1kktozq d-none">
      </div>
    </div>
  </section>
<!-- Abschnitt vorgefertigte Kurse-->
  <section id="kurse" class="svelte-18wrtac">
    <div class="container svelte-18wrtac">
      <h3 class="text-center">Kurse finden</h3>
      <h4 class="text-center">Durchsuchen Sie unsere große Auswahl an vorgefertigten Kursen</h4>
      <!-- Suchleiste-->
      <div class="searchbar svelte-z2pf3c"><input type="text" class="form-control svelte-1994qsi" placeholder="Suchbegriff eingeben, z.B. Hygiene-Schulung ..." value="">
        <div class="loader svelte-z2pf3c">
          <svg id="sc-loader-svg" data-name="sc-loader-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 103.85 89.59" style="width: 32px;" class="svelte-1y3s990 mono">
            <g id="sc-loader-svg-layer1" data-name="sc-loader-svg-layer1">
              <g>
                <g>
                  <path class="sc-loader-svg-red svelte-1y3s990" d="m84.61,25.56H29.61c1.49-10.99,10.93-19.49,22.32-19.49,9.74,0,18.1,6.08,21.22,14.94h6.34c-1.49-5.43-4.58-10.34-8.89-14.06-5.19-4.48-11.82-6.94-18.68-6.94-15.77,0-28.59,12.83-28.59,28.59v3.03h61.27c7.27,0,13.18,5.91,13.18,13.18s-5.91,13.18-13.18,13.18v6.07c10.61,0,19.25-8.63,19.25-19.25s-8.63-19.25-19.25-19.25Z" id="sc-loader-line1"></path>
                  <path class="sc-loader-svg-blue svelte-1y3s990" d="m19.25,64.04h55c-1.49,10.99-10.93,19.49-22.32,19.49-9.74,0-18.1-6.08-21.22-14.94h-6.34c1.49,5.43,4.58,10.34,8.89,14.06,5.19,4.48,11.82,6.94,18.68,6.94,15.77,0,28.59-12.83,28.59-28.59v-3.03H19.25c-7.27,0-13.18-5.91-13.18-13.18s5.91-13.18,13.18-13.18v-6.07C8.63,25.54,0,34.17,0,44.79s8.63,19.25,19.25,19.25Z" id="sc-loader-line2"></path>
                </g>
                <g>
                  <path class="sc-loader-svg-blue svelte-1y3s990" d="m33.62,44.8c0,2.84-2.3,5.14-5.14,5.14s-5.14-2.3-5.14-5.14,2.3-5.14,5.14-5.14,5.14,2.3,5.14,5.14Z" id="sc-loader-dot1"></path>
                  <path class="sc-loader-svg-blue svelte-1y3s990" d="m57.07,44.8c0,2.84-2.3,5.14-5.14,5.14s-5.14-2.3-5.14-5.14,2.3-5.14,5.14-5.14,5.14,2.3,5.14,5.14Z" id="sc-loader-dot2"></path>
                  <path class="sc-loader-svg-blue svelte-1y3s990" d="m80.52,44.8c0,2.84-2.3,5.14-5.14,5.14s-5.14-2.3-5.14-5.14,2.3-5.14,5.14-5.14,5.14,2.3,5.14,5.14Z" id="sc-loader-dot3"></path>
                </g>
              </g>
            </g>
          </svg>
        </div>
      </div>

      <!-- Abschnitt Tags-->
      <div class="row">
        <!--Eine Spalte, die auf großen Bildschirmen (large, lg) 3 von 12 Teilen einnimmt.-->
        <div class="col-lg-3">
          <h4>Tags</h4>
          <div class="tags svelte-z2pf3c">
            <span class="svelte-6paitv">Büroalltag</span>
            <span class="svelte-6paitv">Organisation</span>
            <span class="svelte-6paitv">Ergonomie</span>
            <span class="svelte-6paitv">Gesundheit</span>
            <span class="svelte-6paitv">Einkauf</span>
            <span class="svelte-6paitv">Human Resources</span>
            <span class="svelte-6paitv">Führungskräfte</span>
            <span class="svelte-6paitv">Recht</span>
            <span class="svelte-6paitv">Gesetz</span>
            <span class="svelte-6paitv">Datenschutz</span>
            <span class="svelte-6paitv">Informationssicherheit</span>
          </div>
        </div>
        <div class="col-lg-9 course-list">
          <h4>Kurse</h4>
          <div class="row">
            <!--Eine Spalte, die auf großen Bildschirmen (large, lg) 4 von 12 Teilen einnimmt.-->
            <div class="col-lg-4 d-flex">
              <div class="card svelte-19v7hip">
                <img src="https://elearning.schulungs.cloud/api/v1/course/23/image/2949ce7e-8bcc-48a0-a4c4-27cf9c776435.jpg" alt="" class="card-header svelte-19v7hip">
                <div class="card-body">
                  <h3 class="card-title">Datenschutz Grundlagen</h3>
                  <p class="svelte-19v7hip">In diesem Kurs werden die absoluten Grundlagen zum Thema Datenschutz vermittelt. Vermittelt wird, was Datenschutz ist, was die rechtlichen Grundlagen sind bzw. welche vorgaben sich durch die DSGVO auf unser Leben ergeben.</p>
                </div>
              </div>
            </div>
            <div class="col-lg-4 d-flex">
              <div class="card svelte-19v7hip">
                <img src="https://elearning.schulungs.cloud/api/v1/course/21/image/4edc277b-0019-4545-946d-98cefe4323fb.jpg" alt="" class="card-header svelte-19v7hip">
                <div class="card-body">
                  <h3 class="card-title">Einführung in Vertragsrecht</h3>
                  <p class="svelte-19v7hip">Einführung in Vertragsrecht</p>
                </div>
              </div>
            </div>
            <div class="col-lg-4 d-flex">
              <div class="card svelte-19v7hip">
                <img src="https://elearning.schulungs.cloud/api/v1/course/16/image/4d2b5878-f594-4236-a39d-13488702ac9f.jpg" alt="" class="card-header svelte-19v7hip">
                <div class="card-body">
                  <h3 class="card-title">Grundlagen der Arbeitsplatzergonomie</h3>
                  <p class="svelte-19v7hip">In dieser Schulungen werden die Grundlagen zum Thema Arbeitsplatzergonomie erklärt.</p>
                </div>
              </div>
            </div>
            <div class="col-lg-4 d-flex">
              <div class="card svelte-19v7hip">
                <img src="https://elearning.schulungs.cloud/api/v1/course/18/image/f3e9f6c8-bd44-4482-96b3-445b9f8e4d12.jpg" alt="" class="card-header svelte-19v7hip">
                <div class="card-body">
                  <h3 class="card-title">Grundlagen der Beschaffung</h3>
                  <p class="svelte-19v7hip">In dieser Schulung werden Ihnen die Grundlagen der Beschaffung näher gebracht.</p>
                </div>
              </div>
            </div>
            <div class="col-lg-4 d-flex">
              <div class="card svelte-19v7hip">
                <img src="https://elearning.schulungs.cloud/api/v1/course/22/image/2d10d251-05b6-49b9-9e91-220f80676ac3.jpg" alt="" class="card-header svelte-19v7hip">
                <div class="card-body">
                  <h3 class="card-title">Grundlagen der ergonomischen Gestaltung von Bildschirmarbeitsplätzen</h3>
                  <p class="svelte-19v7hip">In dieser Schulung werden die Grundlagen einer ergonomischen Ausgestaltung von Bildschirmarbeitsplätzen erläutert.</p>
                </div>
              </div>
            </div>
            <div class="col-lg-4 d-flex">
              <div class="card svelte-19v7hip">
                <img src="https://elearning.schulungs.cloud/api/v1/course/19/image/b081aae0-ed95-40ee-bec9-f42b4b3b03a8.png" alt="" class="card-header svelte-19v7hip">
                <div class="card-body">
                  <h3 class="card-title">Grundlagen der Mitarbeiterführung</h3>
                  <p class="svelte-19v7hip">In dieser Schulung sollen Grundlagen zur Mitarbeiterführung vermittelt werden</p>
                </div>
              </div>
            </div>
            <div class="col-lg-4 d-flex">
              <div class="card svelte-19v7hip">
                <img src="https://elearning.schulungs.cloud/api/v1/course/29/image/422b51fe-2849-43d6-a9a8-28aad41c78c5.jpg" alt="" class="card-header svelte-19v7hip">
                <div class="card-body">
                  <h3 class="card-title">Interkulturelle Kompetenz</h3>
                  <p class="svelte-19v7hip">Interkulturelle Kompetenz im Wirtschaftsleben.</p>
                </div>
              </div>
            </div>
            <div class="col-lg-4 d-flex">
              <div class="card svelte-19v7hip">
                <img src="https://elearning.schulungs.cloud/api/v1/course/17/image/96085c19-8cd2-41bd-aea7-5a0d164798ba.jpg" alt="" class="card-header svelte-19v7hip">
                <div class="card-body">
                  <h3 class="card-title">Kommunikation am Arbeitsplatz</h3>
                  <p class="svelte-19v7hip">In dieser Schulung wird erklärt wie man sich am Arbeitsplatz verhalten sollte.</p>
                </div>
              </div>
            </div>
            <div class="col-lg-4 d-flex">
              <div class="card svelte-19v7hip">
                <img src="https://elearning.schulungs.cloud/api/v1/course/15/image/1b8161dd-b7f4-4cb2-a2bd-dec6940eda83.jpg" alt="" class="card-header svelte-19v7hip">
                <div class="card-body">
                  <h3 class="card-title">Zeitmanagement im Büroalltag</h3>
                  <p class="svelte-19v7hip">Zeitmanagement im Büroalltag - Ein Einstiegskurs in die Kunst des koordinierten und geplanten Zeitmanagements. 
          Lernen Sie die grundlegenden prinzipien kennen, Termine, Meilensteine und andere zeitkritische Fristen sinnvoll abzustimmen, ohne das Stress aufkommt.</p>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
      <div class="card-wrapper svelte-pvmg9g">
        <div class="card svelte-pvmg9g">
          <div class="close svelte-pvmg9g">
            <span class="far fa-times"></span>
          </div>
          <div class="card-header svelte-pvmg9g" style="background-image: url('')">
            <h3 class="card-title svelte-pvmg9g"></h3>
          </div>
          <div class="card-body svelte-pvmg9g">
            <div class="row svelte-pvmg9g">
              <div class="col-lg-4">
                <h4>Beschreibung</h4>
                <p class="svelte-pvmg9g"></p>
              </div>
              <div class="col-lg-8 structure svelte-pvmg9g">
                <h4>Gliederung</h4>
                <div class="d-flex align-items-center justify-content-center w-100 loader svelte-pvmg9g">
                  <div>
                    <div class="loader-wrapper svelte-pvmg9g">
                      <svg id="sc-loader-svg" data-name="sc-loader-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 103.85 89.59" style="" class="svelte-1y3s990">
                        <g id="sc-loader-svg-layer1" data-name="sc-loader-svg-layer1">
                          <g>
                            <g>
                              <path class="sc-loader-svg-red svelte-1y3s990" d="m84.61,25.56H29.61c1.49-10.99,10.93-19.49,22.32-19.49,9.74,0,18.1,6.08,21.22,14.94h6.34c-1.49-5.43-4.58-10.34-8.89-14.06-5.19-4.48-11.82-6.94-18.68-6.94-15.77,0-28.59,12.83-28.59,28.59v3.03h61.27c7.27,0,13.18,5.91,13.18,13.18s-5.91,13.18-13.18,13.18v6.07c10.61,0,19.25-8.63,19.25-19.25s-8.63-19.25-19.25-19.25Z" id="sc-loader-line1"></path>
                              <path class="sc-loader-svg-blue svelte-1y3s990" d="m19.25,64.04h55c-1.49,10.99-10.93,19.49-22.32,19.49-9.74,0-18.1-6.08-21.22-14.94h-6.34c1.49,5.43,4.58,10.34,8.89,14.06,5.19,4.48,11.82,6.94,18.68,6.94,15.77,0,28.59-12.83,28.59-28.59v-3.03H19.25c-7.27,0-13.18-5.91-13.18-13.18s5.91-13.18,13.18-13.18v-6.07C8.63,25.54,0,34.17,0,44.79s8.63,19.25,19.25,19.25Z" id="sc-loader-line2"></path>
                            </g>
                            <g>
                              <path class="sc-loader-svg-blue svelte-1y3s990" d="m33.62,44.8c0,2.84-2.3,5.14-5.14,5.14s-5.14-2.3-5.14-5.14,2.3-5.14,5.14-5.14,5.14,2.3,5.14,5.14Z" id="sc-loader-dot1"></path>
                              <path class="sc-loader-svg-blue svelte-1y3s990" d="m57.07,44.8c0,2.84-2.3,5.14-5.14,5.14s-5.14-2.3-5.14-5.14,2.3-5.14,5.14-5.14,5.14,2.3,5.14,5.14Z" id="sc-loader-dot2"></path>
                              <path class="sc-loader-svg-blue svelte-1y3s990" d="m80.52,44.8c0,2.84-2.3,5.14-5.14,5.14s-5.14-2.3-5.14-5.14,2.3-5.14,5.14-5.14,5.14,2.3,5.14,5.14Z" id="sc-loader-dot3"></path>
                            </g>
                          </g>
                        </g>
                      </svg>
                    </div>
                    <h5 class="text-center">Gliederung wird geladen...</h5>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
        <div class="card-backdrop svelte-pvmg9g"></div>
      </div>
    </div>
  </section>

 <!--Abschnitt Lizenzrechner-->
  <section id="registrieren" class="svelte-53os54">
    <div class="container">
      <h2 class="text-center">Günstige Preise dank skalierbaren Lizenzmodell</h2>
      <h4 class="text-center">Lizenzrechner</h4>
      <p class="text-center">Überzeugen Sie sich von unseren preiswertem Lizenzmodell. Geben Sie unverbindlich die Anzahl der Benutzer ein und erhalten Sie direkt den dazugehörigen Preis. Die Laufzeit beträgt jeweils ein Jahr, zusätzlich zur Nutzungslizenz für Ihre Benutzer erhalten Sie jeweils eine bestimmte Anzahl an <b>Credits</b>. Mit diesen Credits können Sie unsere innovativen KI-Funktionen nutzen.</p>
      <div class="row my-4">
            <label for="users" class="form-label">Anzahl der Benutzer</label>
            <input type="range" class="form-range" id="users" min="100" max="2000" step="100" value="100" v-model="userCount" @change="calculateCredits()">
      </div>
      <div class="offer text-center svelte-53os54">
        <h4>Ihr persönliches Angebot</h4>
        <div class="row mt-3">
          <div class="col-lg-6">
            <div class="form-group">
              <h5 class="mb-1">Anzahl der Benutzer</h5>
              <p>{{userCount}} Benutzer</p>
            </div>
            <div class="form-group mt-4">
              <h5 class="mb-1">Anzahl der Credits</h5>
              <p>{{credits}} Credits</p></div>
            </div>
            <div class="col-lg-6">
              <h5>Preis pro Monat</h5>
              <p>100,00 €</p>
            </div>
          </div>
          <div class="mt-2">
            <small>Jährliche Zahlung, Laufzeit 1 Jahr, jährliche Verlängerung</small>
          </div>
        </div>
    </div>
  </section>

  <!--Abschnitt Registrieren-->
  <section id="registrieren" class="svelte-1ysh0ib">
    <div class="container">
      <h2 class="text-center">Überzeugt? Jetzt unkompliziert anmelden</h2>
      <div class="row mt-3">
        <div class="col-lg-4">
          <h4>3 einfache Schritte</h4>
          <p>In Kürze beginnt Ihre Reise in die Schulungs.Cloud. Registrieren Sie unkompliziert Ihren Unternehmensaccount in 3 einfachen Schritten:</p>
          <ol>
            <li>Firmendaten im Formular ausfüllen</li>
            <li>PayPal-Zahlungen autorisieren</li>
            <li>Schulungs.Cloud-Profil personalisieren</li>
          </ol>
          <p>Anschließend können Sie die ersten Benutzer Ihrer Organisation anlegen und Kurse erstellen.</p>
          <p>In Eile? Kein Problem, wählen Sie einfach einen Kurs aus unserer umfangreichen Kursbibliothek aus.</p>
        </div>
        <!--kleiner Lizenzrechner-->
        <div class="col-lg-8">
          <form method="POST">
            <div class="user-selection svelte-1ysh0ib">
              <div class="row">
                <div class="col-lg-12">
                  <label for="users2" class="form-label">Anzahl der Benutzer</label>
                  <input type="range" class="form-range" id="users2" min="100" max="2000" step="100" value="100">
                  <div class="text-center">
                    <small class="text-muted"><span class="fal fa-mouse me-2"></span>Wählen Sie die benötigte Anzahl der Benutzer über den Schieberegler.</small>
                  </div>
                </div>
              </div>
              <div class="row mt-3">
                <div class="col-lg-6">
                  <h5>Lizenzstufe:</h5>
                  <p>100 Benutzer / 1.200 Credits</p>
                </div>
                <div class="col-lg-6">
                  <h5>Preis pro Monat</h5>
                  <p>100,00 €</p>
                </div>
              </div>
            </div>
            
            <!--Formular-->
            <div class="row">
              <div class="col-lg-6">
                <div class="form-group has-validation">
                  <label for="firstname" class="form-label">Vorname</label>
                  <input type="text" class="form-control svelte-1ysh0ib" id="firstname" value="">
                </div>
              </div>
              <div class="col-lg-6">
                <div class="form-group">
                  <label for="lastname" class="form-label">Nachname</label>
                  <input type="text" class="form-control svelte-1ysh0ib" id="lastname" value="">
                </div>
              </div>
            </div>
            <div class="row mt-3">
              <div class="col-lg-8">
                <div class="form-group">
                  <label for="company" class="form-label">Firmenname</label>
                  <input type="text" class="form-control svelte-1ysh0ib" id="company" value="">
                </div>
              </div>
            </div>
            <div class="row mt-3">
              <div class="col-lg-8">
                <div class="form-group">
                  <label for="email" class="form-label">E-Mail-Adresse</label>
                  <input type="email" class="form-control svelte-1ysh0ib" id="email" value="">
                </div>
              </div>
            </div>
            <div class="row mt-3">
              <div class="col-lg-12">
                <div class="form-check">
                  <input class="form-check-input" type="checkbox" value="" id="flexCheckAGB">
                  <label class="form-check-label" for="flexCheckAGB">Ich habe die <a href="/agb" target="_blank" rel="noopener">AGB</a> gelesen und akzeptiere diese.</label>
                </div>
                <div class="form-check">
                  <input class="form-check-input" type="checkbox" value="" id="flexCheckPrivacy">
                  <label class="form-check-label" for="flexCheckPrivacy">Ich habe die Hinweise zum <a href="/datenschutz" target="_blank" rel="noopener">Datenschutz</a> gelesen und akzeptiere diese.</label>
                </div>
                <div class="form-check">
                  <input class="form-check-input" type="checkbox" value="" id="flexCheckPricing">
                  <label class="form-check-label" for="flexCheckPricing">Ich bestätige, dass ich berechtigt bin, im Namen der obengenannten Firma ein jährliches Abonnement abzuschließen. Nach Ablauf wird das Abonnement automatisch um ein weiteres Jahr verlängert.</label>
                </div>
              </div>
            </div>
            <div class="row my-2">
              <div class="col">
                <small class="text-muted">Bitte beachten Sie, dass Sie nach Klicken der Schaltfläche direkt zu PayPal geleitet werden. Nach erfolgreicher Autorisierung landen Sie automatisch in der Schulungs.Cloud</small>
              </div>
            </div>
            <div class="row">
              <div class="col-lg-12 d-flex align-items-end justify-content-end">
                <button type="submit" class="btn btn-primary svelte-1ysh0ib">Zahlungspflichtig bestellen</button>
              </div>
            </div>
          </form>
        </div>
      </div>
    </div>
  </section>

<!--Abschnitt Fußzeile-->
  <section id="footer" class="svelte-nsiaxd">
    <div class="container-fluid svelte-nsiaxd">
      <div class="row">
        <div class="col-lg-6 d-flex align-items-center">
          <div class="icon me-2 svelte-nsiaxd">
            <svg class="sc-icon-svg svelte-12quz68  white" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 103.85 89.59">
              <g id="l1">
                <g>
                  <g>
                    <path class="cls-2 svelte-12quz68" d="m84.61,25.56H29.61c1.49-10.99,10.93-19.49,22.32-19.49,9.74,0,18.1,6.08,21.22,14.94h6.34c-1.49-5.43-4.58-10.34-8.89-14.06-5.19-4.48-11.82-6.94-18.68-6.94-15.77,0-28.59,12.83-28.59,28.59v3.03h61.27c7.27,0,13.18,5.91,13.18,13.18s-5.91,13.18-13.18,13.18v6.07c10.61,0,19.25-8.63,19.25-19.25s-8.63-19.25-19.25-19.25Z"></path>
                    <path class="cls-1 svelte-12quz68" d="m19.25,64.04h55c-1.49,10.99-10.93,19.49-22.32,19.49-9.74,0-18.1-6.08-21.22-14.94h-6.34c1.49,5.43,4.58,10.34,8.89,14.06,5.19,4.48,11.82,6.94,18.68,6.94,15.77,0,28.59-12.83,28.59-28.59v-3.03H19.25c-7.27,0-13.18-5.91-13.18-13.18s5.91-13.18,13.18-13.18v-6.07C8.63,25.54,0,34.17,0,44.79s8.63,19.25,19.25,19.25Z"></path>
                  </g>
                  <g>
                    <path class="cls-1 svelte-12quz68" d="m33.62,44.8c0,2.84-2.3,5.14-5.14,5.14s-5.14-2.3-5.14-5.14,2.3-5.14,5.14-5.14,5.14,2.3,5.14,5.14Z"></path>
                    <path class="cls-1 svelte-12quz68" d="m57.07,44.8c0,2.84-2.3,5.14-5.14,5.14s-5.14-2.3-5.14-5.14,2.3-5.14,5.14-5.14,5.14,2.3,5.14,5.14Z"></path>
                    <path class="cls-1 svelte-12quz68" d="m80.52,44.8c0,2.84-2.3,5.14-5.14,5.14s-5.14-2.3-5.14-5.14,2.3-5.14,5.14-5.14,5.14,2.3,5.14,5.14Z"></path>
                  </g>
                </g>
              </g>
            </svg>
          </div>
          <span>Schulungs.Cloud ist ein Produkt der LEIBOLD Sicherheits- &amp; Informationstechnik GmbH</span>
        </div>
        <div class="col-lg-6 d-flex align-items-center justify-content-end">
          <a href="/impressum" class="svelte-nsiaxd">Impressum</a>
          <a href="/datenschutz" class="svelte-nsiaxd">Datenschutz</a>
          <a href="/agb" class="svelte-nsiaxd">AGB</a>
        </div>
      </div>
    </div>
  </section>
</div>
<DoIt></DoIt>
</template>

<!--Abschnitt Lizenzrechner Beispiel JavaScript Code für das Berechnen der Credits:-->
<script setup lang="ts">
import { Ref, ref } from "vue";
import DoIt from "./components/DoIt.vue";

const userCount : Ref<string> = ref("100");
const credits : Ref<number> = ref(1200);

function calculateCredits() {
  credits.value = userCount.value * 12;
}
</script>

