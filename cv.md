# Anton Zakhar
Phone: +375 (29) 834-77-25
Email: e725f1d26ac8041f@gmail.com

## Summary
I have a passion for programming which I have demonstrated through months of self-study.  I also have a teachable attitude and a desire to learn (as evidenced by my continued self-study)

## Skills
* HTML
* CSS
* JavaScript
* Git

## Code example
````javascript
/**
* @param preferences - an array of integers. Indices of people, whom they love
* @returns number of love triangles
*/

module.exports = function getLoveTrianglesCount(preferences = []) {
	// your implementation
	let trianglesCount = 0;
	let fstLoves, secLoves, thdLoves;
	for (let i = 0; i < preferences.length; i++) {
		if (preferences[i] == i + 1) continue;
		
		fstLoves = preferences[i] - 1;
		secLoves = preferences[fstLoves] - 1;
		thdLoves = preferences[secLoves] - 1;
		
		if (thdLoves == i) {
			trianglesCount++;
		};
	};
	return trianglesCount / 3;
};
````

## Experience


## Education
* Mozyr State Polytechnical College 2006
* [Codecademy HTML & CSS course][1]

## English level
A2+ according to training.by score




[1]: https://www.codecademy.com/users/e725f1d26ac8041f/achievements
