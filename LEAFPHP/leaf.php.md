### Introduzione a PHP

PHP (acronimo ricorsivo di "PHP: Hypertext Preprocessor") è un linguaggio di scripting open source ampiamente utilizzato per lo sviluppo web. È progettato specificamente per la creazione di pagine web dinamiche e interattive e si integra facilmente con HTML.

### Origini e Storia di PHP

PHP è stato creato da Rasmus Lerdorf nel 1994. Inizialmente, era una serie di script CGI (Common Gateway Interface) scritti in C, che Lerdorf utilizzava per tracciare le visite al proprio curriculum online. Questi script iniziali vennero chiamati "Personal Home Page Tools" (Strumenti per Pagine Personali), da cui deriva l'acronimo originale PHP. Nel 1995, Lerdorf pubblicò la prima versione di PHP, rendendola disponibile a chiunque volesse usarla o migliorarla.

Nel 1997, due sviluppatori israeliani, Zeev Suraski e Andi Gutmans, riscrissero il core di PHP, creando quella che è diventata la versione 3. Questa riscrittura è stata fondamentale per la successiva evoluzione del linguaggio. Nel 1999, Suraski e Gutmans svilupparono il motore Zend, una piattaforma di esecuzione per PHP che ha ulteriormente migliorato le prestazioni e la funzionalità del linguaggio. Questa versione, PHP 4, fu rilasciata nel 2000 e includeva il motore Zend 1.0.

### Punti di Forza di PHP

PHP offre numerosi vantaggi che hanno contribuito alla sua popolarità nel tempo:

1. **Facilità d'Uso**: PHP è noto per la sua curva di apprendimento relativamente bassa. I nuovi sviluppatori possono rapidamente imparare a creare pagine web dinamiche.
2. **Flessibilità**: PHP può essere integrato con HTML, XML, JSON e molte altre tecnologie web. È anche compatibile con vari sistemi di database, come MySQL, PostgreSQL, Oracle, e SQLite.
3. **Ecosistema Esteso**: Grazie alla sua lunga storia, PHP ha un vasto ecosistema di librerie, framework (come Laravel, Symfony, e CodeIgniter) e strumenti di sviluppo.
4. **Performance**: Con il motore Zend e successive ottimizzazioni, PHP offre buone prestazioni per le applicazioni web, specialmente con le versioni più recenti come PHP 7 e PHP 8, che hanno migliorato significativamente la velocità e l'efficienza.
5. **Comunità Attiva**: PHP ha una comunità di sviluppatori molto attiva che contribuisce con pacchetti, librerie, tutorial, e supporto.

### Evoluzione di PHP con il Web

Nel corso degli anni, PHP si è evoluto per rispondere alle crescenti esigenze del web moderno:

- **PHP 5 (2004)**: Introduzione del supporto completo alla programmazione orientata agli oggetti (OOP), miglioramenti nel motore Zend, e nuove estensioni come SimpleXML e PDO (PHP Data Objects).
- **PHP 7 (2015)**: Un significativo aumento delle prestazioni rispetto alle versioni precedenti, grazie a una nuova versione del motore Zend (Zend Engine 3.0). Altre caratteristiche includono la dichiarazione dei tipi scalari, il supporto ai tipi di ritorno, e l'operatore spaceship.
- **PHP 8 (2020)**: Introduzione di JIT (Just-In-Time compilation), miglioramenti nella sintassi del linguaggio, e nuove funzionalità come gli attributi, i named arguments, e le unioni di tipi.

### La Programmazione Client-Server con PHP

La programmazione client-server è un modello fondamentale per le applicazioni web. In questo modello, il client (solitamente un browser web) invia richieste al server, che elabora queste richieste e restituisce le risposte appropriate.

1. **Client**: Il client invia una richiesta HTTP (HyperText Transfer Protocol) al server. Questa richiesta può essere una richiesta di pagina web, dati tramite API, o l'invio di dati di un modulo.
2. **Server**: Il server web (come Apache, Nginx, o IIS) riceve la richiesta e la passa al motore PHP.
3. **Elaborazione PHP**: PHP elabora la richiesta, eseguendo script che possono interagire con un database, manipolare dati, e generare contenuti HTML dinamici.
4. **Risposta al Client**: Il server web restituisce l'output generato da PHP al client, tipicamente sotto forma di una pagina web.

Ad esempio, quando un utente compila un modulo di login su un sito web:

1. Il client invia i dati di login (username e password) al server.
2. Il server elabora i dati ricevuti utilizzando PHP, verificando le credenziali contro un database.
3. Se le credenziali sono corrette, PHP genera una pagina web che indica che l'utente ha effettuato il login con successo.
4. Il server invia questa pagina al client, che la visualizza nel browser.

### Lo Stack LAMP

Un altro elemento chiave del successo di PHP è il suo ruolo centrale nello stack LAMP, un insieme di tecnologie open source utilizzate comunemente per sviluppare e implementare applicazioni web. LAMP è un acronimo che sta per Linux (sistema operativo), Apache (server web), MySQL (sistema di gestione di database) e PHP (linguaggio di scripting). Ogni componente dello stack LAMP svolge un ruolo cruciale nel funzionamento delle applicazioni web.

- **Linux**: Essendo un sistema operativo open source e altamente configurabile, Linux offre una base robusta e sicura per le applicazioni web. La sua compatibilità con una vasta gamma di hardware e la presenza di numerose distribuzioni (come Ubuntu, CentOS, e Debian) lo rendono una scelta popolare per i server web.
- **Apache**: Apache è uno dei server web più utilizzati al mondo. È noto per la sua affidabilità, flessibilità e vasta gamma di funzionalità. Apache gestisce le richieste HTTP, inoltrandole al motore PHP per l'elaborazione.
- **MySQL**: MySQL è un sistema di gestione di database relazionale molto diffuso, apprezzato per le sue prestazioni, scalabilità e facilità d'uso. Viene utilizzato per memorizzare e gestire i dati delle applicazioni web. PHP può interagire con MySQL per eseguire query, recuperare dati e aggiornare record.
- **PHP**: PHP integra i vari componenti dello stack LAMP, elaborando le richieste del server web, interagendo con il database MySQL e generando contenuti dinamici che vengono inviati al client.

La combinazione di questi strumenti crea un ambiente di sviluppo potente e flessibile che consente agli sviluppatori di creare applicazioni web complesse in modo efficiente. L'adozione dello stack LAMP è diffusa tra le piccole e grandi imprese grazie alla sua natura open source, che riduce i costi di licenza, e alla sua stabilità e scalabilità, che garantiscono buone prestazioni anche per le applicazioni più esigenti.

PHP è un linguaggio potente e versatile che ha giocato un ruolo cruciale nello sviluppo del web. La sua facilità d'uso, flessibilità, e continua evoluzione lo rendono una scelta eccellente per sviluppatori web di tutti i livelli. Con l'avvento delle versioni più recenti, PHP continua a migliorare le sue performance e funzionalità, garantendo la sua rilevanza nel panorama tecnologico attuale.

Capire i concetti di base della programmazione, come le variabili, le strutture di controllo e i cicli, è essenziale per sviluppare competenze di programmazione solide. La programmazione orientata agli oggetti, con i suoi principi di classi, oggetti, incapsulamento, ereditarietà e polimorfismo, offre potenti strumenti per scrivere codice modulare, riutilizzabile e manutenibile. Questi concetti fondamentali sono alla base di molti linguaggi di programmazione e sono indispensabili per diventare un programmatore competente.

### Le Basi della Programmazione

#### Introduzione

La programmazione è il processo di scrittura di istruzioni che un computer può seguire per eseguire compiti specifici. Per comprendere le basi della programmazione, è essenziale conoscere alcuni concetti fondamentali, come le variabili, le strutture di controllo (if e cicli) e la programmazione orientata agli oggetti (OOP).

### Variabili

Le variabili sono uno dei concetti più basilari in qualsiasi linguaggio di programmazione. Una variabile è un contenitore che memorizza un valore che può cambiare durante l'esecuzione del programma. Immagina una variabile come una scatola con un'etichetta. L'etichetta è il nome della variabile, e il contenuto della scatola è il valore memorizzato.

Ad esempio, una variabile può memorizzare numeri, testo, valori booleani (vero/falso) o persino strutture più complesse come liste e oggetti. Utilizzare le variabili consente ai programmatori di manipolare i dati e mantenerli in memoria per usi futuri.

### Strutture di Controllo

#### Condizionali (if)

Le strutture condizionali sono utilizzate per prendere decisioni nel codice. La più comune è l'istruzione `if`, che permette di eseguire un blocco di codice solo se una certa condizione è vera. Se la condizione non è vera, il codice all'interno dell'istruzione `if` viene saltato.

Ad esempio, se si desidera verificare se un numero è positivo, si può utilizzare una struttura `if` per eseguire il codice corrispondente solo se il numero è maggiore di zero.

#### Cicli

I cicli sono utilizzati per eseguire ripetutamente un blocco di codice finché una certa condizione è vera. Ci sono diversi tipi di cicli, tra cui:

- **Ciclo while**: Esegue un blocco di codice finché una condizione è vera.
- **Ciclo do-while**: Simile al ciclo while, ma la condizione viene verificata dopo aver eseguito il blocco di codice, garantendo che il blocco venga eseguito almeno una volta.
- **Ciclo for**: Utilizzato quando si conosce in anticipo quante volte eseguire il blocco di codice. È composto da un'initializzazione, una condizione di esecuzione e un aggiornamento al termine di ogni iterazione.
- **Ciclo foreach**: Utilizzato per iterare attraverso gli elementi di una collezione (come un array o una lista).

I cicli sono particolarmente utili per operazioni ripetitive, come l'elaborazione di ogni elemento in una lista o l'esecuzione di un'azione un numero specifico di volte.

### Programmazione Orientata agli Oggetti (OOP)

La programmazione orientata agli oggetti (OOP) è un paradigma di programmazione che utilizza "oggetti" per modellare dati e comportamenti. Gli oggetti sono istanze di "classi", che sono come schemi o modelli che definiscono le proprietà e i metodi comuni a tutti gli oggetti di quel tipo.

#### Concetti Fondamentali dell'OOP

1. **Classi e Oggetti**:
    - Una classe è una definizione o un blueprint per un tipo di oggetto. Definisce le proprietà (dati) e i metodi (funzioni) che gli oggetti di quel tipo avranno.
    - Un oggetto è un'istanza di una classe. È una entità autonoma con uno stato (valori delle proprietà) e un comportamento (metodi).

2. **Incapsulamento**:
    - L'incapsulamento è il principio di nascondere i dettagli interni di un oggetto e permettere l'accesso solo attraverso metodi pubblici. Questo protegge lo stato interno di un oggetto dall'accesso e dalla modifica non controllati.

3. **Ereditarietà**:
    - L'ereditarietà permette di creare nuove classi che ereditano le proprietà e i metodi di una classe esistente. Questo promuove il riuso del codice e facilita l'estensione delle funzionalità.
    - La classe da cui si eredita è chiamata "classe base" o "superclasse", mentre la nuova classe è chiamata "classe derivata" o "sottoclasse".

