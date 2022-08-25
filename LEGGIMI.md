# Swalstrap for Bootstrap 4
Un'alternativa a Swetalert e Bootbox, basata sulle componenti Modal e Toast di Bootstrap 4. Cerchi una versione per Bootstrap 5? [Vai qui](https://github.com/magicbruno/swalstrap5).

## Per iniziare 
Carica Swalstrap da CDN:

```
<script src="https://cdn.jsdelivr.net/npm/@magicbruno/swalstrap4@1.0.0/dist/js/swalstrap_all.min.js"></script>
```
swalstrap_all.js caricherà automaticamente il foglio di stile necessario e creerà un'istanza predefinita della classe Swalstrap chiamata Swal (verranno creati anche gli alias: swal, Sweelelert e sweelelert).

Per utilizzare Swalstrap devi applicare il metodo fire() all'istanza creata:
```
<script>
    Swal.fire('Wanderful!','Swalstrap is working!','success')
</script>
```
Se preferisci caricare separatamente il foglio di stile (o caricarne uno personalizzato)
```
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@magicbruno/swalstrap4@1.0.0/dist/css/swalstrap.min.css">
```
devi usare swalstrap.js:
```
<script src="https://cdn.jsdelivr.net/npm/@magicbruno/swalstrap4@1.0.0/dist/js/swalstrap.min.js"></script>
```
In questo caso è a tuo carico creare almeno un'istanza di swalstrap:
```
<script>
    // Create an instance 
    const mySwal = new Swalstrap();
    // Then use it for all your popups
    mySwal.fire('Wanderful!','Swalstrap is working!','success');
</script>
```
## Download

In alternativa è possibile installare il pacchetto tramite npm:
```
npm install @magicbruno/swalstrap4@1.0.0
```
clonare il repository git:
```
git clone https://github.com/magicbruno/SwalStrap4.git
```
o [scaricalo](https://github.com/magicbruno/SwalStrap4/archive/refs/heads/main.zip).

>### Avvertimento
>Swalstrap è ispirato a Sweelelert, non è un clone della componente. Le caratteristiche sono riprodotte non copiate.
>E quindi ci sono differenze. Controlla la documentazione e gli esempi.

- [Documentazione](https://magicbruno.github.io/SwalStrap4/api-it.html).
- [Esempi](https://magicbruno.github.io/SwalStrap4/basic-examples.html).
- [Esempio di personalizzazione](https://magicbruno.github.io/SwalStrap4/custumization.html).




