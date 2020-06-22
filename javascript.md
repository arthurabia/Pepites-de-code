<h1>Javascript</h1>

Pour supprimer le plus petit élément d'un array de nombres :

        function removeSmallest(arr) {
          return arr.filter((x,y) => y !== (arr.indexOf(Math.min(...arr))));
        }

