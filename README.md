# Pezzhub

Le tue storie, tutte nello stesso posto.

Questo è il repository pubblico di **distribuzione e aggiornamento** di Pezzhub.
Qui vengono pubblicati gli installer e le note delle versioni. Il codice sorgente
dell'applicazione è mantenuto in un repository separato e non viene caricato qui.

## Scarica Pezzhub

Apri [l'ultima release](https://github.com/ceres077/pezzhub-releases/releases/latest)
e scarica `pezzhub-setup-X.Y.Z.exe` per Windows 64 bit.

Il setup include il player MPV e non preinstalla estensioni video: puoi scegliere
e configurare le tue fonti nelle impostazioni. Dalla versione Windows 1.0.21
include anche la prima versione di SoundHub.
Una versione portatile, quando disponibile, è indicata tra i file della release.

## Tre spazi, un solo posto

- **MangaHub:** catalogo manga, libreria personale, reader e ripresa della lettura.
- **CineHub:** film, serie TV e anime, progressi, calendario e player.
- **SoundHub (Windows):** ricerca YouTube Music, cataloghi per generi e atmosfere,
  album, libreria laterale, player persistente, preferiti, playlist e coda
  riordinabile, separati per profilo. Dalla 1.0.22 ha un layout ispirato a Spotify
  con colori Pezzhub e una sidebar che resta separata dal player.

Il collegamento Spotify di SoundHub è **sperimentale**, ma l’importazione è
stata verificata anche con un account reale. Dalla 1.0.25 è disponibile l’importatore dei brani
preferiti: dopo il login apri «Brani che ti piacciono» nella finestra Spotify,
quindi importa dalla pagina Sorgenti e preferenze. I preferiti esistenti non
vengono cancellati in caso di errore. L'audio viene risolto su YouTube Music.
L'accesso avviene nel sito ufficiale e la sessione
resta cifrata sul dispositivo, senza essere inviata al cloud. I dati musicali
sono per ora locali: la sincronizzazione cloud di SoundHub non è ancora attiva.
Questa prima versione non replica tutte le funzionalità di Meld e non ne
incorpora il codice. Le versioni Android e i loro aggiornamenti restano separati.
La versione 1.0.23 corregge le richieste dei blocchi audio e il rinnovo della
sessione con «Riprova», verificati nel player Electron Windows. YouTube può
comunque limitare o rendere indisponibili singoli contenuti.

Dalla 1.0.24 SoundHub ha un banner dedicato nella home Pezzhub. L'avvio di un
film o trailer ferma la musica e chiude il player musicale. La presenza Discord
supporta anche titolo, artista, copertina e tempo del brano: si attiva nelle
impostazioni del profilo, anche da SoundHub. Richiede Discord desktop aperto;
resta disattivata per l'ospite e non condivide collegamenti delle fonti.

Dalla 1.0.25 la home musicale legge il [catalogo pubblico Amazon Music](https://music.amazon.it/),
con categorie aggiornate, senza podcast. La ricerca propone anteprime e dà
priorità alle corrispondenze esatte; gli artisti hanno popolari, discografia e
una lista personale degli artisti seguiti. Il menu dei brani offre playlist,
preferiti, coda, esclusioni, timer, radio, album, artista e link pubblico.
Le informazioni non fornite dalla fonte non vengono inventate. La coda può
continuare con brani collegati all’artista corrente: quando manca una
corrispondenza coerente si ferma. Le Jam condivise sono previste in seguito.

Dalla 1.0.26 il player mantiene una sola voce Pezzhub nella barra applicazioni
di Windows. Nella scheda di un titolo già iniziato trovi «Continua a guardare»
accanto al pulsante principale, per riprendere episodio e minuto salvati.

Profili, preferenze e librerie sono personali. La sincronizzazione tramite
account Pezzhub è facoltativa; senza account puoi usare l'app in locale.
Il catalogo TMDB condiviso richiede l'accesso all'account Pezzhub: la relativa
chiave resta sul server, non nell'installer. In locale puoi usare le tue estensioni
oppure una chiave TMDB personale nelle integrazioni.

## Aggiornamenti nell'app

In **Impostazioni → Aggiornamenti** puoi controllare nuove versioni, leggere le
novità e scaricare il setup. Il canale ufficiale è già configurato nelle nuove build.
Dal setup 1.0.6 il controllo all'avvio e ogni sei ore e il download in background
sono attivi per impostazione predefinita, senza configurare nulla. Dalla 1.0.8,
quando Pezzhub rileva una nuova versione compare automaticamente un avviso
nell'app: mostra anche il download e propone il riavvio quando è pronto. Puoi
disattivarli separatamente nelle impostazioni. Quando il file è verificato,
compare «Riavvia e aggiorna»: l'installazione richiede conferma e l'avviso non
interrompe film o letture. Un aggiornamento già pronto si conserva anche dopo
la chiusura dell'app. Le scelte salvate nelle versioni precedenti vengono rispettate.
Gli aggiornamenti conservano la cartella dati con profili e impostazioni.

Pezzhub verifica lo SHA-256 del setup prima di avviarlo. Questo verifica
l'integrità rispetto al manifest; non sostituisce una firma digitale del produttore.
Non devi inserire token GitHub né creare un account GitHub per scaricare le release.

## Sicurezza e privacy

Questo repository non contiene database personali, credenziali, configurazioni
private delle estensioni o file multimediali degli utenti. Pezzhub non fornisce
contenuti: usa soltanto fonti e materiali per cui hai diritto di accesso.
Scarica gli eseguibili esclusivamente dalle release di questo repository.

Le licenze e le attribuzioni delle componenti di terze parti incluse nell'app
restano valide e sono distribuite con il pacchetto.

## Segnalazioni

Puoi aprire una [segnalazione](https://github.com/ceres077/pezzhub-releases/issues)
indicando versione di Pezzhub, versione di Windows e passaggi per riprodurre il problema.
Non allegare password, token, email private o collegamenti delle fonti contenenti credenziali.
