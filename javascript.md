<h1>Javascript</h1>


*Pour supprimer le plus petit élément d'un array de nombres :*

        function removeSmallest(arr) {
          return arr.filter((x,y) => y !== (arr.indexOf(Math.min(...arr))));
        }
        
        
        
*Pour supprimer l'élément unique d'un array de paires (avec le XOR) : *
        
        const solo = arr => arr.reduce((a, b) => a ^ b);
        
        

[Retour à l'accueil](readme.md)
