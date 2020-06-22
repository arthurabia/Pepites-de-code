<h1>Javascript</h1>

        function removeSmallest(numbers) {
          return numbers.filter((x,y) => y !== (numbers.indexOf(Math.min(...numbers))));
        }
