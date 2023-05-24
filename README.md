# CheckpointAlgorithmsanditselements

AlGORITHM 


algorithm

1. Initialize three counters.
One is the length of the sentence (starting at 0), one is the number of words (starting at 1, assuming at least one word), and one is the number of vowels (starting at 0).
2. Enter text as a string.
3. Iterate over each character in the string and do the following:

A. Increment the length counter for each character.
B. Increase the word count if the character is a space.
C. If the letter is a vowel (a, e, i, o, or u), increase the number of vowels.
D. If the character is a period, exit the loop.
4. Display the calculated sentence length, word count and vowel count. Here's the refined JavaScript code:


""
const readline = require('readline').createInterface({
entry:
process.stdin,
Exit:
process.stdout
});

readline.question('Please enter a statement:
', statement => {
Let lengthCounter = 0.
Let wordCounter = 1.
Bird counter = 0.

for (i = 0; i < record length; i++) {
const character = Set.charAt(i);
length counter ++;
if (char === '') {
wordCounter++;
} else if (/[aeiou]/i.test(character)) {
bird counter++;
} else if (character === '.') {
break down;
}
}

console.log('Record length:
${lengthCounter}');
console.log('Number of words:
${wordCounter}');
console.log('number of vowels:
${birdCounter}');

readline.close();
});Â 