4. **Polimorfismo**:
    - Il polimorfismo permette a oggetti di classi diverse di essere trattati come oggetti della stessa classe tramite un'interfaccia comune. Ciò consente di scrivere codice più flessibile e riutilizzabile.
    - Esistono due tipi principali di polimorfismo: il polimorfismo di sottotipo (basato sull'ereditarietà) e il polimorfismo di ad-hoc (basato sulla sovraccarico dei metodi).

#### Vantaggi dell'OOP

- **Modularità**: Le classi possono essere sviluppate, testate e mantenute in modo indipendente, migliorando la manutenibilità del codice.
- **Riutilizzabilità**: Le classi e gli oggetti possono essere riutilizzati in diversi progetti, riducendo la duplicazione del codice.
- **Manutenzione facilitata**: Le modifiche possono essere apportate a una classe senza influenzare altre parti del programma, a condizione che l'interfaccia pubblica rimanga invariata.
- **Flessibilità ed Estensibilità**: Nuove funzionalità possono essere aggiunte tramite l'ereditarietà e il polimorfismo senza modificare il codice esistente.

Adesso che abbia descritto i concetti fondamentali della programmazione vediamo come PHP li implementa.

### Sintassi di Base

#### Il Primo Script PHP

Crea un file chiamato `index.php` e inserisci il seguente codice:

```php
<?php
echo "Hello, World!";
?>
```

Salva il file nella directory del tuo server web e aprilo nel browser. Dovresti vedere "Hello, World!" visualizzato nella pagina.

#### Commenti

I commenti in PHP possono essere singola riga o multi-riga:

```php
// Questo è un commento su una sola riga

/*
Questo è un commento
su più righe
*/
```

#### Variabili

Le variabili in PHP iniziano con il simbolo `$`:

```php
<?php
$nome = "John";
$eta = 25;
echo $nome;
echo $eta;
?>
```

#### Tipi di Dati

PHP supporta vari tipi di dati, inclusi:

- **Stringhe**: Sequenze di caratteri racchiuse tra apici singoli (`'`) o doppi (`"`).
- **Interi**: Numeri interi.
- **Float**: Numeri decimali.
- **Booleani**: `true` o `false`.
- **Array**: Collezioni di valori.
- **Oggetti**: Istanze di classi.
- **Null**: Una variabile senza valore.

Esempi:

```php
<?php
$stringa = "Hello";
$intero = 42;
$float = 3.14;
$booleano = true;
$array = array(1, 2, 3);
$oggetto = new stdClass();
$nulla = null;
?>
```

#### Operatori

PHP supporta vari operatori:

- **Aritmetici**: `+`, `-`, `*`, `/`, `%`
- **Assegnazione**: `=`, `+=`, `-=`, `*=`, `/=`, `%=`
- **Confronto**: `==`, `!=`, `===`, `!==`, `<`, `>`, `<=`, `>=`
- **Logici**: `&&`, `||`, `!`

### Strutture di Controllo

#### Condizionali

PHP supporta `if`, `else`, `elseif` e `switch`:

```php
<?php
$eta = 20;

if ($eta < 18) {
    echo "Minorenne";
} elseif ($eta == 18) {
    echo "Appena Maggiorenne";
} else {
    echo "Maggiorenne";
}
?>
```

```php
<?php
$colore = "rosso";

switch ($colore) {
    case "rosso":
        echo "Il colore è rosso";
        break;
    case "blu":
        echo "Il colore è blu";
        break;
    default:
        echo "Colore sconosciuto";
}
?>
```

#### Loop

PHP supporta vari tipi di loop, tra cui `while`, `do-while`, `for`, e `foreach`:

```php
<?php
// Loop while
$i = 0;
while ($i < 5) {
    echo $i;
    $i++;
}

// Loop do-while
$j = 0;
do {
    echo $j;
    $j++;
} while ($j < 5);

// Loop for
for ($k = 0; $k < 5; $k++) {
    echo $k;
}

// Loop foreach
$array = array(1, 2, 3);
foreach ($array as $valore) {
    echo $valore;
}
?>
```

### Funzioni

Le funzioni in PHP sono definite utilizzando la parola chiave `function`:

```php
<?php
function saluta($nome) {
    return "Ciao, " . $nome;
}

echo saluta("Maria");
?>
```

Le funzioni possono avere parametri con valori predefiniti e tipi di ritorno:

```php
<?php
function somma($a, $b = 0): int {
    return $a + $b;
}

echo somma(5, 10); // 15
echo somma(5);     // 5
?>
```

### Programmazione Orientata agli Oggetti (OOP)

PHP supporta la programmazione orientata agli oggetti. Ecco una panoramica di base:

#### Classi e Oggetti

Definire una classe e creare un oggetto:

```php
<?php
class Persona {
    public $nome;
    public $eta;

    public function __construct($nome, $eta) {
        $this->nome = $nome;
        $this->eta = $eta;
    }

    public function saluta() {
        return "Ciao, " . $this->nome;
    }
}

$persona = new Persona("Marco", 30);
echo $persona->saluta();
?>
```

#### Ereditarietà

PHP supporta l'ereditarietà, permettendo a una classe di derivare da un'altra:

```php
<?php
class Studente extends Persona {
    public $corso;

    public function __construct($nome, $eta, $corso) {
        parent::__construct($nome, $eta);
        $this->corso = $corso;
    }

    public function info() {
        return $this->nome . " ha " . $this->eta . " anni e studia " . $this->corso;
    }
}

$studente = new Studente("Laura", 22, "Informatica");
echo $studente->info();
?>
```

#### Modificatori di Accesso

PHP supporta tre modificatori di accesso: `public`, `protected`, e `private`:

```php
<?php
class MyClass {
    public $pubblico = "Pubblico";
    protected $protetto = "Protetto";
    private $privato = "Privato";

    public function mostra() {
        echo $this->pubblico;
        echo $this->protetto;
        echo $this->privato;
    }
}

$obj = new MyClass();
echo $obj->pubblico; // Funziona
$obj->mostra();      // Funziona
// echo $obj->protetto; // Errore
// echo $obj->privato;  // Errore
?>
```

### Gestione degli Errori

PHP offre diverse modalità per gestire gli errori, inclusi `try`, `catch` e `finally`:

```php
<?php
try {
    // Codice che potrebbe generare un'eccezione
    if (!file_exists("file.txt")) {
        throw new Exception("File non trovato.");
    }
} catch (Exception $e) {
    echo "Eccezione catturata: " . $e->getMessage();
} finally {
    echo "Questo blocco viene sempre eseguito.";
}
?>
```

Adesso che abbiamo un’infarinatura di base di programmazione e di PHP passiamo a vedere il framework web Leaf.

Leaf PHP è un micro framework leggero e facile da usare per lo sviluppo di applicazioni web e API. Progettato per essere minimalista e semplice, Leaf PHP offre solo le funzionalità essenziali necessarie per creare rapidamente applicazioni web, rendendolo ideale per progetti di piccole e medie dimensioni.

### Caratteristiche Principali di Leaf PHP

1. **Routing Semplice**:
   Leaf PHP fornisce un sistema di routing intuitivo per definire facilmente le rotte e gestire le richieste HTTP. Supporta diversi metodi HTTP come GET, POST, PUT, DELETE.

2. **Gestione delle Risposte**:
   Leaf consente di gestire le risposte HTTP in modo semplice, inclusa la possibilità di inviare risposte JSON, gestire codici di stato HTTP e personalizzare le intestazioni delle risposte.

3. **Middleware**:
   Il framework supporta middleware, che permette di eseguire logica personalizzata prima o dopo che una richiesta venga gestita dal suo handler. Questo è utile per autenticazione, autorizzazione, logging, ecc.

4. **Supporto per Template**:
   Leaf PHP include il supporto per l'uso di template, facilitando la separazione della logica di business dalla presentazione. Può essere integrato con template engine come Twig.

5. **Gestione delle Richieste**:
   Offre strumenti per accedere facilmente ai dati della richiesta, inclusi i parametri della query, il payload del corpo della richiesta e le intestazioni.

6. **Compatibilità**:
   Leaf PHP è compatibile con altri componenti e librerie PHP, permettendo agli sviluppatori di estendere facilmente le funzionalità del framework con pacchetti di terze parti.

### Esempio di Utilizzo

Ecco un esempio semplice di come creare un'applicazione con Leaf PHP:

```php
require 'vendor/autoload.php';

$app = new Leaf\App();

$app->get('/', function() {
    echo 'Hello, world!';
});

$app->run();
```

In questo esempio, importiamo il pacchetto Leaf PHP tramite Composer, creiamo un'istanza dell'applicazione Leaf, definiamo una rotta per la radice dell'applicazione (`/`) che restituisce "Hello, world!" e infine eseguiamo l'applicazione.

### Quando Usare Leaf PHP

Leaf PHP è particolarmente utile in contesti in cui la semplicità e la leggerezza sono cruciali, come:

- Progetti di piccole e medie dimensioni
- API semplici e microservizi
- Prototipi e proof-of-concept
- Applicazioni con requisiti specifici e minimali

Grazie alla sua facilità d'uso e alla curva di apprendimento ridotta, Leaf PHP è una scelta eccellente per sviluppatori che cercano un framework rapido e efficace per costruire applicazioni web senza il sovraccarico di funzionalità complesse e non necessarie.

### Vantaggi di Leaf PHP

1. **Semplicità e Facilità d'Uso**:
   Leaf PHP è progettato per essere semplice e intuitivo, rendendolo accessibile anche ai principianti. La curva di apprendimento è bassa, e le funzionalità di base possono essere comprese e utilizzate rapidamente.

2. **Leggerezza**:
   Leaf PHP è un micro framework leggero, il che significa che ha un footprint ridotto e non include funzionalità non necessarie. Questo lo rende rapido e poco esigente in termini di risorse, ideale per applicazioni leggere e microservizi.

3. **Flessibilità**:
   La sua architettura minimalista consente di estenderlo facilmente con librerie e pacchetti di terze parti. Puoi aggiungere solo ciò di cui hai bisogno, senza essere vincolato a un ecosistema monolitico.

4. **Routing Intuitivo**:
   Leaf PHP offre un sistema di routing semplice e potente, che rende facile definire e gestire le rotte delle applicazioni web.

5. **Supporto per Middleware**:
   Il supporto per middleware permette di eseguire logica personalizzata prima o dopo la gestione delle richieste, utile per funzioni come l'autenticazione e il logging.

6. **Gestione delle Risposte**:
   La gestione delle risposte HTTP è facilitata, inclusa la possibilità di restituire risposte JSON, gestire codici di stato e personalizzare le intestazioni.

### Svantaggi di Leaf PHP

1. **Funzionalità Limitate**:
   Essendo un micro framework, Leaf PHP non offre tutte le funzionalità avanzate e integrate che si trovano in framework più robusti come Laravel o Symfony. Questo potrebbe richiedere l'aggiunta manuale di librerie per funzioni avanzate.

2. **Supporto e Documentazione**:
   Essendo meno popolare di altri framework più grandi, potrebbe avere meno risorse, documentazione e comunità di supporto disponibili. Questo può rendere più difficile trovare soluzioni a problemi specifici.

3. **Scalabilità**:
   Mentre Leaf PHP è eccellente per applicazioni piccole e medie, potrebbe non essere la scelta migliore per applicazioni molto grandi e complesse che richiedono funzionalità avanzate di gestione delle prestazioni e scalabilità.

4. **Meno Ecosistema**:
   Framework più grandi come Laravel hanno un ecosistema molto ricco di pacchetti, estensioni e strumenti di terze parti già pronti all'uso. Leaf PHP, essendo più giovane e meno diffuso, potrebbe avere un ecosistema meno sviluppato.

5. **Assenza di Convenzioni Rigide**:
   Framework come Laravel offrono convenzioni rigide che aiutano a mantenere il codice organizzato e strutturato. Leaf PHP, essendo minimalista, lascia più libertà agli sviluppatori, il che potrebbe portare a codice meno strutturato se non gestito correttamente.

Leaf PHP è una scelta eccellente per progetti dove la semplicità, la leggerezza e la velocità di sviluppo sono prioritari. Tuttavia, per applicazioni molto grandi o complesse, potrebbe essere necessario considerare un framework più completo che offra un ecosistema più ricco e funzionalità integrate avanzate.

### Installazione e Configurazione di Leaf PHP

Per iniziare a lavorare con Leaf PHP, segui questi passaggi per installare e configurare correttamente il framework.

#### 1. Requisiti di Sistema
Prima di iniziare, assicurati di avere i seguenti requisiti:
- PHP 7.2 o superiore
- Composer (per gestire le dipendenze PHP)
- Un server web (Apache, Nginx, ecc.)

#### 2. Installazione tramite Composer
Composer è un gestore di pacchetti per PHP che facilita l'installazione e la gestione delle dipendenze. Per installare Leaf PHP, esegui i seguenti comandi:

1. **Installazione di Composer**:
   Se non hai ancora Composer installato, puoi scaricarlo e installarlo seguendo le istruzioni sul [sito ufficiale di Composer](https://getcomposer.org/).

2. **Creazione di un Nuovo Progetto**:
   Crea una nuova directory per il tuo progetto e spostati al suo interno:
   ```sh
   mkdir nome_progetto
   cd nome_progetto
   ```

3. **Installazione di Leaf PHP**:
   Utilizza Composer per installare Leaf PHP:
   ```sh
   composer require leafs/leaf
   ```

#### 3. Configurazione di Base
Dopo aver installato Leaf PHP, è necessario configurare l'ambiente di sviluppo. Crea un file `index.php` nella directory principale del tuo progetto con il seguente contenuto:

```php
<?php
require 'vendor/autoload.php';

$app = new Leaf\App();

$app->get('/', function() {
    echo 'Hello, world!';
});

$app->run();
```

Questo codice importa il pacchetto Leaf PHP tramite Composer, crea un'istanza dell'applicazione, definisce una rotta per la radice (`/`) che restituisce "Hello, world!" e avvia l'applicazione.

#### 4. Configurazione del Server Web
Configura il tuo server web per puntare alla directory del tuo progetto. Ecco come configurare Apache e Nginx.

**Apache**:
Crea un file di configurazione virtual host per Apache (ad esempio, `leaf_app.conf`):

```apache
<VirtualHost *:80>
    ServerName leaf-app.local
    DocumentRoot /percorso/al/tuo/progetto

    <Directory /percorso/al/tuo/progetto>
        AllowOverride All
        Require all granted
    </Directory>

    ErrorLog ${APACHE_LOG_DIR}/leaf_app_error.log
    CustomLog ${APACHE_LOG_DIR}/leaf_app_access.log combined
</VirtualHost>
```

Assicurati di abilitare il modulo `mod_rewrite` di Apache:

```sh
a2enmod rewrite
service apache2 restart
```

**Nginx**:
Crea un file di configurazione server per Nginx (ad esempio, `leaf_app`):

```nginx
server {
    listen 80;
    server_name leaf-app.local;
    root /percorso/al/tuo/progetto;

    index index.php index.html index.htm;

    location / {
        try_files $uri $uri/ /index.php?$query_string;
    }

    location ~ \.php$ {
        include snippets/fastcgi-php.conf;
        fastcgi_pass unix:/var/run/php/php7.4-fpm.sock; # Assicurati di usare la versione corretta di PHP
    }

    location ~ /\.ht {
        deny all;
    }
}
```

#### 5. Configurazione del File Hosts
Modifica il file hosts del tuo sistema per puntare il dominio locale al tuo server. Aggiungi la seguente riga al file hosts:

- **Linux/Mac**: `/etc/hosts`
- **Windows**: `C:\Windows\System32\drivers\etc\hosts`

```plaintext
127.0.0.1   leaf-app.local
```

#### 6. Avvio dell'Applicazione
Assicurati che il server web sia in esecuzione, quindi visita `http://leaf-app.local` nel tuo browser. Dovresti vedere la scritta "Hello, world!" sullo schermo, indicando che l'installazione e la configurazione di Leaf PHP sono state completate con successo.

Leaf PHP offre flessibilità e semplicità, rendendolo una scelta eccellente per sviluppatori che desiderano un framework rapido e leggero per sviluppare applicazioni web e API.

### Panoramica della Struttura delle Directory in un Progetto Leaf PHP

Una struttura organizzata delle directory è fondamentale per mantenere il codice del progetto pulito e gestibile. Di seguito è riportata una panoramica della struttura delle directory comunemente utilizzata nei progetti Leaf PHP, con una spiegazione di ogni directory e file.

```
nome_progetto/
│
├── app/
│   ├── Controllers/
│   ├── Models/
│   └── Views/
│
├── config/
│   └── config.php
│
├── public/
│   └── index.php
│
├── storage/
│   ├── logs/
│   └── cache/
│
├── vendor/
│   └── (directory creata da Composer, contiene le dipendenze)
│
├── .env
├── composer.json
├── composer.lock
└── README.md
```

### Descrizione delle Directory e dei File

#### 1. `app/`
Questa directory contiene il codice dell'applicazione. È suddivisa ulteriormente in sottodirectory per mantenere il codice organizzato.

- **`app/Controllers/`**: Contiene i controller dell'applicazione, che gestiscono la logica delle richieste e delle risposte.
- **`app/Models/`**: Contiene i modelli dell'applicazione, che rappresentano i dati e le interazioni con il database.
- **`app/Views/`**: Contiene i file di vista (template) utilizzati per generare l'output HTML.

#### 2. `config/`
Questa directory contiene i file di configurazione dell'applicazione.

- **`config/config.php`**: Il file principale di configurazione, dove è possibile definire le impostazioni globali dell'applicazione.

#### 3. `public/`
Questa directory contiene i file pubblicamente accessibili dell'applicazione, come il file di ingresso principale (`index.php`).

- **`public/index.php`**: Il punto di ingresso dell'applicazione. Questo file include l'autoload di Composer e avvia l'applicazione Leaf.

#### 4. `storage/`
Questa directory è utilizzata per archiviare file generati dall'applicazione, come log e cache.

- **`storage/logs/`**: Contiene i file di log dell'applicazione.
- **`storage/cache/`**: Contiene i file di cache generati dall'applicazione.

#### 5. `vendor/`
Questa directory viene creata da Composer e contiene tutte le dipendenze del progetto. Non è necessario modificare direttamente questa directory.

#### 6. `composer.json` e `composer.lock`
- **`composer.json`**: Il file di configurazione di Composer, dove sono definite le dipendenze del progetto.
- **`composer.lock`**: Un file generato automaticamente da Composer che blocca le versioni delle dipendenze installate.

#### 7. `.env`
Un file opzionale utilizzato per definire le variabili di ambiente, come le credenziali del database e altre configurazioni specifiche dell'ambiente.

#### 8. `README.md`
Un file opzionale che contiene informazioni sul progetto, istruzioni per l'installazione, l'uso e altri dettagli utili. È particolarmente utile per chiunque stia collaborando al progetto o ne prenda visione per la prima volta.

### Esempio di Configurazione del File `index.php`

Il file `public/index.php` avrà un aspetto simile a questo:

```php
<?php
require '../vendor/autoload.php';

$app = new Leaf\App();

$app->get('/', function() {
    echo 'Hello, world!';
});

$app->run();
```

### Esempio di Configurazione del File `.env`

Ecco un esempio di file `.env`:

```
APP_NAME=LeafApp
APP_ENV=local
APP_DEBUG=true
APP_URL=http://localhost

DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=leafapp
DB_USERNAME=root
DB_PASSWORD=secret
```


Questa struttura delle directory aiuta a mantenere il codice dell'applicazione ben organizzato e modulare, facilitando la gestione e la scalabilità del progetto. Adattare la struttura alle proprie esigenze specifiche è sempre possibile, ma seguire queste convenzioni può semplificare la collaborazione con altri sviluppatori e migliorare la manutenzione del codice a lungo termine.

### File Principali e le Loro Funzioni in un Progetto Leaf PHP

In un progetto Leaf PHP ben strutturato, ci sono diversi file chiave che svolgono ruoli importanti per il funzionamento dell'applicazione. Di seguito è riportata una descrizione dei file principali e delle loro funzioni.

#### 1. `public/index.php`

**Funzione**:
- Questo è il punto di ingresso dell'applicazione. È responsabile dell'inizializzazione dell'applicazione Leaf e della gestione delle richieste in entrata.

**Contenuto Tipico**:
```php
<?php
require '../vendor/autoload.php';

$app = new Leaf\App();

$app->get('/', function() {
    echo 'Hello, world!';
});

$app->run();
```

#### 2. `app/Controllers/HomeController.php`

**Funzione**:
- Questo file contiene i controller, che gestiscono la logica delle richieste e delle risposte. I controller agiscono come intermediari tra i modelli e le viste.

**Contenuto Tipico**:
```php
<?php

namespace App\Controllers;

use Leaf\Controller;

class HomeController extends Controller
{
    public function index()
    {
        echo 'Welcome to Leaf PHP!';
    }
}
```

#### 3. `app/Models/User.php`

**Funzione**:
- I modelli rappresentano i dati e gestiscono le interazioni con il database. Definiscono la struttura dei dati e contengono la logica per recuperare, salvare e manipolare i dati.

**Contenuto Tipico**:
```php
<?php

namespace App\Models;

use Leaf\Model;

class User extends Model
{
    protected $table = 'users';
}
```

#### 4. `app/Views/home.php`

**Funzione**:
- I file di vista contengono il markup HTML che viene restituito al client. Le viste possono essere semplici file PHP che includono logica per visualizzare i dati passati dai controller.

**Contenuto Tipico**:
```php
<!DOCTYPE html>
<html>
<head>
    <title>Home Page</title>
</head>
<body>
    <h1><?php echo $title; ?></h1>
    <p><?php echo $message; ?></p>
</body>
</html>
```

#### 5. `config/config.php`

**Funzione**:
- Questo file contiene la configurazione dell'applicazione. Può includere impostazioni come le credenziali del database, le chiavi API e altre configurazioni globali.

**Contenuto Tipico**:
```php
<?php

return [
    'app' => [
        'name' => 'LeafApp',
        'env' => 'local',
        'debug' => true,
        'url' => 'http://localhost',
    ],

    'db' => [
        'driver' => 'mysql',
        'host' => '127.0.0.1',
        'port' => '3306',
        'database' => 'leafapp',
        'username' => 'root',
        'password' => 'secret',
    ],
];
```

#### 6. `.env`

**Funzione**:
- Questo file contiene le variabili di ambiente. È utilizzato per memorizzare configurazioni specifiche dell'ambiente, come le credenziali del database, senza doverle includere direttamente nel codice.

**Contenuto Tipico**:
```
APP_NAME=LeafApp
APP_ENV=local
APP_DEBUG=true
APP_URL=http://localhost

DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=leafapp
DB_USERNAME=root
DB_PASSWORD=secret
```

#### 7. `composer.json`

**Funzione**:
- Questo file è il gestore delle dipendenze del progetto. Contiene le informazioni sul progetto e le dipendenze necessarie che Composer utilizzerà per installare i pacchetti.

**Contenuto Tipico**:
```json
{
    "name": "yourname/leafapp",
    "description": "A simple Leaf PHP application",
    "require": {
        "leafs/leaf": "^2.4"
    },
    "autoload": {
        "psr-4": {
            "App\\": "app/"
        }
    }
}
```

#### 8. `composer.lock`

**Funzione**:
- Questo file viene generato automaticamente da Composer e contiene le versioni esatte delle dipendenze installate. Garantisce che le stesse versioni dei pacchetti vengano installate su tutte le macchine.

#### 9. `storage/logs/`

**Funzione**:
- Questa directory contiene i file di log dell'applicazione. I log possono essere utilizzati per il debugging e il monitoraggio delle operazioni dell'applicazione.

#### 10. `storage/cache/`

**Funzione**:
- Questa directory contiene i file di cache generati dall'applicazione. La cache può migliorare le prestazioni dell'applicazione riducendo il carico di lavoro del server.


Questi file e directory costituiscono la spina dorsale di un progetto Leaf PHP. Organizzando il progetto in modo chiaro e mantenendo una struttura ben definita, si facilita la gestione del codice, la collaborazione con altri sviluppatori e la manutenzione del progetto a lungo termine.

### Gestione delle Risposte in Leaf PHP

La gestione delle risposte è una parte fondamentale di qualsiasi applicazione web. Leaf PHP fornisce diversi strumenti e metodi per creare e gestire risposte HTTP in modo efficiente e flessibile.

### Creazione di Risposte Semplici

In Leaf PHP, le risposte possono essere create e inviate facilmente all'interno delle callback delle rotte. Ecco alcuni esempi di risposte semplici:

```php
$app->get('/hello', function() {
    echo 'Hello, world!';
});
```

### Utilizzo della Classe `Response`

Leaf PHP include una classe `Response` che fornisce metodi per creare risposte più complesse. Puoi utilizzare la classe `Response` per impostare il codice di stato, gli header e il corpo della risposta.

#### Esempio di Utilizzo della Classe `Response`

```php
use Leaf\Http\Response;

$app->get('/json', function() {
    Response::json([
        'status' => 'success',
        'message' => 'This is a JSON response'
    ]);
});

$app->get('/redirect', function() {
    Response::redirect('/hello');
});
```

### Impostazione del Codice di Stato

Il codice di stato HTTP è una parte importante di una risposta HTTP, che indica il risultato della richiesta. Puoi impostare il codice di stato utilizzando la classe `Response`.

#### Esempio di Impostazione del Codice di Stato

```php
use Leaf\Http\Response;

$app->get('/not-found', function() {
    Response::status(404);
    echo 'Page not found';
});
```

### Impostazione degli Header

Gli header HTTP forniscono informazioni aggiuntive sulla risposta. Puoi impostare gli header personalizzati utilizzando la classe `Response`.

#### Esempio di Impostazione degli Header

```php
use Leaf\Http\Response;

$app->get('/headers', function() {
    Response::header('Content-Type', 'application/json');
    echo json_encode(['message' => 'Custom headers set']);
});
```

### Risposte JSON

Le risposte JSON sono comuni nelle API RESTful. Leaf PHP semplifica la creazione di risposte JSON con il metodo `Response::json`.

#### Esempio di Risposta JSON

```php
use Leaf\Http\Response;

$app->get('/data', function() {
    $data = [
        'name' => 'John Doe',
        'email' => 'john@example.com'
    ];
    Response::json($data);
});
```

### Redirezioni

Le redirezioni sono utili per reindirizzare gli utenti a un'altra pagina. Puoi creare redirezioni utilizzando il metodo `Response::redirect`.

#### Esempio di Redirezione

```php
use Leaf\Http\Response;

$app->get('/old-route', function() {
    Response::redirect('/new-route');
});
```

### Download di File

Leaf PHP consente di gestire facilmente il download di file. Puoi utilizzare il metodo `Response::download` per inviare file al client.

#### Esempio di Download di File

```php
use Leaf\Http\Response;

$app->get('/download', function() {
    $filePath = '/path/to/your/file.zip';
    Response::download($filePath, 'downloaded_file.zip');
});
```

### Gestione degli Errori

Leaf PHP ti consente di gestire facilmente gli errori e inviare risposte appropriate. Puoi utilizzare i metodi di `Response` per inviare messaggi di errore personalizzati.

#### Esempio di Gestione degli Errori

```php
use Leaf\Http\Response;

$app->get('/error', function() {
    if (someConditionFails()) {
        Response::status(500);
        Response::json([
            'error' => 'Internal Server Error'
        ]);
    }
});
```

### Middleware per la Gestione delle Risposte

Puoi anche utilizzare middleware per modificare o gestire le risposte prima che vengano inviate al client. I middleware possono essere utilizzati per aggiungere header comuni, gestire la cache o eseguire altre operazioni comuni.

#### Esempio di Middleware per la Gestione delle Risposte

```php
$app->get('/with-middleware', function() {
    echo 'Response with middleware';
})->middleware(function() {
    Response::header('X-Custom-Header', 'MiddlewareHeader');
});
```

La gestione delle risposte in Leaf PHP è potente e flessibile, permettendo di creare risposte HTTP personalizzate e di alta qualità. Utilizzando la classe `Response` e i metodi associati, puoi facilmente impostare codici di stato, header, risposte JSON, redirezioni, download di file e gestire gli errori in modo efficiente. Con l'uso di middleware, puoi inoltre aggiungere logica aggiuntiva per gestire le risposte in modo centralizzato e modulare.

### Middleware in Leaf PHP

I middleware sono componenti che vengono eseguiti durante il ciclo di vita di una richiesta HTTP, sia prima che la richiesta raggiunga il controller, sia dopo che il controller ha generato una risposta. I middleware possono essere utilizzati per varie funzioni, come l'autenticazione, la gestione della sessione, la registrazione delle richieste e la modifica delle risposte.

### Cos'è un Middleware?

Un middleware è una funzione o un insieme di funzioni che vengono eseguite in sequenza, permettendo di aggiungere logica intermedia tra la richiesta e la risposta. In Leaf PHP, i middleware possono essere applicati a singole rotte, gruppi di rotte o globalmente a tutte le rotte.

### Creazione di Middleware

Un middleware in Leaf PHP può essere una funzione anonima o una classe che implementa un'interfaccia specifica. Ecco alcuni esempi di middleware:

#### Middleware Come Funzione Anonima

```php
$app->get('/admin', function() {
    echo 'Welcome to the admin panel';
})->middleware(function() {
    // Logica di autenticazione
    if (!isLoggedIn()) {
        Response::redirect('/login');
        exit();
    }
});
```

In questo esempio, il middleware verifica se l'utente è autenticato prima di consentire l'accesso alla rotta `/admin`.

#### Middleware Come Classe

Puoi creare una classe middleware per organizzare meglio la tua logica middleware:

```php
namespace App\Middleware;

use Leaf\Http\Response;

class AuthMiddleware
{
    public function handle($request, $next)
    {
        if (!isLoggedIn()) {
            Response::redirect('/login');
            exit();
        }

        return $next($request);
    }
}
```

E poi applicare questo middleware a una rotta:

```php
$app->get('/admin', function() {
    echo 'Welcome to the admin panel';
})->middleware(new \App\Middleware\AuthMiddleware());
```

### Applicazione di Middleware a Gruppi di Rotte

Puoi applicare middleware a gruppi di rotte per condividere la logica tra più rotte.

```php
$app->group('/admin', function() use ($app) {
    $app->get('/dashboard', function() {
        echo 'Admin Dashboard';
    });

    $app->get('/settings', function() {
        echo 'Admin Settings';
    });
})->middleware(new \App\Middleware\AuthMiddleware());
```

In questo esempio, il middleware `AuthMiddleware` viene applicato a tutte le rotte all'interno del gruppo `/admin`.

### Applicazione di Middleware Globali

Puoi applicare middleware globali che verranno eseguiti per tutte le rotte dell'applicazione.

```php
$app->add(new \App\Middleware\AuthMiddleware());

$app->get('/admin/dashboard', function() {
    echo 'Admin Dashboard';
});

$app->get('/admin/settings', function() {
    echo 'Admin Settings';
});
```

### Esempi di Utilizzo Comune dei Middleware

#### 1. Autenticazione

Verifica se un utente è autenticato prima di consentire l'accesso a determinate rotte.

```php
$app->get('/profile', function() {
    echo 'User Profile';
})->middleware(function() {
    if (!isLoggedIn()) {
        Response::redirect('/login');
        exit();
    }
});
```

#### 2. Autorizzazione

Verifica se un utente ha i permessi necessari per accedere a una risorsa.

```php
$app->get('/admin', function() {
    echo 'Admin Area';
})->middleware(function() {
    if (!isAdmin()) {
        Response::status(403);
        echo 'Access Denied';
        exit();
    }
});
```

#### 3. Logging

Registra le informazioni sulle richieste per il monitoraggio e il debugging.

```php
$app->get('/dashboard', function() {
    echo 'Dashboard';
})->middleware(function($request) {
    logRequest($request);
    return $request;
});
```

#### 4. Modifica delle Risposte

Aggiunge header o modifica il contenuto delle risposte.

```php
$app->get('/api/data', function() {
    Response::json(['data' => 'Sample Data']);
})->middleware(function($request, $next) {
    $response = $next($request);
    $response->header('X-Custom-Header', 'Value');
    return $response;
});
```

I middleware in Leaf PHP offrono un modo potente e flessibile per gestire la logica comune delle richieste e delle risposte. Possono essere utilizzati per una vasta gamma di funzionalità, tra cui autenticazione, autorizzazione, logging e modifica delle risposte. Utilizzando middleware, puoi mantenere il tuo codice più pulito, modulare e riutilizzabile, applicando logica comune a più rotte in modo coerente.

### Gestione delle Richieste in Leaf PHP

Gestire le richieste HTTP in modo efficiente è fondamentale per lo sviluppo di applicazioni web robuste. Leaf PHP offre una serie di strumenti e metodi per accedere e manipolare i dati della richiesta, inclusi query string, payload (dati del corpo della richiesta) e header. Inoltre, la validazione delle richieste è essenziale per garantire che i dati ricevuti siano corretti e sicuri. Vediamo in dettaglio come gestire questi aspetti in Leaf PHP.

### Accesso ai Dati della Richiesta

#### Query String

I dati della query string sono i parametri passati nell'URL dopo il simbolo `?`. In Leaf PHP, è possibile accedere facilmente ai dati della query string utilizzando il metodo `Request::get`.

**Esempio di Accesso alla Query String**:

```php
use Leaf\Http\Request;

$app->get('/search', function() {
    $query = Request::get('q');
    echo "Search query: $query";
});
```

Se l'utente visita `/search?q=leaf`, la risposta sarà "Search query: leaf".

#### Payload

Il payload della richiesta contiene i dati inviati nel corpo della richiesta. Questo è comune nelle richieste POST, PUT e PATCH. Leaf PHP fornisce metodi per accedere a questi dati.

**Esempio di Accesso al Payload**:

```php
use Leaf\Http\Request;

$app->post('/submit', function() {
    $name = Request::get('name');
    $email = Request::get('email');
    echo "Name: $name, Email: $email";
});
```

Se l'utente invia una richiesta POST a `/submit` con `name=John` e `email=john@example.com`, la risposta sarà "Name: John, Email: john@example.com".

#### Headers

Gli header HTTP contengono metadati sulla richiesta. In Leaf PHP, puoi accedere agli header utilizzando il metodo `Request::header`.

**Esempio di Accesso agli Header**:

```php
use Leaf\Http\Request;

$app->get('/headers', function() {
    $userAgent = Request::header('User-Agent');
    echo "User Agent: $userAgent";
});
```

### Validazione delle Richieste

La validazione delle richieste è cruciale per assicurare che i dati ricevuti siano corretti e conformi ai requisiti dell'applicazione. Leaf PHP offre una classe di validazione che semplifica questo processo.

#### Regole di Validazione

Leaf PHP fornisce diverse regole di validazione predefinite come `required`, `email`, `min`, `max`, `string`, `numeric`, e molte altre.

**Esempio di Validazione di una Richiesta POST**:

```php
use Leaf\Validator;

$app->post('/register', function() {
    $validator = new Validator(Request::all());

    $validator->rules([
        'name' => 'required|string|min:3',
        'email' => 'required|email',
        'password' => 'required|string|min:6'
    ]);

    if ($validator->fails()) {
        Response::json([
            'status' => 'error',
            'errors' => $validator->errors()
        ], 422);
    } else {
        // Logica di registrazione dell'utente
        Response::json(['status' => 'success']);
    }
});
```

In questo esempio, la richiesta a `/register` deve includere `name`, `email` e `password`, ciascuno conforme alle rispettive regole di validazione.

#### Messaggi di Errore Personalizzati

Puoi anche personalizzare i messaggi di errore per ciascuna regola di validazione.

**Esempio di Messaggi di Errore Personalizzati**:

```php
$validator->messages([
    'name.required' => 'Il campo nome è obbligatorio.',
    'email.required' => 'Il campo email è obbligatorio.',
    'email.email' => 'L\'email deve essere un indirizzo email valido.',
    'password.required' => 'Il campo password è obbligatorio.',
    'password.min' => 'La password deve avere almeno 6 caratteri.'
]);
```

### Validazione Avanzata

Leaf PHP consente anche di creare regole di validazione personalizzate e complesse.

**Esempio di Regola di Validazione Personalizzata**:

```php
$validator->extend('username_unique', function($field, $value, $data) {
    return !User::where('username', $value)->exists();
}, 'Il nome utente è già in uso.');

$validator->rules([
    'username' => 'required|username_unique'
]);
```

### Middleware di Validazione

Puoi anche utilizzare middleware per centralizzare la logica di validazione, rendendo il codice più modulare e mantenibile.

**Esempio di Middleware di Validazione**:

```php
namespace App\Middleware;

use Leaf\Validator;
use Leaf\Http\Request;
use Leaf\Http\Response;

class ValidateRegister
{
    public function handle($request, $next)
    {
        $validator = new Validator(Request::all());

        $validator->rules([
            'name' => 'required|string|min:3',
            'email' => 'required|email',
            'password' => 'required|string|min:6'
        ]);

        if ($validator->fails()) {
            Response::json([
                'status' => 'error',
                'errors' => $validator->errors()
            ], 422);
            return;
        }

        return $next($request);
    }
}
```

E poi applicare il middleware:

```php
$app->post('/register', function() {
    // Logica di registrazione dell'utente
    Response::json(['status' => 'success']);
})->middleware(new \App\Middleware\ValidateRegister());
```

La gestione delle richieste in Leaf PHP è potente e flessibile, permettendo di accedere facilmente ai dati della richiesta, come query string, payload e header. La validazione delle richieste è altrettanto robusta, con supporto per regole di validazione predefinite, messaggi di errore personalizzati, regole personalizzate e middleware di validazione. Utilizzando questi strumenti, puoi assicurarti che la tua applicazione gestisca i dati delle richieste in modo sicuro e conforme ai requisiti del business.


### Template e View in Leaf PHP
In Leaf PHP, la gestione delle viste (view) e dei template è un aspetto fondamentale per separare la logica dell'applicazione dalla presentazione. Utilizzando un motore di template, è possibile creare facilmente layout complessi e riutilizzabili, mantenendo il codice organizzato e mantenibile.

### Utilizzo di BareUI in Leaf PHP

BareUI è un motore di template leggero e semplice che può essere utilizzato con Leaf PHP per la gestione delle viste e dei template. A differenza di Blade, BareUI è specificamente progettato per essere minimalista e facile da usare, offrendo un approccio diretto alla generazione di HTML dinamico.

### Installazione di BareUI

Per utilizzare BareUI con Leaf PHP, è necessario installarlo tramite Composer.

```bash
composer require leafs/bareui
```

### Configurazione di BareUI in Leaf PHP

Dopo aver installato BareUI, puoi configurarlo nella tua applicazione Leaf PHP. Ecco un esempio di configurazione:

```php
require '../vendor/autoload.php';

use Leaf\App;
use Leaf\BareUI;

// Inizializzazione di Leaf
$app = new App();

// Configurazione di BareUI
$views = __DIR__ . '/views';
BareUI::setPath($views);

$app->set('view', function () {
    global $views;
    return new BareUI($views);
});
```

### Creazione di Template

Con BareUI configurato, puoi iniziare a creare i tuoi file di template. I file di template di BareUI sono semplici file PHP.

**Esempio di Layout di Base:**

```php
<!-- /views/layouts/main.php -->
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title><?= $title ?? 'My Application' ?></title>
    <link rel="stylesheet" href="/css/style.css">
</head>
<body>
    <header>
        <h1>My Application</h1>
        <nav>
            <a href="/">Home</a>
            <a href="/about">About</a>
            <a href="/contact">Contact</a>
        </nav>
    </header>
    <main>
        <?= $content ?>
    </main>
    <footer>
        <p>&copy; 2024 My Application</p>
    </footer>
</body>
</html>
```

**Esempio di Pagina che Estende il Layout:**

```php
<!-- /views/home.php -->
<?php $this->layout('layouts/main', ['title' => 'Home Page']); ?>

<h2>Welcome to the Home Page</h2>
<p>This is the content of the home page.</p>
```

### Passaggio di Dati al Template

Per passare dati dal controller al template, puoi utilizzare il metodo `render` e passare i dati come array.

**Esempio di Passaggio di Dati:**

```php
$app->get('/', function() {
    app('view')->render('home', [
        'name' => 'John Doe',
        'title' => 'Welcome Page'
    ]);
});
```

Nel file di template, puoi accedere ai dati passati utilizzando variabili PHP:

```php
<!-- /views/home.php -->
<?php $this->layout('layouts/main', ['title' => $title]); ?>

<h2>Welcome, <?= $name ?>!</h2>
<p>This is the content of the welcome page.</p>
```

### Utilizzo di Componenti e Include

BareUI consente l'uso di inclusioni per riutilizzare parti di template.

**Esempio di Include:**

```php
<!-- /views/partials/header.php -->
<header>
    <h1>My Application</h1>
    <nav>
        <a href="/">Home</a>
        <a href="/about">About</a>
        <a href="/contact">Contact</a>
    </nav>
</header>

<!-- Include nel Template Principale -->
<?php $this->layout('layouts/main', ['title' => 'Home Page']); ?>

<?php $this->insert('partials/header'); ?>
<h2>Welcome to the Home Page</h2>
<p>This is the content of the home page.</p>
```

BareUI è un motore di template semplice e minimalista che si integra facilmente con Leaf PHP, offrendo un modo diretto per gestire template e viste. Utilizzando BareUI, puoi creare layout riutilizzabili, includere parti comuni di template e passare facilmente i dati ai template per generare HTML dinamico. Questo approccio mantiene il codice organizzato e leggibile, rendendo lo sviluppo web con Leaf PHP più efficiente e piacevole.

### Utilizzo di HTMX con Leaf PHP

HTMX è una libreria JavaScript che permette di costruire applicazioni web moderne utilizzando ipertesti estesi. Con HTMX, è possibile aggiornare parti specifiche di una pagina web senza dover ricaricare l'intera pagina. Quando combinato con Leaf PHP, HTMX offre un potente strumento per creare applicazioni web dinamiche e interattive mantenendo una struttura semplice e leggera.

### Installazione di HTMX

Per utilizzare HTMX in una tua applicazione, puoi includerlo direttamente nel tuo progetto tramite un CDN. Aggiungi il seguente script nel tuo layout principale:

```html
<!-- /views/layouts/main.php -->
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title><?= $title ?? 'My Application' ?></title>
    <link rel="stylesheet" href="/css/style.css">
    <script src="https://unpkg.com/htmx.org@1.8.4"></script>
</head>
<body>
    <header>
        <h1>My Application</h1>
        <nav>
            <a href="/">Home</a>
            <a href="/about">About</a>
            <a href="/contact">Contact</a>
        </nav>
    </header>
    <main>
        <?= $content ?>
    </main>
    <footer>
        <p>&copy; 2024 My Application</p>
    </footer>
</body>
</html>
```

### Creazione di una Pagina con HTMX

Per dimostrare come HTMX possa essere utilizzato con Leaf PHP, creeremo un semplice esempio in cui un contenuto viene caricato dinamicamente quando l'utente clicca un pulsante.

**Esempio di Template con HTMX:**

```php
<!-- /views/home.php -->
<?php $this->layout('layouts/main', ['title' => 'Home Page']); ?>

<h2>Welcome to the Home Page</h2>
<p>This is the content of the home page.</p>

<button hx-get="/load-more" hx-target="#more-content">Load More Content</button>

<div id="more-content"></div>
```

### Definizione del Route per il Contenuto Dinamico

Definiamo una route che restituisce il contenuto aggiuntivo da caricare quando l'utente clicca il pulsante.

**Esempio di Route in Leaf PHP:**

```php
$app->get('/load-more', function() {
    echo '<p>Here is some more content loaded dynamically!</p>';
});
```

Quando l'utente clicca il pulsante "Load More Content", HTMX invierà una richiesta GET a `/load-more` e inserirà la risposta all'interno del div con l'id `more-content`.

### Passaggio di Parametri con HTMX

HTMX permette di passare parametri alla richiesta utilizzando attributi come `hx-vals`, `hx-params`, e `hx-data`.

**Esempio di Passaggio di Parametri:**

```php
<!-- /views/home.php -->
<?php $this->layout('layouts/main', ['title' => 'Home Page']); ?>

<h2>Welcome to the Home Page</h2>
<p>This is the content of the home page.</p>

<button hx-get="/load-more" hx-target="#more-content" hx-vals='{"extra": "data"}'>Load More Content</button>

<div id="more-content"></div>
```

**Gestione dei Parametri nel Controller:**

```php
$app->get('/load-more', function() {
    $extra = Request::get('extra'); // Ottieni il parametro extra
    echo '<p>Here is some more content loaded dynamically! Extra data: ' . htmlspecialchars($extra) . '</p>';
});
```

### Esempio di Form Dinamico

Un altro uso comune di HTMX è l'invio di form e l'aggiornamento di parti della pagina con i risultati.

**Esempio di Form Dinamico:**

```php
<!-- /views/home.php -->
<?php $this->layout('layouts/main', ['title' => 'Home Page']); ?>

<h2>Welcome to the Home Page</h2>
<p>This is the content of the home page.</p>

<form hx-post="/submit-form" hx-target="#form-result">
    <input type="text" name="name" placeholder="Enter your name">
    <button type="submit">Submit</button>
</form>

<div id="form-result"></div>
```

**Definizione della Route per Gestire il Form:**

```php
$app->post('/submit-form', function() {
    $name = Request::get('name'); // Ottieni il nome dal form
    echo '<p>Form submitted! Hello, ' . htmlspecialchars($name) . '!</p>';
});
```

L'utilizzo di HTMX con Leaf PHP permette di creare applicazioni web dinamiche e interattive con una configurazione semplice e un overhead minimo. Con HTMX, puoi facilmente aggiornare parti specifiche di una pagina senza ricaricare l'intera pagina, migliorando l'esperienza utente e mantenendo il codice organizzato e leggibile. Utilizzando BareUI per la gestione dei template e HTMX per l'interattività, puoi costruire applicazioni web moderne e reattive in modo efficiente.

### Utilizzo di Twig con Leaf PHP

Twig è un motore di template potente e flessibile per PHP, ampiamente utilizzato per la sua sintassi pulita e la capacità di separare la logica di presentazione dal codice dell'applicazione. Integrarlo con Leaf PHP permette di creare applicazioni web con una struttura ben organizzata e facile da mantenere.

### Installazione di Twig

Per utilizzare Twig con Leaf PHP, è necessario installarlo tramite Composer.

```bash
composer require twig/twig
```

### Configurazione di Twig in Leaf PHP

Dopo aver installato Twig, puoi configurarlo nella tua applicazione Leaf PHP. Ecco un esempio di configurazione:

```php
require '../vendor/autoload.php';

use Leaf\App;
use Leaf\View\Twig as TwigView;
use Twig\Loader\FilesystemLoader;
use Twig\Environment;

// Inizializzazione di Leaf
$app = new App();

// Configurazione di Twig
$loader = new FilesystemLoader(__DIR__ . '/views');
$twig = new Environment($loader);

$app->set('view', function () use ($twig) {
    return new TwigView($twig);
});
```

### Creazione di Template

Con Twig configurato, puoi iniziare a creare i tuoi file di template. I file di template di Twig hanno estensione `.twig`.

**Esempio di Layout di Base:**

```twig
{# /views/layouts/main.twig #}
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>{{ title }}</title>
    <link rel="stylesheet" href="/css/style.css">
</head>
<body>
    <header>
        <h1>My Application</h1>
        <nav>
            <a href="/">Home</a>
            <a href="/about">About</a>
            <a href="/contact">Contact</a>
        </nav>
    </header>
    <main>
        {% block content %}{% endblock %}
    </main>
    <footer>
        <p>&copy; 2024 My Application</p>
    </footer>
</body>
</html>
```

**Esempio di Pagina che Estende il Layout:**

```twig
{# /views/home.twig #}
{% extends 'layouts/main.twig' %}

{% block content %}
    <h2>Welcome to the Home Page</h2>
    <p>This is the content of the home page.</p>
{% endblock %}
```

### Passaggio di Dati al Template

Per passare dati dal controller al template, puoi utilizzare il metodo `render` e passare i dati come array.

**Esempio di Passaggio di Dati:**

```php
$app->get('/', function() {
    app('view')->render('home.twig', [
        'name' => 'John Doe',
        'title' => 'Welcome Page'
    ]);
});
```

Nel file di template, puoi accedere ai dati passati utilizzando le variabili Twig:

```twig
{# /views/home.twig #}
{% extends 'layouts/main.twig' %}

{% block content %}
    <h2>Welcome, {{ name }}!</h2>
    <p>This is the content of the welcome page.</p>
{% endblock %}
```

### Utilizzo di Include e Macro

Twig supporta l'uso di inclusioni e macro per riutilizzare parti di template.

**Esempio di Include:**

```twig
{# /views/partials/header.twig #}
<header>
    <h1>My Application</h1>
    <nav>
        <a href="/">Home</a>
        <a href="/about">About</a>
        <a href="/contact">Contact</a>
    </nav>
</header>

{# Include nel Template Principale #}
{% extends 'layouts/main.twig' %}

{% block content %}
    {% include 'partials/header.twig' %}
    <h2>Welcome to the Home Page</h2>
    <p>This is the content of the home page.</p>
{% endblock %}
```

**Esempio di Macro:**

```twig
{# /views/macros.twig #}
{% macro input(name, placeholder) %}
    <input type="text" name="{{ name }}" placeholder="{{ placeholder }}">
{% endmacro %}

{# Utilizzo della Macro nel Template #}
{% extends 'layouts/main.twig' %}
{% import 'macros.twig' as forms %}

{% block content %}
    <h2>Welcome to the Home Page</h2>
    <p>This is the content of the home page.</p>
    <form>
        {{ forms.input('name', 'Enter your name') }}
    </form>
{% endblock %}
```

### Esempio di Form Dinamico

Un altro uso comune di Twig è la gestione di form e la visualizzazione dei dati inseriti dall'utente.

**Esempio di Form Dinamico:**

```twig
{# /views/home.twig #}
{% extends 'layouts/main.twig' %}

{% block content %}
    <h2>Welcome to the Home Page</h2>
    <p>This is the content of the home page.</p>
    
    <form action="/submit-form" method="post">
        <input type="text" name="name" placeholder="Enter your name">
        <button type="submit">Submit</button>
    </form>
    
    {% if name %}
        <p>Form submitted! Hello, {{ name }}!</p>
    {% endif %}
{% endblock %}
```

**Definizione della Route per Gestire il Form:**

```php
$app->post('/submit-form', function() {
    $name = Request::get('name'); // Ottieni il nome dal form
    app('view')->render('home.twig', ['name' => $name]);
});
```

L'utilizzo di Twig con Leaf PHP permette di creare applicazioni web con una struttura ben organizzata e una chiara separazione tra logica e presentazione. Twig offre una sintassi potente e flessibile per gestire template complessi, inclusioni e macro, facilitando la creazione di layout riutilizzabili e la gestione dei dati. Integrando Twig con Leaf PHP, puoi costruire applicazioni web moderne, mantenibili e efficienti.

### Gestione dei Database con Leaf PHP

Leaf PHP è un micro-framework che facilita lo sviluppo di applicazioni web semplici e veloci. Uno degli aspetti fondamentali nello sviluppo di qualsiasi applicazione web è la gestione dei database. Leaf offre diversi strumenti per interagire con i database, dalla connessione al CRUD (Create, Read, Update, Delete), utilizzando ORM (Object-Relational Mapping) e query builder per semplificare le operazioni.

### Connessione al Database

La prima cosa da fare è stabilire una connessione al database. Leaf utilizza PDO (PHP Data Objects) per interagire con il database, il che offre una modalità sicura e flessibile per eseguire query SQL.

**Esempio di Connessione a un Database MySQL:**

```php
require '../vendor/autoload.php';

use Leaf\App;
use Leaf\Db;

// Inizializzazione di Leaf
$app = new App();

// Configurazione della Connessione al Database
Db::connect('mysql:host=localhost;dbname=testdb', 'username', 'password');
```

### CRUD con Leaf PHP

Una volta stabilita la connessione, puoi iniziare a eseguire operazioni CRUD. Leaf fornisce metodi semplici per queste operazioni di base.

#### Create (Inserimento)

Per inserire dati in una tabella del database, puoi utilizzare il metodo `Db::insert`.

```php
$data = [
    'name' => 'John Doe',
    'email' => 'john@example.com',
    'age' => 30
];

Db::table('users')->insert($data);
```

#### Read (Lettura)

Per leggere dati da una tabella, puoi utilizzare il metodo `Db::select`.

**Esempio di Lettura di Tutti i Record:**

```php
$users = Db::table('users')->select('*')->fetchAll();
```

**Esempio di Lettura di un Singolo Record:**

```php
$user = Db::table('users')->where('id', 1)->select('*')->fetch();
```

#### Update (Aggiornamento)

Per aggiornare un record nel database, utilizza il metodo `Db::update`.

```php
$data = [
    'email' => 'john.doe@example.com',
    'age' => 31
];

Db::table('users')->where('id', 1)->update($data);
```

#### Delete (Cancellazione)

Per cancellare un record dal database, utilizza il metodo `Db::delete`.

```php
Db::table('users')->where('id', 1)->delete();
```

### ORM (Object-Relational Mapping)

Leaf PHP supporta anche l'ORM tramite Leaf Model, che mappa le tabelle del database a classi PHP, permettendo di interagire con i dati come se fossero oggetti.

**Definizione di un Modello:**

```php
use Leaf\Model;

class User extends Model {
    protected $table = 'users';
}
```

**Esempio di Utilizzo del Modello:**

```php
// Create
$user = new User();
$user->name = 'Jane Doe';
$user->email = 'jane@example.com';
$user->age = 25;
$user->save();

// Read
$user = User::find(1);

// Update
$user = User::find(1);
$user->email = 'jane.doe@example.com';
$user->save();

// Delete
$user = User::find(1);
$user->delete();
```

### Query Builder

Leaf PHP include un query builder che rende più semplice scrivere query SQL complesse utilizzando una sintassi fluida e leggibile.

**Esempio di Query Complessa:**

```php
$results = Db::table('users')
    ->join('orders', 'users.id', '=', 'orders.user_id')
    ->where('users.age', '>', 18)
    ->where('orders.status', 'completed')
    ->select('users.name', 'orders.total')
    ->orderBy('orders.total', 'desc')
    ->fetchAll();
```

### Esempi di Query Complesse

#### Selezione con Condizioni Multiple

```php
$users = Db::table('users')
    ->where('age', '>', 25)
    ->where('email', 'LIKE', '%@example.com')
    ->select('*')
    ->fetchAll();
```

#### Aggregazioni

```php
$totalOrders = Db::table('orders')
    ->where('status', 'completed')
    ->sum('total');
```

#### Raggruppamento e Ordinamento

```php
$users = Db::table('users')
    ->select('age', Db::raw('COUNT(*) as count'))
    ->groupBy('age')
    ->orderBy('count', 'desc')
    ->fetchAll();
```

#### Paginazione

```php
$page = 1;
$perPage = 10;
$users = Db::table('users')
    ->limit($perPage)
    ->offset(($page - 1) * $perPage)
    ->select('*')
    ->fetchAll();
```

Leaf PHP rende la gestione dei database semplice e intuitiva grazie a strumenti come il query builder e l'ORM. Con metodi facili da usare per le operazioni CRUD e la possibilità di scrivere query SQL complesse in modo leggibile, Leaf PHP è una scelta eccellente per sviluppatori che cercano un framework leggero ma potente per costruire applicazioni web. Utilizzando questi strumenti, puoi mantenere il tuo codice organizzato e facilmente manutenibile, permettendoti di concentrarti sulle funzionalità della tua applicazione piuttosto che sulla complessità della gestione del database.

### Cos'è l'Aggregazione nel Contesto dei Database?

L'aggregazione nei database è un insieme di operazioni che riassumono gruppi di dati per ottenere informazioni statistiche come somme, medie, conteggi, minimi e massimi. Queste operazioni sono essenziali per analizzare e riassumere grandi volumi di dati in modo efficiente.

### Operazioni di Aggregazione Comuni

1. **SUM**: Somma dei valori di una colonna.
2. **AVG**: Media dei valori di una colonna.
3. **COUNT**: Conteggio del numero di righe.
4. **MAX**: Valore massimo di una colonna.
5. **MIN**: Valore minimo di una colonna.

### Esempi di Aggregazioni con SQL

**Esempio di Somma (SUM):**

```sql
SELECT SUM(amount) as total_amount
FROM orders
WHERE status = 'completed';
```

**Esempio di Media (AVG):**

```sql
SELECT AVG(age) as average_age
FROM users
WHERE gender = 'female';
```

**Esempio di Conteggio (COUNT):**

```sql
SELECT COUNT(*) as total_users
FROM users;
```

**Esempio di Massimo (MAX):**

```sql
SELECT MAX(salary) as highest_salary
FROM employees;
```

**Esempio di Minimo (MIN):**

```sql
SELECT MIN(price) as lowest_price
FROM products;
```

### Aggregazioni con Raggruppamento

Le aggregazioni diventano particolarmente potenti quando vengono utilizzate in combinazione con l'istruzione `GROUP BY`, che consente di raggruppare i dati in base a una o più colonne e poi applicare funzioni di aggregazione a ciascun gruppo.

**Esempio di Conteggio con Raggruppamento:**

```sql
SELECT department, COUNT(*) as num_employees
FROM employees
GROUP BY department;
```

**Esempio di Somma con Raggruppamento:**

```sql
SELECT customer_id, SUM(total) as total_spent
FROM orders
GROUP BY customer_id;
```

### Esempi di Aggregazioni con Leaf PHP

#### Conteggio

```php
$totalUsers = Db::table('users')->count();
```

#### Somma

```php
$totalSales = Db::table('orders')->where('status', 'completed')->sum('total');
```

#### Media

```php
$averageAge = Db::table('users')->avg('age');
```

#### Massimo

```php
$highestSalary = Db::table('employees')->max('salary');
```

#### Minimo

```php
$lowestPrice = Db::table('products')->min('price');
```

### Raggruppamento e Aggregazione con Leaf PHP

**Conteggio con Raggruppamento:**

```php
$employeeCounts = Db::table('employees')
    ->select('department', Db::raw('COUNT(*) as num_employees'))
    ->groupBy('department')
    ->fetchAll();
```

**Somma con Raggruppamento:**

```php
$customerSpending = Db::table('orders')
    ->select('customer_id', Db::raw('SUM(total) as total_spent'))
    ->groupBy('customer_id')
    ->fetchAll();
```

Le operazioni di aggregazione sono fondamentali per riassumere e analizzare i dati nei database. Utilizzando funzioni di aggregazione come SUM, AVG, COUNT, MAX e MIN, è possibile ottenere rapidamente statistiche utili dai dati. In combinazione con l'istruzione `GROUP BY`, queste operazioni diventano ancora più potenti, permettendo di analizzare i dati in gruppi logici. Leaf PHP semplifica l'uso delle aggregazioni attraverso il suo query builder, rendendo facile eseguire queste operazioni e mantenere il codice pulito e leggibile.

### Gestione degli Errori, Eccezioni e Pagine di Errore in Leaf PHP

La gestione degli errori è una parte fondamentale dello sviluppo di applicazioni web robuste e affidabili. Leaf PHP offre strumenti per gestire errori ed eccezioni in modo efficace, consentendo di creare pagine di errore personalizzate che migliorano l'esperienza dell'utente.

### Gestione degli Errori ed Eccezioni

Leaf PHP fornisce un gestore di errori integrato che permette di intercettare e gestire errori ed eccezioni in modo centralizzato. Questo è particolarmente utile per mantenere il codice pulito e per fornire messaggi di errore chiari e coerenti.

#### Configurazione del Gestore di Errori

Per configurare il gestore di errori in Leaf PHP, puoi utilizzare il metodo `errorHandler`. Ecco un esempio:

```php
require '../vendor/autoload.php';

use Leaf\App;

$app = new App();

// Configurazione del gestore di errori
$app->set('errorHandler', function() {
    return function($request, $response, $exception) {
        $status = $exception->getCode() ?: 500;
        $response->write("Oops! Something went wrong. Error: " . $exception->getMessage());
        $response->withStatus($status);
        return $response;
    };
});

// Un esempio di route che genera un'eccezione
$app->get('/error', function() {
    throw new Exception("This is a test exception.");
});

$app->run();
```

### Creazione di Pagine di Errore Personalizzate

Per migliorare l'esperienza utente, è importante fornire pagine di errore personalizzate per diversi tipi di errori, come errori 404 (Pagina non trovata) o 500 (Errore interno del server).

#### Gestione degli Errori 404

Per gestire gli errori 404, puoi utilizzare il metodo `notFound`. Ecco un esempio di configurazione:

```php
$app->set('notFound', function($request, $response) {
    $response->write("Page not found. It looks like you're lost.");
    $response->withStatus(404);
    return $response;
});
```

#### Gestione degli Errori 500

Gli errori 500 possono essere gestiti tramite il gestore di errori configurato precedentemente. È possibile personalizzare ulteriormente la gestione degli errori 500.

```php
$app->set('errorHandler', function() {
    return function($request, $response, $exception) {
        $status = $exception->getCode() ?: 500;
        $response->write("Internal Server Error. Please try again later.");
        $response->withStatus($status);
        return $response;
    };
});
```

### Esempio Completo di Gestione degli Errori

Di seguito è riportato un esempio completo che include la gestione degli errori 404 e 500, nonché la configurazione di pagine di errore personalizzate.

```php
require '../vendor/autoload.php';

use Leaf\App;

$app = new App();

// Configurazione del gestore di errori
$app->set('errorHandler', function() {
    return function($request, $response, $exception) {
        $status = $exception->getCode() ?: 500;
        $response->write("Internal Server Error. Please try again later.");
        $response->withStatus($status);
        return $response;
    };
});

// Gestione degli errori 404
$app->set('notFound', function($request, $response) {
    $response->write("Page not found. It looks like you're lost.");
    $response->withStatus(404);
    return $response;
});

// Un esempio di route che genera un'eccezione
$app->get('/error', function() {
    throw new Exception("This is a test exception.");
});

// Un esempio di route esistente
$app->get('/', function() {
    echo "Welcome to the home page!";
});

$app->run();
```

### Logging degli Errori

Oltre a gestire gli errori e mostrare pagine di errore personalizzate, è buona pratica registrare gli errori in un file di log per la diagnosi e il debug. Leaf PHP può essere configurato per utilizzare un logger.

#### Configurazione di un Logger

Per configurare un logger, puoi utilizzare una libreria di logging come Monolog. Ecco un esempio di configurazione:

```php
require '../vendor/autoload.php';

use Leaf\App;
use Monolog\Logger;
use Monolog\Handler\StreamHandler;

$app = new App();

// Creazione del logger
$log = new Logger('app');
$log->pushHandler(new StreamHandler(__DIR__ . '/logs/app.log', Logger::ERROR));

// Configurazione del gestore di errori con logging
$app->set('errorHandler', function() use ($log) {
    return function($request, $response, $exception) use ($log) {
        $log->error($exception->getMessage(), ['exception' => $exception]);
        $status = $exception->getCode() ?: 500;
        $response->write("Internal Server Error. Please try again later.");
        $response->withStatus($status);
        return $response;
    };
});

// Gestione degli errori 404
$app->set('notFound', function($request, $response) {
    $response->write("Page not found. It looks like you're lost.");
    $response->withStatus(404);
    return $response;
});

// Un esempio di route che genera un'eccezione
$app->get('/error', function() {
    throw new Exception("This is a test exception.");
});

// Un esempio di route esistente
$app->get('/', function() {
    echo "Welcome to the home page!";
});

$app->run();
```

La gestione degli errori ed eccezioni in Leaf PHP è fondamentale per creare applicazioni robuste e user-friendly. Configurare correttamente i gestori di errori, creare pagine di errore personalizzate e implementare il logging degli errori aiuta a migliorare l'esperienza utente e facilita il processo di debug e manutenzione dell'applicazione. Utilizzando queste tecniche, puoi assicurarti che la tua applicazione gestisca gli errori in modo elegante e fornisca feedback utili agli utenti e agli sviluppatori.

### Gestione degli Utenti con Leaf PHP

La gestione degli utenti è una funzionalità cruciale in molte applicazioni web. Con Leaf PHP, puoi implementare registrazione, login, gestione dei profili e altre funzionalità relative agli utenti in modo efficace e sicuro.

### Struttura del Progetto

Prima di iniziare, è utile organizzare il progetto in modo logico. Ecco una possibile struttura delle directory:

```
/project-root
  /app
    /controllers
      AuthController.php
      UserController.php
    /models
      User.php
  /config
    database.php
  /public
    index.php
  /vendor
  /views
    login.php
    register.php
    profile.php
  .env
  composer.json
```

### Configurazione del Database

1. **Installazione delle dipendenze**

Assicurati di avere `leaf/leaf` e `leaf/db` installati tramite Composer:

```bash
composer require leafs/leaf leafs/db
```

2. **Configurazione del database**

Crea un file `.env` nella root del progetto per configurare le variabili di ambiente:

```env
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=mydatabase
DB_USERNAME=myusername
DB_PASSWORD=mypassword
```

Carica le variabili di ambiente nel file di configurazione del database (`config/database.php`):

```php
<?php

Leaf\Config::loadEnv();

Leaf\Db::connect([
    'driver' => getenv('DB_CONNECTION'),
    'host' => getenv('DB_HOST'),
    'port' => getenv('DB_PORT'),
    'database' => getenv('DB_DATABASE'),
    'username' => getenv('DB_USERNAME'),
    'password' => getenv('DB_PASSWORD'),
    'charset' => 'utf8mb4',
    'collation' => 'utf8mb4_unicode_ci',
    'prefix' => '',
]);
```

### Modello Utente

Crea un modello per rappresentare gli utenti (`app/models/User.php`):

```php
<?php

namespace App\Models;

use Leaf\Db;

class User extends Db
{
    protected $table = 'users';

    public static function createUser($data)
    {
        return self::table('users')->insert($data);
    }

    public static function findUserByEmail($email)
    {
        return self::table('users')->where('email', $email)->first();
    }
}
```

### Controller di Autenticazione

Crea un controller per gestire l'autenticazione (`app/controllers/AuthController.php`):

```php
<?php

namespace App\Controllers;

use Leaf\Http\Request;
use Leaf\Http\Response;
use App\Models\User;

class AuthController
{
    public function showRegister()
    {
        return view('register');
    }

    public function register()
    {
        $data = Request::all();

        // Validazione dei dati
        if (empty($data['email']) || empty($data['password'])) {
            return Response::json(['error' => 'Email and password are required'], 400);
        }

        // Hash della password
        $data['password'] = password_hash($data['password'], PASSWORD_DEFAULT);

        // Creazione dell'utente
        User::createUser($data);

        return Response::json(['message' => 'User registered successfully']);
    }

    public function showLogin()
    {
        return view('login');
    }

    public function login()
    {
        $data = Request::all();
        $user = User::findUserByEmail($data['email']);

        if (!$user || !password_verify($data['password'], $user['password'])) {
            return Response::json(['error' => 'Invalid credentials'], 401);
        }

        // Impostazione della sessione
        session_start();
        $_SESSION['user'] = $user;

        return Response::json(['message' => 'Login successful']);
    }

    public function logout()
    {
        session_start();
        session_destroy();

        return Response::json(['message' => 'Logged out successfully']);
    }
}
```

### Rotte per la Gestione degli Utenti

Configura le rotte nel file di ingresso (`public/index.php`):

```php
require '../vendor/autoload.php';

use Leaf\App;
use App\Controllers\AuthController;
use Leaf\Db;

$app = new App();

require '../config/database.php';

// Rotte di autenticazione
$app->get('/register', [AuthController::class, 'showRegister']);
$app->post('/register', [AuthController::class, 'register']);
$app->get('/login', [AuthController::class, 'showLogin']);
$app->post('/login', [AuthController::class, 'login']);
$app->get('/logout', [AuthController::class, 'logout']);

// Esempio di rotta protetta
$app->get('/profile', function() {
    session_start();
    if (!isset($_SESSION['user'])) {
        return Response::json(['error' => 'Unauthorized'], 401);
    }
    return view('profile', ['user' => $_SESSION['user']]);
});

$app->run();
```

### Creazione delle Tabelle nel Database

Crea le tabelle necessarie nel database utilizzando una migrazione. Ecco un esempio di script SQL per creare la tabella `users`:

```sql
CREATE TABLE `users` (
  `id` INT AUTO_INCREMENT PRIMARY KEY,
  `email` VARCHAR(255) NOT NULL UNIQUE,
  `password` VARCHAR(255) NOT NULL,
  `created_at` TIMESTAMP DEFAULT CURRENT_TIMESTAMP,
  `updated_at` TIMESTAMP DEFAULT CURRENT_TIMESTAMP ON UPDATE CURRENT_TIMESTAMP
);
```

### Vista per la Registrazione e il Login

Crea le viste per la registrazione e il login (`views/register.php` e `views/login.php`):

**register.php:**

```php
<!DOCTYPE html>
<html>
<head>
    <title>Register</title>
</head>
<body>
    <h1>Register</h1>
    <form action="/register" method="POST">
        <label for="email">Email:</label>
        <input type="email" name="email" required><br>
        <label for="password">Password:</label>
        <input type="password" name="password" required><br>
        <button type="submit">Register</button>
    </form>
</body>
</html>
```

**login.php:**

```php
<!DOCTYPE html>
<html>
<head>
    <title>Login</title>
</head>
<body>
    <h1>Login</h1>
    <form action="/login" method="POST">
        <label for="email">Email:</label>
        <input type="email" name="email" required><br>
        <label for="password">Password:</label>
        <input type="password" name="password" required><br>
        <button type="submit">Login</button>
    </form>
</body>
</html>
```

**profile.php:**

```php
<!DOCTYPE html>
<html>
<head>
    <title>Profile</title>
</head>
<body>
    <h1>Profile</h1>
    <p>Welcome, <?php echo $user['email']; ?>!</p>
    <a href="/logout">Logout</a>
</body>
</html>
```

La gestione degli utenti con Leaf PHP può essere implementata in modo semplice ed efficace utilizzando sessioni o token JWT per l'autenticazione e middleware per proteggere le rotte. La struttura del progetto organizzata e l'uso di modelli e controller contribuiscono a mantenere il codice pulito e manutenibile. Con queste basi, puoi estendere ulteriormente la funzionalità per gestire ruoli, permessi, reset delle password e altre caratteristiche avanzate di gestione degli utenti.

### Autenticazione e Autorizzazione in Leaf PHP

L'autenticazione e l'autorizzazione sono componenti cruciali di molte applicazioni web, garantendo che solo utenti autorizzati possano accedere a determinate risorse o eseguire specifiche azioni. Leaf PHP offre strumenti e middleware per gestire queste funzionalità in modo semplice e sicuro.

### Autenticazione

L'autenticazione è il processo di verifica dell'identità di un utente. In Leaf PHP, puoi implementare l'autenticazione utilizzando vari metodi come sessioni, token JWT (JSON Web Token), o altre tecniche basate su API.

#### Autenticazione con Sessioni

L'autenticazione con sessioni è comune nelle applicazioni web. Ecco un esempio di implementazione di autenticazione con sessioni in Leaf PHP:

1. **Configurazione del middleware di sessione**

```php
require '../vendor/autoload.php';

use Leaf\App;
use Leaf\Http\Session;

$app = new App();
$session = new Session();
$session->start();
```

2. **Implementazione del login**

```php
$app->post('/login', function() use ($session) {
    $username = $_POST['username'];
    $password = $_POST['password'];

    // Verifica delle credenziali dell'utente
    if ($username === 'admin' && $password === 'password') {
        $session->set('user', $username);
        echo "Login successful";
    } else {
        echo "Invalid credentials";
    }
});
```

3. **Protezione delle route**

Per proteggere le route, puoi creare un middleware che verifica se l'utente è autenticato.

```php
$app->set('auth', function() use ($session) {
    return function($request, $response, $next) use ($session) {
        if (!$session->has('user')) {
            $response->write("Unauthorized");
            return $response->withStatus(401);
        }
        return $next($request, $response);
    };
});

// Utilizzo del middleware di autenticazione
$app->get('/dashboard', 'auth', function() {
    echo "Welcome to the dashboard!";
});
```

4. **Logout**

Per gestire il logout dell'utente, basta distruggere la sessione.

```php
$app->get('/logout', function() use ($session) {
    $session->destroy();
    echo "Logged out successfully";
});
```

### Autenticazione con JWT

L'autenticazione basata su JWT è ampiamente utilizzata nelle API. JWT sono token che possono essere firmati e verificati, permettendo di gestire sessioni stateless.

1. **Installazione della libreria JWT**

```bash
composer require firebase/php-jwt
```

2. **Generazione del token JWT**

```php
use \Firebase\JWT\JWT;

$key = "example_key";
$payload = [
    'iss' => 'http://example.org',
    'aud' => 'http://example.com',
    'iat' => 1356999524,
    'nbf' => 1357000000,
];

$jwt = JWT::encode($payload, $key);
echo "Token: " . $jwt;
```

3. **Verifica del token JWT**

```php
$decoded = JWT::decode($jwt, $key, array('HS256'));
print_r($decoded);
```

4. **Middleware per la verifica del token**

```php
$app->set('jwtAuth', function() use ($key) {
    return function($request, $response, $next) use ($key) {
        $authHeader = $request->getHeader('Authorization');
        if ($authHeader) {
            list($jwt) = sscanf($authHeader[0], 'Bearer %s');
            if ($jwt) {
                try {
                    JWT::decode($jwt, $key, ['HS256']);
                    return $next($request, $response);
                } catch (Exception $e) {
                    $response->write("Unauthorized: " . $e->getMessage());
                    return $response->withStatus(401);
                }
            }
        }
        $response->write("Unauthorized");
        return $response->withStatus(401);
    };
});

// Utilizzo del middleware JWT
$app->get('/protected', 'jwtAuth', function() {
    echo "This is a protected route!";
});
```

### Autorizzazione

L'autorizzazione determina se un utente autenticato ha il permesso di eseguire una determinata azione o accedere a una risorsa specifica. Puoi gestire l'autorizzazione utilizzando ruoli e permessi.

#### Esempio di Middleware di Autorizzazione

1. **Definizione dei ruoli**

```php
$roles = [
    'admin' => ['create', 'edit', 'delete'],
    'editor' => ['create', 'edit'],
    'viewer' => ['view'],
];
```

2. **Middleware di autorizzazione**

```php
$app->set('authorize', function($role, $permission) use ($roles) {
    return function($request, $response, $next) use ($role, $permission, $roles) {
        if (!in_array($permission, $roles[$role])) {
            $response->write("Forbidden");
            return $response->withStatus(403);
        }
        return $next($request, $response);
    };
});

// Utilizzo del middleware di autorizzazione
$app->get('/admin', ['auth', 'authorize:admin,edit'], function() {
    echo "Welcome Admin!";
});
```

Leaf PHP offre strumenti potenti per gestire l'autenticazione e l'autorizzazione. Utilizzando sessioni o JWT per l'autenticazione e middleware per la protezione delle route, puoi garantire che solo gli utenti autorizzati possano accedere a determinate parti della tua applicazione. La gestione di ruoli e permessi attraverso middleware di autorizzazione permette di mantenere il controllo granulare sulle azioni consentite agli utenti. Implementando queste pratiche, puoi migliorare la sicurezza e l'affidabilità della tua applicazione web.

### Tutorial Dettagliato su Leaf Auth

Leaf Auth è un potente strumento per gestire l'autenticazione degli utenti nelle applicazioni Leaf PHP. Questo tutorial ti guiderà passo dopo passo attraverso l'installazione, la configurazione e l'uso di Leaf Auth per creare un sistema di autenticazione completo, incluse registrazione, login, gestione delle sessioni e protezione delle rotte.

### Struttura del Progetto

Iniziamo con una struttura di directory consigliata per organizzare il nostro progetto:

```
/project-root
  /app
    /controllers
      AuthController.php
    /models
      User.php
  /config
    database.php
  /public
    index.php
  /vendor
  /views
    login.php
    register.php
    profile.php
  .env
  composer.json
```

### Installazione

Assicurati di avere Composer installato. Poi, installa Leaf e Leaf Auth:

```bash
composer require leafs/leaf leafs/auth leafs/db leafs/validate
```

### Configurazione del Database

Crea un file `.env` nella root del progetto per configurare le variabili di ambiente:

```env
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=mydatabase
DB_USERNAME=myusername
DB_PASSWORD=mypassword
```

Carica le variabili di ambiente e configura il database in `config/database.php`:

```php
<?php

Leaf\Config::loadEnv();

Leaf\Db::connect([
    'driver' => getenv('DB_CONNECTION'),
    'host' => getenv('DB_HOST'),
    'port' => getenv('DB_PORT'),
    'database' => getenv('DB_DATABASE'),
    'username' => getenv('DB_USERNAME'),
    'password' => getenv('DB_PASSWORD'),
    'charset' => 'utf8mb4',
    'collation' => 'utf8mb4_unicode_ci',
    'prefix' => '',
]);
```

### Creazione della Tabella Utenti

Esegui il seguente script SQL per creare la tabella `users`:

```sql
CREATE TABLE `users` (
  `id` INT AUTO_INCREMENT PRIMARY KEY,
  `email` VARCHAR(255) NOT NULL UNIQUE,
  `password` VARCHAR(255) NOT NULL,
  `created_at` TIMESTAMP DEFAULT CURRENT_TIMESTAMP,
  `updated_at` TIMESTAMP DEFAULT CURRENT_TIMESTAMP ON UPDATE CURRENT_TIMESTAMP
);
```

### Modello Utente

Crea un modello per rappresentare gli utenti (`app/models/User.php`):

```php
<?php

namespace App\Models;

use Leaf\Db;

class User extends Db
{
    protected $table = 'users';
}
```

### Controller di Autenticazione

Crea un controller per gestire l'autenticazione (`app/controllers/AuthController.php`):

```php
<?php

namespace App\Controllers;

use Leaf\Http\Request;
use Leaf\Http\Response;
use Leaf\Auth;
use App\Models\User;

class AuthController
{
    public function showRegister()
    {
        return view('register');
    }

    public function register()
    {
        $data = Request::all();

        // Validazione dei dati
        $validation = \Leaf\Validate::make($data, [
            'email' => 'required|email|unique:users,email',
            'password' => 'required|min:6'
        ]);

        if (!$validation->passes()) {
            return Response::json(['errors' => $validation->errors()], 400);
        }

        // Hash della password
        $data['password'] = password_hash($data['password'], PASSWORD_DEFAULT);

        // Creazione dell'utente
        User::table('users')->insert($data);

        return Response::json(['message' => 'User registered successfully']);
    }

    public function showLogin()
    {
        return view('login');
    }

    public function login()
    {
        $data = Request::all();
        $user = User::table('users')->where('email', $data['email'])->first();

        if (!$user || !password_verify($data['password'], $user['password'])) {
            return Response::json(['error' => 'Invalid credentials'], 401);
        }

        // Impostazione della sessione
        Auth::login($user['id']);

        return Response::json(['message' => 'Login successful']);
    }

    public function logout()
    {
        Auth::logout();
        return Response::json(['message' => 'Logged out successfully']);
    }
}
```

### Rotte per la Gestione degli Utenti

Configura le rotte nel file di ingresso (`public/index.php`):

```php
require '../vendor/autoload.php';

use Leaf\App;
use App\Controllers\AuthController;
use Leaf\Auth;

$app = new App();

require '../config/database.php';

// Configurazione di Leaf Auth
Auth::init();

$app->get('/register', [AuthController::class, 'showRegister']);
$app->post('/register', [AuthController::class, 'register']);
$app->get('/login', [AuthController::class, 'showLogin']);
$app->post('/login', [AuthController::class, 'login']);
$app->get('/logout', [AuthController::class, 'logout']);

// Esempio di rotta protetta
$app->get('/profile', function() {
    if (!Auth::check()) {
        return Response::json(['error' => 'Unauthorized'], 401);
    }

    $user = Auth::user();
    return view('profile', ['user' => $user]);
});

$app->run();
```

### Viste per la Registrazione e il Login

Crea le viste per la registrazione e il login (`views/register.php` e `views/login.php`):

**register.php:**

```php
<!DOCTYPE html>
<html>
<head>
    <title>Register</title>
</head>
<body>
    <h1>Register</h1>
    <form action="/register" method="POST">
        <label for="email">Email:</label>
        <input type="email" name="email" required><br>
        <label for="password">Password:</label>
        <input type="password" name="password" required><br>
        <button type="submit">Register</button>
    </form>
</body>
</html>
```

**login.php:**

```php
<!DOCTYPE html>
<html>
<head>
    <title>Login</title>
</head>
<body>
    <h1>Login</h1>
    <form action="/login" method="POST">
        <label for="email">Email:</label>
        <input type="email" name="email" required><br>
        <label for="password">Password:</label>
        <input type="password" name="password" required><br>
        <button type="submit">Login</button>
    </form>
</body>
</html>
```

**profile.php:**

```php
<!DOCTYPE html>
<html>
<head>
    <title>Profile</title>
</head>
<body>
    <h1>Profile</h1>
    <p>Welcome, <?php echo $user['email']; ?>!</p>
    <a href="/logout">Logout</a>
</body>
</html>
```

Leaf Auth fornisce un modo semplice ed efficiente per gestire l'autenticazione degli utenti nelle applicazioni Leaf PHP. Questo tutorial ti ha guidato attraverso l'installazione, configurazione e utilizzo di Leaf Auth per creare un sistema di autenticazione completo. Ora hai una base solida per estendere ulteriormente la funzionalità di gestione degli utenti nella tua applicazione, come la gestione dei ruoli e dei permessi, il reset delle password e molto altro.

### Creazione di un'API RESTful con Leaf PHP

Leaf PHP è un framework leggero e flessibile che permette di costruire applicazioni web e API in modo rapido ed efficiente. In questo tutorial, creeremo un'API RESTful completa utilizzando Leaf PHP, che include operazioni CRUD (Create, Read, Update, Delete) per un modello "Book".

### Struttura del Progetto

Ecco una struttura di directory suggerita per il nostro progetto:

```
/project-root
  /app
    /controllers
      BookController.php
    /models
      Book.php
  /config
    database.php
  /public
    index.php
  /vendor
  .env
  composer.json
```

### Installazione

Assicurati di avere Composer installato e poi installa Leaf e Leaf DB:

```bash
composer require leafs/leaf leafs/db leafs/validate
```

### Configurazione del Database

Crea un file `.env` nella root del progetto per configurare le variabili di ambiente:

```env
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=mydatabase
DB_USERNAME=myusername
DB_PASSWORD=mypassword
```

Carica le variabili di ambiente e configura il database in `config/database.php`:

```php
<?php

Leaf\Config::loadEnv();

Leaf\Db::connect([
    'driver' => getenv('DB_CONNECTION'),
    'host' => getenv('DB_HOST'),
    'port' => getenv('DB_PORT'),
    'database' => getenv('DB_DATABASE'),
    'username' => getenv('DB_USERNAME'),
    'password' => getenv('DB_PASSWORD'),
    'charset' => 'utf8mb4',
    'collation' => 'utf8mb4_unicode_ci',
    'prefix' => '',
]);
```

### Creazione della Tabella Books

Esegui il seguente script SQL per creare la tabella `books`:

```sql
CREATE TABLE `books` (
  `id` INT AUTO_INCREMENT PRIMARY KEY,
  `title` VARCHAR(255) NOT NULL,
  `author` VARCHAR(255) NOT NULL,
  `published_date` DATE NOT NULL,
  `isbn` VARCHAR(20) NOT NULL UNIQUE,
  `created_at` TIMESTAMP DEFAULT CURRENT_TIMESTAMP,
  `updated_at` TIMESTAMP DEFAULT CURRENT_TIMESTAMP ON UPDATE CURRENT_TIMESTAMP
);
```

### Modello Book

Crea un modello per rappresentare i libri (`app/models/Book.php`):

```php
<?php

namespace App\Models;

use Leaf\Db;

class Book extends Db
{
    protected $table = 'books';

    public static function createBook($data)
    {
        return self::table('books')->insert($data);
    }

    public static function getAllBooks()
    {
        return self::table('books')->get();
    }

    public static function getBookById($id)
    {
        return self::table('books')->where('id', $id)->first();
    }

    public static function updateBook($id, $data)
    {
        return self::table('books')->where('id', $id)->update($data);
    }

    public static function deleteBook($id)
    {
        return self::table('books')->where('id', $id)->delete();
    }
}
```

### Controller Book

Crea un controller per gestire le operazioni CRUD (`app/controllers/BookController.php`):

```php
<?php

namespace App\Controllers;

use Leaf\Http\Request;
use Leaf\Http\Response;
use App\Models\Book;

class BookController
{
    public function index()
    {
        $books = Book::getAllBooks();
        return Response::json($books);
    }

    public function show($id)
    {
        $book = Book::getBookById($id);
        if (!$book) {
            return Response::json(['error' => 'Book not found'], 404);
        }
        return Response::json($book);
    }

    public function store()
    {
        $data = Request::all();

        // Validazione dei dati
        $validation = \Leaf\Validate::make($data, [
            'title' => 'required',
            'author' => 'required',
            'published_date' => 'required|date',
            'isbn' => 'required|unique:books,isbn'
        ]);

        if (!$validation->passes()) {
            return Response::json(['errors' => $validation->errors()], 400);
        }

        // Creazione del libro
        $book = Book::createBook($data);
        return Response::json($book, 201);
    }

    public function update($id)
    {
        $data = Request::all();

        // Validazione dei dati
        $validation = \Leaf\Validate::make($data, [
            'title' => 'required',
            'author' => 'required',
            'published_date' => 'required|date',
            'isbn' => 'required|unique:books,isbn,' . $id
        ]);

        if (!$validation->passes()) {
            return Response::json(['errors' => $validation->errors()], 400);
        }

        // Aggiornamento del libro
        $book = Book::updateBook($id, $data);
        return Response::json($book);
    }

    public function destroy($id)
    {
        $deleted = Book::deleteBook($id);
        if ($deleted) {
            return Response::json(['message' => 'Book deleted successfully']);
        } else {
            return Response::json(['error' => 'Book not found'], 404);
        }
    }
}
```

### Rotte per l'API

Configura le rotte nel file di ingresso (`public/index.php`):

```php
require '../vendor/autoload.php';

use Leaf\App;
use App\Controllers\BookController;

$app = new App();

require '../config/database.php';

// Rotte per l'API dei libri
$app->get('/books', [BookController::class, 'index']);
$app->get('/books/{id}', [BookController::class, 'show']);
$app->post('/books', [BookController::class, 'store']);
$app->put('/books/{id}', [BookController::class, 'update']);
$app->delete('/books/{id}', [BookController::class, 'destroy']);

$app->run();
```

### Test dell'API

Ora che l'API è configurata, puoi testarla utilizzando strumenti come Postman o cURL.

**Esempio di richiesta POST per creare un libro:**

```bash
curl -X POST http://localhost/books \
  -H "Content-Type: application/json" \
  -d '{
    "title": "Leaf PHP for Beginners",
    "author": "John Doe",
    "published_date": "2024-01-01",
    "isbn": "1234567890123"
  }'
```

**Esempio di richiesta GET per ottenere tutti i libri:**

```bash
curl http://localhost/books
```

**Esempio di richiesta GET per ottenere un libro specifico:**

```bash
curl http://localhost/books/1
```

**Esempio di richiesta PUT per aggiornare un libro:**

```bash
curl -X PUT http://localhost/books/1 \
  -H "Content-Type: application/json" \
  -d '{
    "title": "Updated Title",
    "author": "Jane Doe",
    "published_date": "2024-02-01",
    "isbn": "9876543210987"
  }'
```

**Esempio di richiesta DELETE per eliminare un libro:**

```bash
curl -X DELETE http://localhost/books/1
```


In questo tutorial, abbiamo creato un'API RESTful completa utilizzando Leaf PHP. Abbiamo configurato il database, creato un modello, un controller e definito le rotte per gestire le operazioni CRUD per un modello "Book". Leaf PHP e Leaf DB rendono la creazione di API rapida ed efficiente, consentendo di concentrarsi sulla logica dell'applicazione piuttosto che sui dettagli infrastrutturali.

### Best Practices per Sviluppare API RESTful

Sviluppare un'API RESTful richiede attenzione non solo alla funzionalità ma anche a come questa funzionalità viene esposta e utilizzata. Di seguito sono riportate alcune best practices per creare API RESTful robuste, scalabili e sicure.

#### 1. **Utilizza Verb HTTP correttamente**
   - **GET:** Recupera risorse.
   - **POST:** Crea nuove risorse.
   - **PUT:** Aggiorna risorse esistenti.
   - **DELETE:** Elimina risorse.
   - **PATCH:** Aggiorna parzialmente risorse.

#### 2. **Design dell'Endpoint**
   - Utilizza nomi di endpoint descrittivi e plurali per le risorse.
   - Evita verbi negli endpoint (es: `/users` invece di `/getUsers`).

```plaintext
GET    /books
POST   /books
GET    /books/{id}
PUT    /books/{id}
DELETE /books/{id}
```

#### 3. **Gestione degli Stati HTTP**
   - **200 OK:** Richiesta riuscita.
   - **201 Created:** Risorsa creata.
   - **204 No Content:** Richiesta riuscita, nessun contenuto da restituire.
   - **400 Bad Request:** Richiesta non valida.
   - **401 Unauthorized:** Autenticazione richiesta.
   - **403 Forbidden:** Accesso negato.
   - **404 Not Found:** Risorsa non trovata.
   - **500 Internal Server Error:** Errore lato server.

#### 4. **Versioning dell'API**
   - Includi la versione dell'API nell'URL o nei header.
   - Es: `/v1/books` o `Accept: application/vnd.yourapi.v1+json`.

```plaintext
GET /v1/books
```

#### 5. **Gestione degli Errori**
   - Fornisci messaggi di errore chiari e strutturati.
   - Usa un formato consistente, ad esempio JSON.

```json
{
  "error": {
    "code": 400,
    "message": "Invalid request",
    "details": {
      "field": "title",
      "issue": "Title is required"
    }
  }
}
```

#### 6. **Paginazione, Ordinamento e Filtraggio**
   - Fornisci opzioni di paginazione per liste di risorse lunghe.
   - Consenti ordinamento e filtraggio tramite query string.

```plaintext
GET /books?page=2&limit=10
GET /books?sort=published_date
GET /books?author=John%20Doe
```

#### 7. **Documentazione Completa**
   - Utilizza strumenti come Swagger/OpenAPI per documentare l'API.
   - Fornisci esempi di richieste e risposte.

#### 8. **Autenticazione e Autorizzazione**
   - Utilizza HTTPS per tutte le comunicazioni.
   - Implementa un meccanismo di autenticazione sicuro come OAuth2.
   - Proteggi endpoint sensibili con autorizzazioni adeguate.

#### 9. **Rate Limiting**
   - Implementa limitazioni di velocità per prevenire abusi.
   - Fornisci header che indicano i limiti e lo stato di utilizzo.

```plaintext
X-RateLimit-Limit: 1000
X-RateLimit-Remaining: 500
X-RateLimit-Reset: 1377013266
```

#### 10. **Utilizzo di HTTP Cache**
   - Utilizza header HTTP come `ETag`, `Last-Modified`, `Cache-Control` per ottimizzare la cache e migliorare le prestazioni.

#### 11. **Supporto per Content Negotiation**
   - Consenti ai client di specificare il formato di risposta tramite header `Accept`.

```plaintext
Accept: application/json
Accept: application/xml
```

#### 12. **Sicurezza delle API**
   - Valida e filtra tutti i dati in ingresso.
   - Proteggi contro le vulnerabilità comuni (es: SQL injection, XSS).
   - Limita i dati esposti in output.

### Implementazione di Best Practices in Leaf PHP

Ecco un esempio di come alcune di queste best practices possono essere implementate in un'API Leaf PHP:

```php
require '../vendor/autoload.php';

use Leaf\App;
use Leaf\Http\Request;
use Leaf\Http\Response;

$app = new App();

require '../config/database.php';

// Versioning
$app->group('/v1', function() use ($app) {
    // Endpoint: GET /v1/books
    $app->get('/books', 'BookController@index');
    
    // Endpoint: GET /v1/books/{id}
    $app->get('/books/{id}', 'BookController@show');
    
    // Endpoint: POST /v1/books
    $app->post('/books', 'BookController@store');
    
    // Endpoint: PUT /v1/books/{id}
    $app->put('/books/{id}', 'BookController@update');
    
    // Endpoint: DELETE /v1/books/{id}
    $app->delete('/books/{id}', 'BookController@destroy');
});

// Error handling middleware
$app->set404(function() {
    Response::json(['error' => 'Endpoint not found'], 404);
});

$app->setErrorHandler(function($error) {
    Response::json(['error' => $error->getMessage()], 500);
});

$app->run();
```

Seguire le best practices per la creazione di API RESTful non solo rende la tua API più robusta e sicura, ma migliora anche l'esperienza degli sviluppatori che la utilizzano. Leaf PHP offre gli strumenti necessari per implementare queste pratiche in modo efficace, consentendoti di costruire API ben progettate e facilmente mantenibili.

### Testing delle Rotte e delle Funzioni in Leaf PHP con PHPUnit

Il testing è una parte cruciale dello sviluppo di qualsiasi applicazione, inclusa la creazione di API RESTful. PHPUnit è uno dei framework di testing più utilizzati in PHP. In questo tutorial, vedremo come testare le rotte e le funzioni di un'applicazione Leaf PHP utilizzando PHPUnit.

### Prerequisiti

1. Assicurati di avere Composer installato.
2. Aggiungi PHPUnit come dipendenza al tuo progetto:

```bash
composer require --dev phpunit/phpunit
```

### Configurazione di PHPUnit

Crea un file `phpunit.xml` nella root del tuo progetto per configurare PHPUnit:

```xml
<?xml version="1.0" encoding="UTF-8"?>
<phpunit bootstrap="tests/bootstrap.php" colors="true">
    <testsuites>
        <testsuite name="Leaf App Test Suite">
            <directory>tests</directory>
        </testsuite>
    </testsuites>
</phpunit>
```

### Configurazione Bootstrap

Crea un file `bootstrap.php` nella directory `tests` per configurare l'ambiente di test:

```php
<?php

require __DIR__ . '/../vendor/autoload.php';

// Carica le variabili di ambiente
Leaf\Config::loadEnv();

// Configura il database per i test
Leaf\Db::connect([
    'driver' => getenv('DB_CONNECTION'),
    'host' => getenv('DB_HOST'),
    'port' => getenv('DB_PORT'),
    'database' => getenv('DB_DATABASE'),
    'username' => getenv('DB_USERNAME'),
    'password' => getenv('DB_PASSWORD'),
    'charset' => 'utf8mb4',
    'collation' => 'utf8mb4_unicode_ci',
    'prefix' => '',
]);

// Configura l'applicazione Leaf
$app = new Leaf\App();
require __DIR__ . '/../config/database.php';
require __DIR__ . '/../public/index.php';

return $app;
```

### Creazione dei Test

Crea una directory `tests` nella root del tuo progetto. In questa directory, creeremo i test per la nostra applicazione Leaf PHP.

#### Test delle Rotte

Crea un file `BookControllerTest.php` nella directory `tests`:

```php
<?php

use PHPUnit\Framework\TestCase;
use Leaf\Http\Request;
use Leaf\Http\Response;
use Leaf\App;

class BookControllerTest extends TestCase
{
    protected $app;

    protected function setUp(): void
    {
        $this->app = require __DIR__ . '/../tests/bootstrap.php';
    }

    public function testGetAllBooks()
    {
        $response = $this->app->get('/v1/books');
        $this->assertEquals(200, $response->status());
        $this->assertIsArray($response->body());
    }

    public function testCreateBook()
    {
        $bookData = [
            'title' => 'Test Book',
            'author' => 'John Doe',
            'published_date' => '2024-01-01',
            'isbn' => '1234567890123'
        ];

        $response = $this->app->post('/v1/books', $bookData);
        $this->assertEquals(201, $response->status());
        $this->assertArrayHasKey('id', $response->body());
    }

    public function testGetSingleBook()
    {
        $response = $this->app->get('/v1/books/1');
        $this->assertEquals(200, $response->status());
        $this->assertArrayHasKey('id', $response->body());
    }

    public function testUpdateBook()
    {
        $bookData = [
            'title' => 'Updated Test Book',
            'author' => 'Jane Doe',
            'published_date' => '2024-02-01',
            'isbn' => '9876543210987'
        ];

        $response = $this->app->put('/v1/books/1', $bookData);
        $this->assertEquals(200, $response->status());
        $this->assertEquals('Updated Test Book', $response->body()['title']);
    }

    public function testDeleteBook()
    {
        $response = $this->app->delete('/v1/books/1');
        $this->assertEquals(200, $response->status());
        $this->assertEquals(['message' => 'Book deleted successfully'], $response->body());
    }
}
```

### Esecuzione dei Test

Esegui i test utilizzando il comando PHPUnit:

```bash
vendor/bin/phpunit
```

### Test delle Funzioni

Per testare funzioni specifiche, come i metodi del modello `Book`, crea un file `BookModelTest.php` nella directory `tests`:

```php
<?php

use PHPUnit\Framework\TestCase;
use App\Models\Book;

class BookModelTest extends TestCase
{
    protected function setUp(): void
    {
        $this->app = require __DIR__ . '/../tests/bootstrap.php';
    }

    public function testCreateBook()
    {
        $bookData = [
            'title' => 'Test Book',
            'author' => 'John Doe',
            'published_date' => '2024-01-01',
            'isbn' => '1234567890123'
        ];

        $book = Book::createBook($bookData);
        $this->assertArrayHasKey('id', $book);
    }

    public function testGetAllBooks()
    {
        $books = Book::getAllBooks();
        $this->assertIsArray($books);
    }

    public function testGetBookById()
    {
        $book = Book::getBookById(1);
        $this->assertEquals(1, $book['id']);
    }

    public function testUpdateBook()
    {
        $bookData = [
            'title' => 'Updated Test Book',
            'author' => 'Jane Doe',
            'published_date' => '2024-02-01',
            'isbn' => '9876543210987'
        ];

        $book = Book::updateBook(1, $bookData);
        $this->assertEquals('Updated Test Book', $book['title']);
    }

    public function testDeleteBook()
    {
        $deleted = Book::deleteBook(1);
        $this->assertTrue($deleted);
    }
}
```

Testing è una parte essenziale dello sviluppo di API per garantire che le funzionalità siano corrette e stabili. PHPUnit, combinato con Leaf PHP, offre un ambiente di test potente e flessibile che ti consente di testare facilmente le tue rotte e funzioni. Seguendo questo tutorial, puoi impostare una suite di test completa per la tua applicazione Leaf PHP, assicurandoti che ogni parte del tuo codice funzioni come previsto.

### Test-Driven Development (TDD) con Leaf PHP

Test-Driven Development (TDD) è una pratica di sviluppo software che consiste nel scrivere i test prima del codice effettivo. L'idea è di creare test che definiscano e verificano il comportamento desiderato delle funzionalità prima ancora che queste vengano implementate. In questo modo, il codice viene scritto per soddisfare i test, garantendo un'alta copertura e un design orientato ai test.

Ecco una guida dettagliata su come utilizzare TDD con Leaf PHP.

### Passi per il TDD

1. **Scrivere un test che fallisce**: Scrivi un test per una funzionalità che non è ancora implementata.
2. **Implementare la funzionalità**: Scrivi il codice minimo necessario per far passare il test.
3. **Refactor**: Migliora il codice mantenendo i test verdi.

### Prerequisiti

- Assicurati di avere Composer installato.
- Installa PHPUnit:

```bash
composer require --dev phpunit/phpunit
```

### Configurazione di PHPUnit

Crea un file `phpunit.xml` nella root del tuo progetto:

```xml
<?xml version="1.0" encoding="UTF-8"?>
<phpunit bootstrap="tests/bootstrap.php" colors="true">
    <testsuites>
        <testsuite name="Leaf App Test Suite">
            <directory>tests</directory>
        </testsuite>
    </testsuites>
</phpunit>
```

### Configurazione Bootstrap

Crea un file `bootstrap.php` nella directory `tests`:

```php
<?php

require __DIR__ . '/../vendor/autoload.php';

// Configura l'applicazione Leaf
$app = new Leaf\App();
require __DIR__ . '/../config/database.php';
require __DIR__ . '/../public/index.php';

return $app;
```

### Esempio di Implementazione TDD

Supponiamo di voler implementare un endpoint per creare un libro (`POST /books`).

#### Passo 1: Scrivere un Test che Fallisce

Crea un file `BookControllerTest.php` nella directory `tests`:

```php
<?php

use PHPUnit\Framework\TestCase;
use Leaf\Http\Request;
use Leaf\Http\Response;
use Leaf\App;

class BookControllerTest extends TestCase
{
    protected $app;

    protected function setUp(): void
    {
        $this->app = require __DIR__ . '/../tests/bootstrap.php';
    }

    public function testCreateBook()
    {
        $bookData = [
            'title' => 'Test Book',
            'author' => 'John Doe',
            'published_date' => '2024-01-01',
            'isbn' => '1234567890123'
        ];

        $response = $this->app->post('/books', $bookData);
        $this->assertEquals(201, $response->status());
        $this->assertArrayHasKey('id', $response->body());
    }
}
```

Esegui il test utilizzando PHPUnit:

```bash
vendor/bin/phpunit --filter testCreateBook
```

Il test fallirà perché non abbiamo ancora implementato l'endpoint.

#### Passo 2: Implementare la Funzionalità

Implementa l'endpoint nel controller dei libri. Crea un file `BookController.php`:

```php
<?php

namespace App\Controllers;

use Leaf\Http\Request;
use Leaf\Http\Response;
use App\Models\Book;

class BookController
{
    public function store()
    {
        $data = Request::get(['title', 'author', 'published_date', 'isbn']);
        
        // Supponiamo che il modello Book gestisca la creazione del libro
        $book = Book::create($data);
        
        Response::json($book, 201);
    }
}
```

Aggiorna il file delle rotte (`routes.php`):

```php
$app->post('/books', 'App\Controllers\BookController@store');
```

Esegui nuovamente il test:

```bash
vendor/bin/phpunit --filter testCreateBook
```

Il test dovrebbe passare ora.

#### Passo 3: Refactor

Ottimizza il codice mantenendo i test verdi. Ad esempio, puoi migliorare la gestione degli errori o la struttura dei dati.

### Implementazione dei Modelli e Test delle Funzioni

Crea il modello `Book.php` nella directory `models`:

```php
<?php

namespace App\Models;

use Leaf\Model;

class Book extends Model
{
    protected $table = 'books';

    public static function create($data)
    {
        // Inserisce il libro nel database
        $id = self::insert($data);
        return self::find($id);
    }
}
```

Aggiungi un test per il modello:

```php
<?php

use PHPUnit\Framework\TestCase;
use App\Models\Book;

class BookModelTest extends TestCase
{
    protected function setUp(): void
    {
        $this->app = require __DIR__ . '/../tests/bootstrap.php';
    }

    public function testCreateBook()
    {
        $bookData = [
            'title' => 'Test Book',
            'author' => 'John Doe',
            'published_date' => '2024-01-01',
            'isbn' => '1234567890123'
        ];

        $book = Book::create($bookData);
        $this->assertArrayHasKey('id', $book);
    }
}
```

Esegui i test:

```bash
vendor/bin/phpunit
```

Il TDD è una metodologia potente che può migliorare la qualità del tuo codice e la sua manutenibilità. Utilizzando PHPUnit e Leaf PHP, puoi implementare facilmente TDD nel tuo flusso di lavoro, assicurandoti che ogni parte del tuo codice sia coperta dai test e funzioni come previsto.

### Cos'è PSR-4?

PSR-4 è uno standard di autoloading definito dal PHP-FIG (PHP Framework Interoperability Group). È uno dei diversi standard PSR (PHP Standard Recommendation) creati per migliorare l'interoperabilità tra le librerie e i framework PHP. PSR-4 specifica come le classi dovrebbero essere autocaricate (autoloaded) utilizzando un mapping tra i namespace e le strutture delle directory.

### Scopo di PSR-4

L'obiettivo principale di PSR-4 è quello di fornire un metodo standard per autocaricare le classi in PHP, senza dover includere manualmente ogni file PHP che contiene una classe.

### Come Funziona PSR-4

PSR-4 definisce un mapping tra un namespace e una directory. Quando una classe viene richiesta, l'autoloader di PSR-4 cerca di risolvere il percorso del file in base al namespace della classe.

#### Struttura di Base

1. **Namespace Root**: La radice del namespace viene mappata a una directory specifica.
2. **Namespace Subdirectories**: Ogni sottospazio dei nomi (subnamespace) viene mappato a una sottodirectory.
3. **Class Name**: Il nome della classe viene mappato a un file con lo stesso nome.

#### Esempio di Mapping

Supponiamo di avere la seguente struttura di directory e namespace:

```
src/
├── Controllers/
│   └── HomeController.php
├── Models/
│   └── User.php
```

Con le seguenti classi:

```php
// src/Controllers/HomeController.php
namespace App\Controllers;

class HomeController {
    // ...
}

// src/Models/User.php
namespace App\Models;

class User {
    // ...
}
```

### Configurazione di PSR-4 in Composer

Per configurare l'autoloading PSR-4 con Composer, devi aggiornare il tuo file `composer.json` come segue:

```json
{
    "autoload": {
        "psr-4": {
            "App\\": "src/"
        }
    }
}
```

Dopo aver aggiornato `composer.json`, esegui il comando:

```bash
composer dump-autoload
```

Questo comando aggiorna i file di autoloading di Composer, permettendo a PHP di caricare automaticamente le classi utilizzando lo standard PSR-4.

### Esempio di Utilizzo

Con la configurazione di cui sopra, puoi usare le tue classi in modo semplice senza doverle includere manualmente:

```php
// In un file qualsiasi, ad esempio index.php
require 'vendor/autoload.php';

use App\Controllers\HomeController;
use App\Models\User;

$controller = new HomeController();
$user = new User();
```

### Vantaggi di PSR-4

1. **Standardizzazione**: Fornisce un modo standard per autocaricare le classi, migliorando l'interoperabilità tra librerie e framework diversi.
2. **Organizzazione**: Incoraggia una struttura organizzata delle directory basata sui namespace.
3. **Efficienza**: Riduce la necessità di includere manualmente i file, migliorando l'efficienza dello sviluppo.
4. **Manutenibilità**: Facilita la gestione e la manutenzione del codice, rendendo più semplice navigare e comprendere la struttura del progetto.

PSR-4 è uno standard essenziale per l'autoloading delle classi in PHP, che semplifica notevolmente lo sviluppo e la gestione dei progetti PHP. Adottando PSR-4, gli sviluppatori possono beneficiare di un metodo coerente e standardizzato per organizzare e caricare automaticamente le loro classi, migliorando l'interoperabilità e la manutenibilità del codice.

Il file `composer.json` è un file di configurazione utilizzato dal gestore di pacchetti Composer per PHP. Serve per definire le dipendenze del tuo progetto e altre informazioni di configurazione. Ecco alcune delle sue funzioni principali:

### Funzioni di `composer.json`

1. **Gestione delle Dipendenze**: Specifica le librerie e i pacchetti di cui il tuo progetto ha bisogno. Composer scarica e installa automaticamente queste dipendenze e le loro dipendenze ricorsive.

2. **Autoloading**: Configura l'autoloading per caricare automaticamente le classi del tuo progetto senza doverle richiamare manualmente.

3. **Metadati del Progetto**: Contiene informazioni sul progetto come il nome, la descrizione, la versione, l'autore, la licenza e altri metadati utili.

4. **Script**: Definisce script che possono essere eseguiti con comandi specifici di Composer, come l'installazione delle dipendenze, la pulizia della cache, ecc.

5. **Configurazione**: Imposta parametri di configurazione per Composer, come repository personalizzati, configurazioni di autoload, e altro.

### Esempio di `composer.json`

Ecco un esempio di file `composer.json` per un progetto PHP:

```json
{
    "name": "nome/progetto",
    "description": "Una breve descrizione del progetto",
    "type": "project",
    "require": {
        "php": "^7.4 || ^8.0",
        "leafs/leaf": "^3.0",
        "leafs/db": "^1.5"
    },
    "require-dev": {
        "phpunit/phpunit": "^9.5"
    },
    "autoload": {
        "psr-4": {
            "App\\": "src/"
        }
    },
    "autoload-dev": {
        "psr-4": {
            "Tests\\": "tests/"
        }
    },
    "scripts": {
        "post-install-cmd": [
            "@php artisan key:generate"
        ],
        "test": "phpunit"
    },
    "authors": [
        {
            "name": "Tuo Nome",
            "email": "tuo.email@example.com"
        }
    ],
    "license": "MIT"
}
```

### Dettagli delle Sezioni

- **name**: Nome del progetto, solitamente in formato `vendor/package`.
- **description**: Breve descrizione del progetto.
- **type**: Tipo di pacchetto. Può essere `library`, `project`, `metapackage`, ecc.
- **require**: Lista delle dipendenze necessarie per il progetto. Ogni voce contiene il nome del pacchetto e la versione richiesta.
- **require-dev**: Dipendenze necessarie solo per lo sviluppo, come strumenti di test.
- **autoload**: Configura l'autoloading per caricare automaticamente le classi. In questo esempio, si utilizza lo standard PSR-4.
- **autoload-dev**: Configura l'autoloading per le classi di sviluppo/test.
- **scripts**: Script che possono essere eseguiti con Composer. Ad esempio, `composer test` eseguirà PHPUnit.
- **authors**: Informazioni sugli autori del progetto.
- **license**: Licenza del progetto.

### Utilizzo di Composer

- **Installare le dipendenze**: Una volta configurato `composer.json`, puoi installare le dipendenze eseguendo:

  ```bash
  composer install
  ```

- **Aggiungere una dipendenza**: Per aggiungere una nuova dipendenza al progetto:

  ```bash
  composer require nome/pacchetto
  ```

- **Eseguire script**: Per eseguire uno script definito nel file `composer.json`:

  ```bash
  composer run-script nome_script
  ```

Il file `composer.json` è essenziale per la gestione delle dipendenze e l'automazione delle configurazioni nei progetti PHP, rendendo lo sviluppo più organizzato ed efficiente.


# Hello World

Per creare un progetto Leaf PHP da shell, segui questi passaggi:

### Prerequisiti

1. **PHP**: Assicurati di avere PHP installato sul tuo sistema.
2. **Composer**: Assicurati di avere Composer installato. Puoi installarlo seguendo le istruzioni sul sito ufficiale di [Composer](https://getcomposer.org/).

### Passaggi per Creare un Progetto Leaf PHP

1. **Apri il Terminale**: Apri il terminale o il prompt dei comandi.

2. **Crea una Cartella per il Progetto**: Spostati nella directory dove vuoi creare il progetto e crea una nuova cartella per il tuo progetto.

   ```bash
   mkdir my-leaf-project
   cd my-leaf-project
   ```

3. **Inizializza un Nuovo Progetto Composer**: Esegui il comando seguente per inizializzare un nuovo progetto Composer.

   ```bash
   composer init
   ```

   Questo comando ti guiderà attraverso una serie di prompt per configurare il tuo file `composer.json`. Puoi accettare i valori predefiniti o specificare le tue preferenze.

4. **Aggiungi Leaf PHP come Dipendenza**: Una volta completata l'inizializzazione, aggiungi Leaf PHP come dipendenza del tuo progetto.

   ```bash
   composer require leafs/leaf
   ```

5. **Crea la Struttura delle Directory**: Crea la struttura delle directory del tuo progetto.

   ```bash
   mkdir -p public src
   touch public/index.php
   ```

6. **Configura l'Autoloading**: Aggiorna il file `composer.json` per configurare l'autoloading PSR-4.

   ```json
   {
       "autoload": {
           "psr-4": {
               "App\\": "src/"
           }
       }
   }
   ```

   Dopo aver aggiornato `composer.json`, esegui:

   ```bash
   composer dump-autoload
   ```

7. **Crea un File di Ingresso (index.php)**: Apri `public/index.php` e aggiungi il seguente codice per iniziare a configurare la tua applicazione Leaf PHP.

   ```php
   <?php

   require __DIR__ . '/../vendor/autoload.php';

   use Leaf\App;

   $app = new App();

   $app->get('/', function() {
       echo "Hello, Leaf!";
   });

   $app->run();
   ```

8. **Esegui il Server**: Esegui il server integrato di PHP per vedere la tua applicazione in azione.

   ```bash
   php -S localhost:8000 -t public
   ```

### Dettagli del Codice

- **Autoloading**: La configurazione `psr-4` nel file `composer.json` permette a Composer di autocaricare le classi presenti nella directory `src` usando il namespace `App`.

- **File di Ingresso (index.php)**: Questo file serve come punto di ingresso per la tua applicazione Leaf PHP. Include l'autoloader di Composer, crea un'istanza dell'applicazione Leaf, definisce una rotta e avvia l'applicazione.

### Struttura Finale del Progetto

La struttura del progetto dovrebbe apparire simile a questa:

```
my-leaf-project/
├── public/
│   └── index.php
├── src/
├── vendor/
├── composer.json
└── composer.lock
```

### Test dell'Applicazione

Apri il browser e vai su `http://localhost:8000`. Dovresti vedere il messaggio "Hello, Leaf!".

### Conclusione

Hai creato con successo un progetto Leaf PHP utilizzando la shell. Ora puoi iniziare a sviluppare la tua applicazione aggiungendo rotte, controller, modelli e altre funzionalità necessarie.

### Creare un Servizio di Accorciamento degli URL con Leaf PHP e SQLite3

In questo tutorial, creeremo un semplice servizio di accorciamento degli URL utilizzando Leaf PHP e un database SQLite3. Il servizio permetterà agli utenti di inserire un URL lungo e ottenere un URL corto, che reindirizzerà all'URL originale.

### Prerequisiti

- PHP e Composer installati.
- SQLite3 installato.

### Struttura del Progetto

Ecco come struttureremo il progetto:

```
url-shortener/
├── config/
│   └── database.php
├── public/
│   └── index.php
├── src/
│   └── Controllers/
│       └── UrlController.php
│   └── Models/
│       └── Url.php
├── tests/
│   └── UrlShortenerTest.php
├── vendor/
├── .env
├── composer.json
└── phpunit.xml
```

### Passo 1: Impostare il Progetto

1. **Crea il progetto e inizializza Composer**

```bash
mkdir url-shortener
cd url-shortener
composer init
```

Aggiungi `leafs/leaf` come dipendenza:

```bash
composer require leafs/leaf
```

2. **Configura il database**

Crea un file `config/database.php`:

```php
<?php

use Leaf\Db;

Db::config('sqlite', [
    'database' => __DIR__ . '/../database.sqlite',
]);
```

3. **Imposta l'ambiente**

Crea un file `.env`:

```env
DB_CONNECTION=sqlite
DB_DATABASE=database.sqlite
```

4. **Configura l'autoloading**

Aggiorna `composer.json`:

```json
"autoload": {
    "psr-4": {
        "App\\": "src/"
    }
}
```

Esegui:

```bash
composer dump-autoload
```

### Passo 2: Creare il Database

Crea il file `database.sqlite` nella root del progetto e una tabella `urls`:

```sql
CREATE TABLE urls (
    id INTEGER PRIMARY KEY AUTOINCREMENT,
    long_url TEXT NOT NULL,
    short_code TEXT NOT NULL UNIQUE,
    created_at TIMESTAMP DEFAULT CURRENT_TIMESTAMP
);
```

### Passo 3: Creare i Modelli

Crea un file `src/Models/Url.php`:

```php
<?php

namespace App\Models;

use Leaf\Model;

class Url extends Model
{
    protected $table = 'urls';

    public static function createShortUrl($longUrl)
    {
        $shortCode = self::generateShortCode();
        self::insert([
            'long_url' => $longUrl,
            'short_code' => $shortCode,
        ]);

        return $shortCode;
    }

    public static function getLongUrl($shortCode)
    {
        $result = self::where('short_code', $shortCode)->first();
        return $result ? $result['long_url'] : null;
    }

    private static function generateShortCode($length = 6)
    {
        $characters = '0123456789abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ';
        $charactersLength = strlen($characters);
        $shortCode = '';
        for ($i = 0; $i < $length; $i++) {
            $shortCode .= $characters[rand(0, $charactersLength - 1)];
        }
        return $shortCode;
    }
}
```

### Passo 4: Creare i Controller

Crea un file `src/Controllers/UrlController.php`:

```php
<?php

namespace App\Controllers;

use Leaf\Http\Request;
use Leaf\Http\Response;
use App\Models\Url;

class UrlController
{
    public function shorten()
    {
        $longUrl = Request::get('url');
        if (!$longUrl) {
            Response::json(['error' => 'URL is required'], 400);
            return;
        }

        $shortCode = Url::createShortUrl($longUrl);
        $shortUrl = Request::baseUrl() . '/' . $shortCode;

        Response::json(['short_url' => $shortUrl], 201);
    }

    public function redirect($shortCode)
    {
        $longUrl = Url::getLongUrl($shortCode);
        if ($longUrl) {
            Response::redirect($longUrl);
        } else {
            Response::json(['error' => 'URL not found'], 404);
        }
    }
}
```

### Passo 5: Configurare le Rotte

Crea un file `public/index.php`:

```php
<?php

require __DIR__ . '/../vendor/autoload.php';

use Leaf\App;
use Leaf\Http\Response;
use App\Controllers\UrlController;

$app = new App();
Leaf\Config::loadEnv(__DIR__ . '/../.env');
require __DIR__ . '/../config/database.php';

$app->post('/shorten', [UrlController::class, 'shorten']);
$app->get('/{shortCode}', [UrlController::class, 'redirect']);

$app->run();
```

### Passo 6: Esecuzione e Test dell'Applicazione

Esegui il server:

```bash
php -S localhost:8000 -t public
```

Ora puoi testare l'applicazione:

- Per accorciare un URL:

```bash
curl -X POST -d "url=https://www.example.com" http://localhost:8000/shorten
```

- Per essere reindirizzati utilizzando l'URL accorciato:

Apri nel browser l'URL corto fornito nella risposta precedente.

### Test con PHPUnit

Crea un file `phpunit.xml`:

```xml
<?xml version="1.0" encoding="UTF-8"?>
<phpunit bootstrap="tests/bootstrap.php" colors="true">
    <testsuites>
        <testsuite name="Leaf App Test Suite">
            <directory>tests</directory>
        </testsuite>
    </testsuites>
</phpunit>
```

Crea un file `tests/UrlShortenerTest.php`:

```php
<?php

use PHPUnit\Framework\TestCase;
use Leaf\App;

class UrlShortenerTest extends TestCase
{
    protected $app;

    protected function setUp(): void
    {
        $this->app = require __DIR__ . '/../tests/bootstrap.php';
    }

    public function testShortenUrl()
    {
        $response = $this->app->post('/shorten', ['url' => 'https://www.example.com']);
        $this->assertEquals(201, $response->status());
        $this->assertArrayHasKey('short_url', $response->body());
    }

    public function testRedirect()
    {
        $shortCode = 'abc123';
        $longUrl = 'https://www.example.com';
        
        $this->app->post('/shorten', ['url' => $longUrl]);
        
        $response = $this->app->get('/' . $shortCode);
        $this->assertEquals(200, $response->status());
    }
}
```

Abbiamo creato un semplice servizio di accorciamento degli URL utilizzando Leaf PHP e SQLite3. Abbiamo configurato il database, creato i modelli e i controller, e definito le rotte. Abbiamo inoltre configurato PHPUnit per testare il nostro servizio. Questo esempio può essere esteso ulteriormente aggiungendo autenticazione, limitazioni di utilizzo, e altre funzionalità avanzate.

L'algoritmo che ho scelto per creare URL corte è un metodo semplice e comune basato sulla generazione di un codice casuale. Questo approccio è facile da implementare e funziona bene per la maggior parte dei casi d'uso. Ecco una spiegazione dettagliata dell'algoritmo:

### Algoritmo per Creare URL Corte

1. **Generazione di un Codice Casuale**:
   - Utilizziamo un set di caratteri che include numeri, lettere maiuscole e minuscole.
   - Il codice casuale viene generato scegliendo casualmente caratteri dal set di caratteri.
   - La lunghezza del codice può essere configurata (in questo caso, è di 6 caratteri).

2. **Verifica dell'Unicità**:
   - Dopo aver generato un codice casuale, si verifica se esiste già nel database.
   - Se il codice esiste già, si genera un nuovo codice e si ripete il processo finché non si trova un codice unico.

3. **Salvataggio nel Database**:
   - Una volta generato un codice unico, si salva il codice insieme all'URL lungo nel database.

### Dettagli del Codice

Ecco il codice completo per il modello `Url` che implementa questo algoritmo:

```php
<?php

namespace App\Models;

use Leaf\Model;

class Url extends Model
{
    protected $table = 'urls';

    public static function createShortUrl($longUrl)
    {
        $shortCode = self::generateUniqueShortCode();
        self::insert([
            'long_url' => $longUrl,
            'short_code' => $shortCode,
        ]);

        return $shortCode;
    }

    public static function getLongUrl($shortCode)
    {
        $result = self::where('short_code', $shortCode)->first();
        return $result ? $result['long_url'] : null;
    }

    private static function generateUniqueShortCode($length = 6)
    {
        do {
            $shortCode = self::generateShortCode($length);
        } while (self::shortCodeExists($shortCode));
        
        return $shortCode;
    }

    private static function generateShortCode($length = 6)
    {
        $characters = '0123456789abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ';
        $charactersLength = strlen($characters);
        $shortCode = '';
        for ($i = 0; $i < $length; $i++) {
            $shortCode .= $characters[rand(0, $charactersLength - 1)];
        }
        return $shortCode;
    }

    private static function shortCodeExists($shortCode)
    {
        return self::where('short_code', $shortCode)->exists();
    }
}
```

### Passaggi dell'Algoritmo

1. **Metodo `createShortUrl`**:
   - Riceve l'URL lungo come parametro.
   - Genera un codice breve unico utilizzando il metodo `generateUniqueShortCode`.
   - Inserisce l'URL lungo e il codice breve nel database.
   - Ritorna il codice breve.

2. **Metodo `generateUniqueShortCode`**:
   - Utilizza un ciclo `do-while` per generare e verificare l'unicità del codice.
   - Chiama il metodo `generateShortCode` per creare un nuovo codice.
   - Verifica l'unicità del codice utilizzando il metodo `shortCodeExists`.
   - Ripete il processo finché non viene trovato un codice unico.

3. **Metodo `generateShortCode`**:
   - Definisce un set di caratteri (`0123456789abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ`).
   - Genera un codice di lunghezza specificata scegliendo casualmente caratteri dal set di caratteri.
   - Ritorna il codice generato.

4. **Metodo `shortCodeExists`**:
   - Controlla se il codice esiste già nel database utilizzando una query.
   - Ritorna `true` se il codice esiste, altrimenti `false`.

### Vantaggi dell'Algoritmo

- **Semplicità**: L'algoritmo è semplice da implementare e comprendere.
- **Efficienza**: Genera rapidamente codici unici, specialmente per piccole dimensioni di dataset.
- **Flessibilità**: La lunghezza del codice può essere facilmente modificata per adattarsi a diverse esigenze.

### Limiti dell'Algoritmo

- **Collisioni**: Sebbene l'algoritmo gestisca le collisioni rigenerando il codice, la probabilità di collisioni aumenta con un numero molto elevato di URL.
- **Sicurezza**: Il codice generato è casuale e non crittograficamente sicuro, quindi non dovrebbe essere utilizzato per applicazioni che richiedono sicurezza elevata.

Questo algoritmo è ideale per un servizio di accorciamento URL semplice e di uso generale.

Sì, è possibile utilizzare hash come MD5 o SHA-256 per generare codici brevi per gli URL. Tuttavia, questi hash producono stringhe molto lunghe, quindi è comune utilizzare solo una parte dell'hash per ottenere un codice breve. Questo approccio ha i suoi vantaggi, tra cui la riduzione delle probabilità di collisione rispetto a un semplice codice casuale.

### Algoritmo Utilizzando Hash

#### Passaggi dell'Algoritmo

1. **Generazione dell'Hash**:
   - Utilizziamo una funzione hash come MD5 o SHA-256 sull'URL lungo.
   - Prendiamo solo una porzione dell'hash (ad esempio, i primi 6-8 caratteri) per ottenere il codice breve.

2. **Verifica dell'Unicità**:
   - Controlliamo se il codice breve esiste già nel database.
   - Se esiste, aggiungiamo un contatore al URL lungo e rigeneriamo l'hash fino a trovare un codice unico.

3. **Salvataggio nel Database**:
   - Una volta generato un codice unico, salviamo il codice insieme all'URL lungo nel database.

### Dettagli del Codice

Ecco un esempio di come implementare questo algoritmo utilizzando MD5 in PHP:

```php
<?php

namespace App\Models;

use Leaf\Model;

class Url extends Model
{
    protected $table = 'urls';

    public static function createShortUrl($longUrl)
    {
        $shortCode = self::generateUniqueShortCode($longUrl);
        self::insert([
            'long_url' => $longUrl,
            'short_code' => $shortCode,
        ]);

        return $shortCode;
    }

    public static function getLongUrl($shortCode)
    {
        $result = self::where('short_code', $shortCode)->first();
        return $result ? $result['long_url'] : null;
    }

    private static function generateUniqueShortCode($longUrl)
    {
        $counter = 0;
        do {
            $shortCode = self::generateShortCode($longUrl, $counter);
            $counter++;
        } while (self::shortCodeExists($shortCode));

        return $shortCode;
    }

    private static function generateShortCode($longUrl, $counter)
    {
        // Usa l'URL lungo e un contatore per generare un hash unico
        $hash = md5($longUrl . $counter);
        // Prendi solo i primi 6 caratteri dell'hash
        return substr($hash, 0, 6);
    }

    private static function shortCodeExists($shortCode)
    {
        return self::where('short_code', $shortCode)->exists();
    }
}
```

### Passaggi dell'Algoritmo Dettagliati

1. **Metodo `createShortUrl`**:
   - Riceve l'URL lungo come parametro.
   - Genera un codice breve unico utilizzando il metodo `generateUniqueShortCode`.
   - Inserisce l'URL lungo e il codice breve nel database.
   - Ritorna il codice breve.

2. **Metodo `generateUniqueShortCode`**:
   - Utilizza un ciclo `do-while` per generare e verificare l'unicità del codice.
   - Chiama il metodo `generateShortCode` per creare un nuovo codice, aggiungendo un contatore al URL lungo.
   - Verifica l'unicità del codice utilizzando il metodo `shortCodeExists`.
   - Ripete il processo finché non viene trovato un codice unico.

3. **Metodo `generateShortCode`**:
   - Utilizza la funzione `md5` per generare un hash dell'URL lungo concatenato con un contatore.
   - Prende solo i primi 6 caratteri dell'hash per ottenere il codice breve.
   - Ritorna il codice generato.

4. **Metodo `shortCodeExists`**:
   - Controlla se il codice esiste già nel database utilizzando una query.
   - Ritorna `true` se il codice esiste, altrimenti `false`.

### Vantaggi dell'Utilizzo di Hash

- **Riduzione delle Collisioni**: Gli hash hanno una distribuzione uniforme, riducendo la probabilità di collisioni rispetto ai codici casuali.
- **Deterministico**: Lo stesso URL lungo con lo stesso contatore produrrà sempre lo stesso codice, il che può essere utile in alcuni scenari.

### Limiti dell'Utilizzo di Hash

- **Lunghezza del Codice**: Utilizzare solo una porzione dell'hash riduce l'unicità e potrebbe aumentare le collisioni se non si utilizza un contatore.
- **Performance**: Generare un hash per ogni URL può essere meno efficiente rispetto alla generazione di codici casuali, specialmente per grandi volumi di URL.

Utilizzare hash come MD5 o SHA-256 per creare URL corte è un approccio valido che può ridurre le collisioni rispetto ai codici casuali. Tuttavia, è importante gestire adeguatamente l'unicità e le performance, ad esempio utilizzando un contatore per gestire le collisioni.