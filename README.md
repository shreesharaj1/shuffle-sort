# shuffle-sort
Simple flexbox squares with the ability to shuffle and sort them in vanilla javascript.

Working url: https://shreesharaj1.github.io/shuffle-sort/

```
//Function to return a shuffled array which is used to order the flexboxes
    function shuffleArray() {
      const array = [ ...Array(9).keys() ];
      for (let i = array.length - 1; i > 0; i--) {
        const j = Math.floor(Math.random() * (i + 1));
        [array[i], array[j]] = [array[j], array[i]];
      }
      return array;
    }

```


