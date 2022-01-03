#Pavel Terno#
##Contact information##
**e-mail:** pt1999@mail.ru
**discord:** Pavel Terno (@PaHaNchickT) / ЗИЛИБОБКА-БЕЗУПРЕЧНЫЙ#4853

##About myself##
I graduated from St. Petersburg State University undergraduate degree in chemistry. During all my life I have love computer graphics, video-making tools and working in Photoshop. During the COVID pandemic, I realized that I wanted to broaden my horizons and began to take various courses. 
Now I work at an enterprise for the production of state standard samples, but in the future I would like to finally move to IT. I really like making sites and I would like to learn how to create complex and beautiful sites based on Javascript.
In my spare time I love to understand scripts to open and explore different unoppened game files. Then I making videos about content that I found and upload it on my YouTube channel called **Spidey Santa**.

##Code sample##
```Javascript
function primeValues(arr) {
    let out = [];
    arr.forEach(e1 => {
        let inp = [];
        let a = 1;
        inp.push(a)
        while (a<e1) {
            a++
            inp.push(a)
        }

        let x = 0;
        let y = 0;
        let z = 0;
        inp.forEach(e2 => {
            if (e1%e2 === 0) {
                if (e2===e1) {
                    x = 1;
                } else if (e2===1) {
                    y = 1;
                } else {
                    z = 1;
                }
            }
        })

        if (x===1 && z===0) {
            out.push(true);
        } else if (y===1 && z===0) {
            out.push(true);
        } else {
            out.push(false);
        }
    })
    return(out);
};
```
##Experience##
none

##Education##
*Saint-Petersburg state university (bachelor)
*Epam Learn, "HTML CSS Program with Personal Mentor"
*Epam Learn, "Basic JavaScript with Personal Mentor"
*Open education, "Web development"

##English level##
I have B2 level