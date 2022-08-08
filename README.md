# Swalstrap for Bootstrap 4
A Swetalert2 and Bootbox.js alternative build on Bootstrap 4 Modal and Toast components.

## Getting started 
Load Swalstrap form CDN:

```

<script src="https://cdn.jsdelivr.net/npm/@magicbruno/swalstrap4@1.0.0/dist/js/swalstrap_all.min.js"></script>
```
swalstrap_all.js will load automatically Swalstrap stylesheet and will create a default instance of Swalstrap class named Swal (and also aliased as swal, Sweetalert and sweetalert).

You can use Swalstrap applying fire method to the created instance:
```
<script>
    Swal.fire('Wanderful!','Swalstrap is working!','success')
</script>
```
If you prefer you can load Swalstrap stylesheet (or a customized one) separately:
```

<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@magicbruno/swalstrap4@1.0.0/dist/css/swalstrap.min.css">
```
and load swalstrap.js version:
```
<script src="https://cdn.jsdelivr.net/npm/@magicbruno/swalstrap4@1.0.0/dist/js/swalstrap.min.js"></script>
```
In this case you must create at least an instance of Swalstrap an then use it to open your popups:
```
<script>
    // Create an instance 
    const mySwal = new Swalstrap();
    // Then use it for all your popups
    mySwal.fire('Wanderful!','Swalstrap is working!','success');
</script>
```
## Downloading

Alternatively you can install package via npm:
```
npm install @magicbruno/swalstrap4@1.0.0
```
clone the git package:
```
git clone https://github.com/magicbruno/SwalStrap4.git
```
or [download it](https://github.com/magicbruno/SwalStrap4/archive/refs/heads/main.zip).

>### Warning
>Swalstrap is inspired to Sweetalert NOT a clone. Features are reproduced not copied.
>So there are differences. Please, watch documentation and test examples.

- [Documentation](https://magicbruno.github.io/SwalStrap4/api.html).
- [Examples](https://magicbruno.github.io/SwalStrap4/basic-examples.html).
- [Customization example](https://magicbruno.github.io/SwalStrap4/custumization.html).




