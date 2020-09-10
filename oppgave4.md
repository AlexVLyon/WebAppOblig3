# HIOF.NO
* Antall bilder på forsiden
    - const images = document.images
    - undefined
    - console.log(images)
    - VM984:1 HTMLCollection(4) [img, img, img, img]

     - Altså: <ins>4 bilder </ins>

* tid med og uten cache:
    - Med cache: 
        - Bare document HTML fila: 124 ms en gang, så 10ms, 10ms og 10ms da de ligger i cache.
        - Første:DOMContentLoaded: 493 ms Load: 708 ms
        - Andre: DOMContentLoaded: 584 ms Load: 775 ms
        - Tredje gang:   DOMContentLoaded: 377 ms Load: 545 ms
    - uten: 
        - første: DOMContentLoaded: 545 ms Load: 742 ms
        - andre: DOMContentLoaded: 409 ms Load: 650 ms
        - tredje: DOMContentLoaded: 391 ms Load: 622 ms

* Antall eksterne: 
    - 14

* Audit:
    - Performance: 96
    - Accessability: 87
    - Best Practices: 97
    - SEO:100


    * (Mobil
    - Performance: 62
    - Accesability:83
    - Best practices: 92
    - SEO: 97)

* Content type:
    - Request header:
    - Respone header: text/html;charset=utf-8
    

