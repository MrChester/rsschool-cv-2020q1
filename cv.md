# Junior Developer Resume

##### 1. Yauheni Ramankou

##### 2. Contacts info:
* Phone number(Viber): +375447309450
* E-mail: iromankov2010@gmail.com
* skype: evgeni_romankov
* telegram: @yauheni_ramankou

##### 3. Summary
My main goals today is a start career as a junior front-end developer and after 5 years grow up to lead developer. it's important for me to be concentrated on learning process. I would like to reveal my potential in programming, time managment, get some speaking experience.

##### 4. Skills
> Skill levels: Beginner, Elementary, Pre-Intermediate, Intermediate, Upper Intermediate, Advanced

<details>
<summary>Languages</summary>

<pre>
  HTML(Pre-Intermediate)
  CSS(Pre-Intermediate)
  JavaScript(Pre-Intermediate)
  PHP(Beginner)
  SQL(Beginner)
  Python(Elementary)
</pre>

</details>
<details>
<summary>Prepocessors</summary>

<pre>
  Sass(Pre-Intermediate)
  Pug(Pre-Intermediate)
</pre>

</details>
<details>
<summary>Graphics</summary>

<pre>
  Photoshop(Pre-Intermediate)
  Figma(Pre-Intermediate)
  Zeplin(Pre-Intermediate)
</pre>

</details>
<details>
<summary>Task-runners</summary>

<pre>
  Gulp(Pre-Intermediate)
</pre>

</details>
<details>
<summary>Bundlers</summary>

<pre>
  Webpack(Elementary)
</pre>

</details>

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