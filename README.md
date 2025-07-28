### User Profile

```js
const profile = {
  name: 'Hariom Patidar',
  title: 'Frontend Developer | Cloud Enthusiast | Problem Solver',
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
