### userProfile.js

```js
const profile = {
  name: 'Hariom Patidar',
  title: 'Frontend Developer | Problem Solver | Graphic Designer',
  skills: [
    'Python', 'C++', 'MySQL', 'JavaScript',
    'React', 'Tailwind CSS', 'Git', 'GitHub'
  ],
  hardWorker: true,
  quickLearner: true,
  problemSolver: true,
  hireable: function() {
    return (
      this.hardWorker &&
      this.quickLearner &&
      this.problemSolver
    );
  }
};
```
