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
        
        
**Regex pour pigLatin :**   

        let as = s.split(' ').map(s=>[...s].reduce((a,b)=>a+b.charCodeAt(0)-96,0));
        return s.split(' ')[as.indexOf(Math.max(...as))];
        
**Créer un array de 0 à 10**   
        
         let list = [...Array(10).keys()];


        
        

[Retour à l'accueil](readme.md)
