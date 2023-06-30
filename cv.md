# rsschool-cv
# Alik Krilov
# Contacts
* Address: Georgia, Tbilisi, Akhmeta street
* Phone: +995 551152877
* E-mail: sashakarosnik@gmail.com
* GitHub: [ripper20004](https://github.com/ripper20004)
* CodeWars: [ripper20004](https://www.codewars.com/users/ripper20004)
# About Me
I am 23 years old, I my ex life, i was a teacher of math. My analytical and problem-solving skills, honed through my mathematical education, have helped me develop a logical approach to coding that allows me to quickly identify and fix errors.
# Skills
* HTML
* CSS
* JavaScript (Fundamentals, ES6+, DOM, JSON, Asynchronous JavaScript)
* Git/GitHub
* Node.js (basic knowledge)
* Figma(for web development)
# Code Examples
function sortByVowels(...words) {
    function countVowels(word) {
        const vowels = ['a', 'e', 'i', 'o', 'u'];
        let count = 0;
        for (let i = 0; i < word.length; i++) {
            if (vowels.includes(word[i].toLowerCase())) {
                count++;
            }
        }
        return count;
    }

    return words.sort((a, b) => countVowels(a) - countVowels(b)).join(' ');
}
