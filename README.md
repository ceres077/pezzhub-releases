# Pezzhub

Le tue storie, tutte nello stesso posto.

Questo è il repository pubblico di **distribuzione e aggiornamento** di Pezzhub.
Qui vengono pubblicati gli installer e le note delle versioni. Il codice sorgente
dell'applicazione è mantenuto in un repository separato e non viene caricato qui.

## Scarica Pezzhub

Apri [l'ultima release](https://github.com/ceres077/pezzhub-releases/releases/latest)
e scarica `pezzhub-setup-X.Y.Z.exe` per Windows 64 bit.
Se non trovi ancora una release, la prima versione pubblica è in preparazione.

Il setup include il player MPV e non preinstalla estensioni video: puoi scegliere
e configurare le tue fonti nelle impostazioni. SoundHub è ancora in preparazione.
Una versione portatile, quando disponibile, è indicata tra i file della release.

## Tre spazi, un solo posto

- **MangaHub:** catalogo manga, libreria personale, reader e ripresa della lettura.
- **CineHub:** film, serie TV e anime, progressi, calendario e player.
- **SoundHub:** spazio dedicato alla musica, non ancora attivo.

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
