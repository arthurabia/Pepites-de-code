<h1>Javascript</h1>


**Pour supprimer le plus petit élément d'un array de nombres :**

        function removeSmallest(arr) {
          return arr.filter((x,y) => y !== (arr.indexOf(Math.min(...arr))));
        }
        
        
        
**Pour supprimer l'élément unique d'un array de paires (avec le XOR) :**
        
        const solo = arr => arr.reduce((a, b) => a ^ b);
        
        
        
**Pour transformer un nombre en tableau de nombres :**
                
        Array.from(String(12345), Number);
        
        
**Regex pour trouver des mots contenant des chiffres (ou n'importe quel charactère) :**  

        \b\w*[\d]\w*\b
        
             
**Regex pour pigLatin :**     
        
        return str.replace(/(\w)(\w*)(\s|$)/g, "\$2\$1ay\$3")
        
        
**Itérer sur chaque lettre d'un mot d'une phrase :**   

        let as = s.split(' ').map(s=>[...s].reduce((a,b)=>a+b.charCodeAt(0)-96,0));
        
**Créer un array de 0 à 9 :**   
        
         let list = [...Array(10).keys()];

**Changer un true en 1 et false en 0 :**

        +true; // 1
        +false; // 0
        
 **Intégrer une variable dans un RegExp**       
        
        var regex = new RegExp(`\\d{${var}}`,'g')

 **Checker si une IP est valide**       
        
        const net = require('net');
        const isValidIP = (s) => net.isIP(s);
        
**Dire 10 fois 'no'**

        Array(10).fill('no')

[Retour à l'accueil](readme.md)
