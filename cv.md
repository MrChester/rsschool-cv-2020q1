# Junior Developer Resume
##### 1. Yauheni Ramankou
##### 2. Contacts info:
* Phone number(Viber): +375447309450
* E-mail: iromankov2010@gmail.com
* skype: evgeni_romankov
* telegram: @yauheni_ramankou
##### 3. Summary
My main goals today is a start career as a junior front-end developer and after 5 years grow up to lead developer. it's important for me to be concentrated on learning process. I would like to reveal my potential in programming, time managment, get some speaking experience.
##### 5. Code examples
<details>
<summary>Expand this for more information</summary>

<pre>
function getLoveTrianglesCount(preferences = []) {
    let count = 0;
    let arrLength = preferences.length;

    for (let i = 0; i < arrLength; i++) {
        let firstSpichonee = preferences[i],
        firstSpichoneePosition = i + 1,
        thirdSpichoneePosition = firstSpichonee,
        thirdSpichonee = preferences[firstSpichonee - 1],
        secondSpichoneePosition = thirdSpichonee,
        secondSpichonee = firstSpichoneePosition;

        if (preferences[secondSpichoneePosition - 1] === secondSpichonee &&
            preferences[thirdSpichoneePosition - 1] === thirdSpichonee) {
            count++;
        }

    }

    return Math.floor(count / 3);
}
</pre>
</details>